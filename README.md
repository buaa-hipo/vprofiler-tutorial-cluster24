<font color=Blue>
When: 9:00 - 12:15, September 24th, 2024
<br />
Where: Room 406, Kobe International Conference Center in Kobe, Japan.
</font>

# Overview

Production software is becoming increasingly complex due to its deep software abstractions as well as the
sophisticated control and dataflows. Such software complexity usually leads to unexpected inefficiencies that
are hard to detect and locate by manual inspection. Fine-grained value profilers have revealed a promising way
to detect value-related inefficiencies with accurate root cause analysis for optimization guidance, which is vital
for achieving superior performance in numerous fields such as scientific simulation, machine learning, and
compiler optimization. 

In this tutorial, we will present a series of works on fine-grained value profilers that
have been published on top-tier conferences such as SC and ASPLOS from our group. After the presentation of each
fine-grained value profiler, we will provide hands-on exercises to acquaint the audience with the usage of each
profiler and show case the effectiveness of each profiler for guiding performance optimization. The value profilers (ZeroSpy and TrivialSpy) and framework (VClinic) demonstrated in this tutorial have already been [open-sourced](https://github.com/VClinic/VClinic) for public access.

This tutorial is expected to provide the audiences with the background of performance analysis,
illustrate the well known performance profilers and their limitations, and then present our fine-grained value profiling framework and tools. We hope after the tutorial the audiences can master
the usage of fine-grained value profilers to pinpoint software inefficiency, and be able to write
customized value profilers tailored to one’s need.

---

# Audience and Prerequisites

The target audience of the tutorial can be identified as two categories: 1) **application developers**,
people who are interested in optimizing the performance of their applications by leveraging the
strength of performance analysis tools, and 2) **tool developers**, people who are interested in building
customized value profilers to pinpoint unrevealed software inefficiencies for guiding performance
optimization.

The audience is expected to have a solid understanding of C/C++ programming languages, and a
basic understanding of computer architecture. Not required, but the audiences with a preliminary
experience of performance analysis tools are preferred.

---

# Hardware and Software Requirements

- **Hardware:** There is no special hardware required by the tutorial. The only thing we expect the
audiences is to bring his/her own laptops. The laptop should have decent computation, memory
and storage capability to access the remote server to run the hands-on exercises.

- **Software:** The necessary software environments have already been installed on the remote server. The audiences only need to copy the source files for
the hands-on exercises from the shared file system to their own workspaces. After that, they can start with
the hands-on exercises right away. Note that the audiences shall install their own favorite terminals in advance in order to access the remote server.

---

# Program

Stage | Content | Presenters | Schedule
-------- | ----- | ----- | ----
1 | Introduction of Performance Analysis <br>and Profiling Tools in HPC | Hailong Yang | 9:00-9:40
2 | Introduction of High Performance Cluster<br> at CNIC ([slide](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/Introduction%20of%20profiler%20in%20High%20Performance%20Cluster%20at%20CNIC.pdf))] | Shunde Li | 9:40-9:50
3 | Tutorial: A Portable and Efficient Framework<br> for Fine-grained Value Profilers (VClinic) Part 1 ([slide](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/CLUSTER24-Tutorial-VClinic.pdf)) | Xin You | 9:50-10:30
4 | Break |  | 10:30-10:45 
5 | Tutorial: A Portable and Efficient Framework<br> for Fine-grained Value Profilers (VClinic) Part 2 ([slide](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/CLUSTER24-Tutorial-VClinic.pdf)) | Xin You | 10:45-10:55
6 | Tutorial: Exploring Software Inefficiency<br> with Redundant Zeros (ZeroSpy) ([slide](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/CLUSTER24-tutorial-zerospy.pdf)) | Kelun Lei | 10:55-11:35
7 | Tutorial: Identifying Software Triviality<br> via Fine-grained and Dataflow-based Value<br> Profiling (TrivialSpy) ([slide](https://github.com/buaa-hipo/vprofiler-tutorial-cluster24/blob/main/Cluster24-tutorial-trivialspy.pdf)) | Zhibo Xuan | 11:35-12:15

---

# Organizers

- Hailong Yang, Beihang University
- Xin You, Beihang University
- Kelun Lei, Beihang University
- Zhibo Xuan, Beihang University
- Shunde Li, Computer Network Information Center, Chinese Academy of Science

---

# Related Publications

- Xin You, Hailong Yang, Zhongzhi Luan, Depei Qian, Xu Liu. [ZeroSpy: Exploring Software Inefficiency with Redundant Zeros](https://ieeexplore.ieee.org/document/9355303). Proceedings of International Conference for High Performance Computing, Networking, Storage and Analysis (SC). 2020: 1-14.
- Xin You, Hailong Yang, Kelun Lei, Zhongzhi Luan, Depei Qian. [VClinic: A Portable and Efficient Framework for Fine-Grained Value Profilers](https://dl.acm.org/doi/10.1145/3575693.3576934). Proceedings of ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS). 2023: 892-904.
- Xin You, Hailong Yang, Kelun Lei, Zhongzhi Luan, Depei Qian. [TrivialSpy: Identifying Software Triviality via Fine-grained and Dataflow-based Value Profiling](https://dl.acm.org/doi/10.1145/3581784.3607052). Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC). 2023: 1-13.

---

# Questions

For questions about this tutorial, please contact Xin You (youxin2015@buaa.edu.cn).
