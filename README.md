# Lab8-Starter

Lab Partners: None

### Page URL

### About graceful degradation and service workers:
Graceful degredation refers to the practice of designing a system to perform to its highest quality on fully capable platforms, but still retain at least basic functionality (even with reduced quality or features) on compromised or less capable systems. This relates to the concept of service workers because when a user is offline or has extremely poor network connection, that is a compromised or less capable system. The way service workers uphold graceful degredation is by storing previous network responses in the browser and returning them when the same request is made later on. This way, even if the user is offline, things like HTML/CSS/JS and Image files are still able to display, providing at least foundational functionality.

![img](pwa.png)