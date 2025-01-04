---
title: "Information-Flow Analysis for Mobile and Wearable Device Security and Privacy"
date: 2021-07-07
time: 3PM
presenter: "jorge-blasco-alis"
youtube: "oU5R7qu-M3w"
zoom-link: "https://york-ac-uk.zoom.us/j/94491221399?pwd%3DdW1lbmxUanhUdCtGOWg2ZjFpOXpMQT09"
zoom-id: "94491221399"
zoom-password: "071545"
---

Information flow analysis techniques have been widely applied to the analysis of mobile applications. In this talk we will explore how they can be used to study the security and privacy properties in mobile-to-IoT and wearable device interactions. For this, we separate the interaction methods in two main categories: those enabled by the operating system in the form of proprietary APIs (Android Wear) and those that are done directly at a lower level using wireless protocols such as Bluetooth Low Energy. We show how we can instrument Google Play APIs to perform information flow analysis over Android Wear API calls. With this, we can identify what information is being exchanged between the mobile application and its wearable counterpart, being able to reason about possible privacy leakages. When looking at lower level interactions, we analyse how Android implements its Bluetooth Low Energy stack and identify an issue that would allow any application with Bluetooth permissions to access any BLE connected device without the users’ consent. We measure how many BLE-enabled apps are affected by this and provide mitigation recommendations to stakeholders in the BLE ecosystem. 

Relevant publications: [RAID 2020](https://www.usenix.org/conference/raid2020/presentation/tileria) and [USENIX Security 2019](https://www.usenix.org/conference/raid2020/presentation/tileria)
