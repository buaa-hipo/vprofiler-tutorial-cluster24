<font color=Blue>
When: September 24th, 2024
<br />
Where: Kobe International Conference Center in Kobe, Japan.
</font>




Slides will be open soon.

# Audience

The target audience of the tutorial can be identified as two categories: 1) application developers,
people who are interested in optimizing the performance of their applications by leveraging the
strength of performance analysis tools, and 2) tool developers, people who are interested in building
customized value profilers to pinpoint unrevealed software inefficiencies for guiding performance
optimization.

# Overview

Production software is becoming increasingly complex due to its deep software abstractions as well as the
sophisticated control and dataflows. Such software complexity usually leads to unexpected inefficiencies that
are hard to detect and locate by manual inspection. Fine-grained value profilers have revealed a promising way
to detect value-related inefficiencies with accurate root cause analysis for optimization guidance, which is vital
for achieving superior performance in numerous fields such as scientific simulation, machine learning, and
compiler optimization. In this tutorial, we will present a series of works on fine-grained value profilers that
have been published on top-tier conferences such as SC and ASPLOS from our group. First, we will introduce
the background of performance analysis, widely used performance profilers, as well as their limitations. Then,
we will present VClinic, a portable and efficient fine-grained value profiling framework for analyzing highly
optimized binaries on both X86 and ARM platforms. VClinic exploits operand-centric two-level designs in its
implementation to provide the common building blocks required for building various value profilers. After
that, we will present ZeroSpy, a fine-grained profiler to pinpoint and quantify the redundant zeros during
program execution. ZeroSpy identifies redundant zeros caused by both inappropriate use of data structures
and useless computation. ZeroSpy also provides intuitive optimization guidance by revealing the locations
where the redundant zeros happen with source lines and calling contexts. Finally, we will present TrivialSpy, a
fine-grained and dataflow-based value profiler to effectively identify software triviality with optimization
potential estimation. With the help of dataflow analysis, TrivialSpy can detect software trivialities of heavy
operation, trivial chain, and redundant backward slice. In addition, TrivialSpy can identify trivial breakpoints
that combine multiple trivial conditions for more optimization opportunities. After the presentation of each
fine-grained value profiler, we will provide hands-on exercises to acquaint the audience with the usage of each
profiler and show case the effectiveness of each profiler for guiding performance optimization. The framework
and value profilers demonstrated in this tutorial have already been open-sourced for public access

This tutorial is expected to provide the audiences with the background of performance analysis,
illustrate the well known performance profilers and their limitations, and then present our fine-grained value profiling framework and tools. We hope after the tutorial the audiences can master
the usage of fine-grained value profilers to pinpoint software inefficiency, and be able to write
customized value profilers tailored to one’s need.

# Hardware and Software Requirements

- **Hardware:** There is no special hardware required by the tutorial. The only thing we expect the
audiences is to bring his/her own laptops. The laptop should have decent computation, memory
and storage capability to run the fine-grained value profilers and hands-on exercises.
- **Software:** We will provide USB drivers that contain all the software required by the tutorial.
Speciffically, we will ask the audiences to install a virtual machine (e.g., virtualbox) if they have
not. Then, a virtual machine image is provided, which has the value profiling framework and tools
presented in the tutorial installed by default. The image also contains the necessary source files for
the hands-on exercises. The audiences can load the image into their virtual machine, and start with
the hands-on exercises right away.

# Prerequisite Background

The audience is expected to have a solid understanding of C/C++ programming languages, and a
basic understanding of computer architecture. Not required, but the audiences with a preliminary
experience of performance analysis tools are preferred.

# Organizers

- Hailong Yang, Beihang University
- Xin You, Beihang University
- Kelun Lei, Beihang University

# Questions

For questions about this tutorial, please contact Hailong Yang and Xin You.

# Related Publications

- Xin You, Hailong Yang, Zhongzhi Luan, Depei Qian, Xu Liu. ZeroSpy: exploring software inefficiency with redundant zeros[C] International Conference for High Performance Computing, Networking, Storage and Analysis (SC). IEEE, 2020: 1-14.
- Xin You, Hailong Yang, Kelun Lei, Zhongzhi Luan, Depei Qian. VClinic: A Portable and Efficient Framework for Fine-Grained Value Profilers[C]. Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS), Volume 2. 2023: 892-904.
- Xin You, Hailong Yang, Kelun Lei, Zhongzhi Luan, Depei Qian. TrivialSpy: Identifying Software Triviality via Fine-grained and Dataflow-based Value Profiling[C]. Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis (SC). 2023: 1-13.


# Program

Phase | Content
-------- | -----
1 | Background (45 min)
2 | Introduction of VClinic with hand-on tutorial (50 min)
3 | Introduction of Zerospy with hand-on tutorial (50 min)
4 | Introduction of TrivialSpy with hand-on tutorial (50 min)