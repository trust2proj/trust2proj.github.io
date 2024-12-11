<p align="center">
<img src="trust2logo.png" alt="TRust" width="500px"/>
</p>

## Overview

CertiCoq is a compiler for Gallina, the specification language of the [Coq proof assistant](https://coq.inria.fr/refman/index.html). CertiCoq targets Clight, a subset of the C language that can be compiled with any C compiler, including the [CompCert](http://compcert.org) verified compiler.

The goal of the CertiCoq project is to build an end-to-end verified compiler for Gallina, bridging the gap between formally verified source programs and their compiled executables.  

Large parts of the CertiCoq compiler have been verified whereas others are in the process of being verified.

You can find CertiCoq's souce code on [GitHub](https://github.com/CertiCoq/certicoq). CertiCoq is part of the [DeepSpec](https://deepspec.org) project.

## Publications 

- *[Formalizing x86-64 ISA in Isabelle/HOL: A Binary Semantics for eBPF JIT Correctness](https://link.springer.com/chapter/10.1007/978-981-96-0602-3_11)*, by Jiayi Lu, Shenghao Yuan, David Sanan, Yongwang Zhao. 10th Symposium on Dependable Software Engineering: Theories, Tools and Applications (SETTA 2024) , Hong Kong, China, November 26–28, 2024, pp. 197-216..


## Current Members (In alphabetical order)

[Rui Chang](https://person.zju.edu.cn/changrui), [Jun Liu](), [Jiayi Lu](), [David Sanan](https://davidsanan.github.io/), [Shenyi Yang](), [Zhibin Yang](), [Qiyuan Xu](), [Shenghao Yuan](https://shenghaoyuan.github.io/), [Zhuoruo Zhang](), [Yongwang Zhao](https://lvpgroup.github.io/)


## Documentation

The [CertiCoq Wiki](https://github.com/PrincetonUniversity/certicoq/wiki) has instructions for using the [CertiCoq plugin](https://github.com/PrincetonUniversity/certicoq/wiki/The-CertiCoq-plugin) to compile Gallina to C and interfacing with the generated C code.

The Wiki also gives an [overview](https://github.com/PrincetonUniversity/certicoq/wiki/The-CertiCoq-pipeline) of the compiler and its verification status. 


## Funding

The project has been supported by the National Science Foundation, grants CCF-1407790,  CCF-1407794,  CCF-2005545, and the CIFellows program.


## License 

TRust2 is open source and distributed under the [MIT license](LICENSE.md).

## Bugs 

We use github's [issue tracker](https://github.com/PrincetonUniversity/certicoq/issues) to keep track of bugs and feature requests.

<p align="center">
<a href="https://clustrmaps.com/site/1c34d" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=TTJIp2Z710NHOwDUNesA6uMqU3dX8kAJiL7b36c4rK0&cl=ffffff"></a>
</p>
