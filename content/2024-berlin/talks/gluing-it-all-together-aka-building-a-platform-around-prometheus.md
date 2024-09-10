---
title: "“Gluing it all together” aka building a platform around Prometheus"
---

## “Gluing it all together” aka building a platform around Prometheus

In a larger setup it becomes cumbersome for everyone to manage their own Prometheus instance, think about its HA, meta monitoring, how to do alerting, service discovery, getting some global view, visualizing the data, authentication and maintaining all of this. Even the prometheus-operator helps mostly on the happy path, but when it comes to debugging, it’s yet another level of complexity.

This talk will show you the things you have to solve to build your own  “monitoring platform” on top of Prometheus without (almost) any cloud services for over 500 developers in tens of different teams running apps in more than 150 k8s clusters so they just “don’t have to care”.

You will see the rainbow and unicorns of the so-called "platform engineering", but also that the rainbow does not always end with a pot of gold and even unicorns need to sometimes 💩


### Speakers
[Martin Chodur](../../speakers/martin-chodur)

<img src="https://sessionize.com/image/8b9e-400o400o1-pgCHc6JQyqQ5giDgZ6AFsV.jpg" style="width: 100px; border-radius: 50%" alt="Martin Chodur Profile Picture"/>

