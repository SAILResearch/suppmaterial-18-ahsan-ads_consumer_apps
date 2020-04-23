This project contains the replication package of our paper _**"Studying Ad Library Integration Strategies of Top Free-to-Download Apps"**_

# Studying Ad Library Integration Strategies of Top Free-to-Download Apps

In-app advertisements have become a major revenue source for app developers in the mobile app ecosystem. 
Ad libraries play an integral part in this ecosystem as app developers integrate these libraries into their apps to display ads. In this paper, we study ad library integration strategies by analyzing 35,459 updates of 1,837 top free-to-download apps of the Google Play Store. We observe that ad libraries (e.g., Google AdMob) are not always used for serving ads - 22.5% of the apps that integrate Google AdMob do not display ads. They instead depend on Google AdMob for analytical purposes. Among the apps that display ads, we observe that 57.9% of them integrate multiple ad libraries. We observe that such integration of multiple ad libraries occurs commonly in apps with a large number of downloads and ones in app categories with a high proportion of ad-displaying apps. We manually analyze a sample of apps and derive a set of rules to automatically identify four common strategies for integrating multiple ad libraries. Our analysis of the apps across the identified strategies shows that app developers prefer to manage their own integrations instead of using off-the-shelf features of ad libraries for integrating multiple ad libraries. Our findings are valuable for ad library developers who wish to learn first hand about the challenges of integrating ad libraries.

# What does this replication package contain?

This replication package contains four artifacts:

1. The package name of the 63 idnetified ad libraries
2. The name of the show-ad methods of the 63 identified ad libraries
3. The Understand project of 8 investigated apps (2 apps in each of the four identified integration strategies)
4. The post id of the selected ad-related Stack Overflow posts for our manual analysis 

# How to use the Understand projects (.udb)?
**Step 1:** To use the understand projects, install the SciTools from the following link: https://scitools.com/ </br>
**Step 2:** Open an Understand Project of the studied ad library (File -> Open -> Project)</br>
**Step 3:** To visualize the relationship between packages and classes, right click on any of the package and select the option: Butterfly-Dependency Graph (Right click on any package -> Graphical Views -> Butterfly-Dependency Graph)
