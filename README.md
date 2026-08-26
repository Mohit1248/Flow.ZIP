# Flow.ZIP

## Introduction

**Flow.ZIP** is a backward-compatible header compression mechanism designed for existing data center networks. Our solution leverages a combination of last-hop network offload and MPLS support, both of which are ubiquitous in modern data center deployments. Flow.ZIP overcomes scalability limitations in these components by selectively and intelligently coordinating compression for a subset of flows. Doing so, Flow.ZIP achieves up to 58% reduction in average flow completion time on real-world data center workloads

[*Our paper*](https://yindazhang.github.io/files/FlowZip.pdf) will appear in SIGCOMM 2026.

## About this repo

- `similation/`: Contains code for the ns-3 simulations of Flow.ZIP.
- `testbed/`: Contains code for the implementation of Flow.ZIP.
- More details can be found within the respective folders.