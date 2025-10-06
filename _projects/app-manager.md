---
layout: project
title: "Project: App Manager"
name: App Manager
description: "A suite of tools and utilities for Android operating system that helps the users improve their privacy and usability."
priority: 1
selected: true
link: https://github.com/MuntashirAkon/AppManager
---

[App Manager](https://github.com/MuntashirAkon/AppManager) is a suite of tools and utilities for Android operating system that helps the users improve their privacy and usability by managing the applications. Many applications come with privacy-invasive advertisements, trackers and permissions which cannot be controlled in a trivial way because neither the application nor the operating system expose such features to the end users. App Manager can provide these features by utilizing Android hidden APIs when the privileged mode is enabled. During the initialization, it can adjust the [threat model](https://owasp.org/www-community/Threat_Modeling) based on the features available in the operating system using a greedy-like approach (e.g., it runs in root mode when the device is rooted). The users can later adjust it based on their own set of requirements. Another important objective of App Manager is sharing insights about an application with its user to improve their understanding of the application. This facilitates proactive prevention of privacy and security incidents which are ever on the increase in the Android platform. It encourages the users to ask questions regarding certain behaviour of an application or, in some cases, certain features offered by the platform itself. As an example of awareness spread by App Manager, a user discovered [a critical privacy leak](https://github.com/GrapheneOS/os-issue-tracker/issues/1634) in Android operating system. App Manager is also built with cutting-edge and ever-evolving design concepts such as Material Design 3 with some home-made designs to fill the remaining gaps on those concepts. It also has an extensive [user manual](http://muntashirakon.github.io/AppManager/) that is available both online and offline inside the application. Features, design principles, and goals has made it quite popular among the Android users as the number of users are constantly growing with more than 550,000 downloads on GitHub alone with more than 12,000 followers in various social media channels. I also raised more than $5,000 for the application using [Open Source Collective](https://opencollective.com/muntashir).

![App Manager banner]({{ '/images/am.png' | relative_url }})
