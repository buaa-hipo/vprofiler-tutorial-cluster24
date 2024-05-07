# Identifying So!ware Inefficiency with Fine-grained Value Profilers

Production software is becoming increasingly complex due to its deep software abstractions as well as the
sophisticated control and data !ows. Such software complexity usually leads to unexpected ine"ciencies that
are hard to detect and locate by manual inspection. Fine-grained value pro#lers have revealed a promising way
to detect value-related ine"ciencies with accurate root cause analysis for optimization guidance, which is vital
for achieving superior performance in numerous #elds such as scienti#c simulation, machine learning, and
compiler optimization. In this tutorial, we will present a series of works on #ne-grained value pro#lers that
have been published on top-tier conferences such as SC and ASPLOS from our group. First, we will introduce
the background of performance analysis, widely used performance pro#lers, as well as their limitations. Then,
we will present VClinic, a portable and e"cient #ne-grained value pro#ling framework for analyzing highly
optimized binaries on both X86 and ARM platforms. VClinic exploits operand-centric two-level designs in its
implementation to provide the common building blocks required for building various value pro#lers. After
that, we will present ZeroSpy, a #ne-grained pro#ler to pinpoint and quantify the redundant zeros during
program execution. ZeroSpy identi#es redundant zeros caused by both inappropriate use of data structures
and useless computation. ZeroSpy also provides intuitive optimization guidance by revealing the locations
where the redundant zeros happen with source lines and calling contexts. Finally, we will present TrivialSpy, a
#ne-grained and data!ow-based value pro#ler to e$ectively identify software triviality with optimization
potential estimation. With the help of data!ow analysis, TrivialSpy can detect software trivialities of heavy
operation, trivial chain, and redundant backward slice. In addition, TrivialSpy can identify trivial breakpoints
that combine multiple trivial conditions for more optimization opportunities. After the presentation of each
#ne-grained value pro#ler, we will provide hands-on exercises to acquaint the audience with the usage of each
pro#ler and show case the e$ectiveness of each pro#ler for guiding performance optimization. The framework
and value pro#lers demonstrated in this tutorial have already been open-sourced for public access

