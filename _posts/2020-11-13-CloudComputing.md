---
layout: post
title:  "3. Cloud Computing and Distributed Systems"
date:   2020-11-13  18:14:00 08:00
categories: Self Study Notes
usemathjax: true
---
1. Develop an appreciation (architecture and operations) of planet-scale cluster managers and orchestrators. In general read [wsc3e] to get an overview of the architecture and operations of large-scale cloud computing systems.
    1. Based on loc and language used (C++) [Mesos][mesos], should have minimum learning curve for me to understand. Start with the paper [Mesos NSDI-2011 paper][mesos-paper].
    2. [Kubernetes][kubernetes] is a more widely used cluster manager (or more narrowly container orchestration system) than [Mesos][mesos], implemented in Go and backed by Google. Read the [Borg][borg-paper] paper to understand some of the key architectural details.
    3. [KubeEdge][Kubedge] is a new container orchestration platform to handle edge computing use cases.

2. Understanding the workload distributions. Some of the papers [tail at scale][tailAtScale] and [sources of tail latency][tailSources] are a must read.

3. Learning for distributed systems
    1. [Ericcson's Graph Machine Learning][gericssonML]

4. Time Series Database
    1. [Prometheus][prometheus] is one of most popular and intuitive time-series database implemented in Go.

[mesos]: http://mesos.apache.org/
[kubernetes]: https://kubernetes.io/
[prometheus]: https://prometheus.io/
[gericssonML]: https://www.ericsson.com/en/blog/2020/3/graph-machine-learning-distributed-systems
[Kubedge]: https://kubeedge.io/en/
[mesos-paper]: https://nusu-my.sharepoint.com/personal/e0146321_u_nus_edu/Documents/Books/CS/CloudComputing/Papers_CloudComputingOSMicroservices/Mesos%20A%20Platform%20for%20Fine-Grained%20Resource%20Sharing%20in%20the%20Data%20Center.pdf
[borg-paper]: https://nusu-my.sharepoint.com/:b:/r/personal/e0146321_u_nus_edu/Documents/Books/CS/CloudComputing/Papers_CloudComputingOSMicroservices/BorgOmegaKubernetes.pdf?csf=1&web=1
[wsc3e]: https://nusu-my.sharepoint.com/personal/e0146321_u_nus_edu/Documents/Books/CS/CloudComputing/Papers_CloudComputingOSMicroservices/WSC3e.pdf
[tailAtScale]: https://nusu-my.sharepoint.com/:b:/r/personal/e0146321_u_nus_edu/Documents/Books/CS/CloudComputing/Papers_CloudComputingOSMicroservices/TailLatencyComputingSystems/The%20tail%20at%20scale.pdf?csf=1&web=1&e=rHjf8N
[tailSources]: https://nusu-my.sharepoint.com/:b:/r/personal/e0146321_u_nus_edu/Documents/Books/CS/CloudComputing/Papers_CloudComputingOSMicroservices/TailLatencyComputingSystems/Tales%20%20of%20%20the%20Tail-Hardware%20OS%20%20and%20Application-level%20Sources%20%20of%20Tail%20Latency.pdf?csf=1&web=1&e=32z5VV