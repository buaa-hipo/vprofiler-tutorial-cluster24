# Identifying Software Inefficiency with Fine-grained Value Profilers

Production software is becoming increasingly complex due to its deep software abstractions as well as the
sophisticated control and dataflows. Such software complexity usually leads to unexpected inefficiencies that
are hard to detect and locate by manual inspection. Fine-grained value pro#lers have revealed a promising way
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
fine-grained and dataflow-based value pro#ler to effectively identify software triviality with optimization
potential estimation. With the help of data!ow analysis, TrivialSpy can detect software trivialities of heavy
operation, trivial chain, and redundant backward slice. In addition, TrivialSpy can identify trivial breakpoints
that combine multiple trivial conditions for more optimization opportunities. After the presentation of each
fine-grained value profiler, we will provide hands-on exercises to acquaint the audience with the usage of each
profiler and show case the effectiveness of each profiler for guiding performance optimization. The framework
and value profilers demonstrated in this tutorial have already been open-sourced for public access

