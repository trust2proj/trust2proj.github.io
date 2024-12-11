<p align="center">
<img src="trust2logo.png" alt="TRust" width="500px"/>
</p>

## Overview

CertiCoq is a compiler for Gallina, the specification language of the [Coq proof assistant](https://coq.inria.fr/refman/index.html). CertiCoq targets Clight, a subset of the C language that can be compiled with any C compiler, including the [CompCert](http://compcert.org) verified compiler.

The goal of the CertiCoq project is to build an end-to-end verified compiler for Gallina, bridging the gap between formally verified source programs and their compiled executables.  

Large parts of the CertiCoq compiler have been verified whereas others are in the process of being verified.

You can find CertiCoq's souce code on [GitHub](https://github.com/CertiCoq/certicoq). CertiCoq is part of the [DeepSpec](https://deepspec.org) project.

## Publications 

- *[Formalizing x86-64 ISA in Isabelle/HOL: A Binary Semantics for eBPF JIT Correctness](https://doi.org/10.1145/3485491)*, by Jiayi Lu, Shenghao Yuan*, David Sanan, Yongwang Zhao. 10th Symposium on Dependable Software Engineering: Theories, Tools and Applications (SETTA 2024) , Hong Kong, China, November 26–28, 2024, pp. 197-216..


## Current Members (In alphabetical order)

[Rui Chang](https://person.zju.edu.cn/changrui), [Jun Liu](), [Jiayi Lu](), [David Sanan](https://davidsanan.github.io/), [Shenyi Yang](), [Zhibin Yang](), [Qiyuan Xu](), [Shenghao Yuan](https://shenghaoyuan.github.io/), [Zhuoruo Zhang](), [Yongwang Zhao](https://lvpgroup.github.io/)


## Documentation

The [CertiCoq Wiki](https://github.com/PrincetonUniversity/certicoq/wiki) has instructions for using the [CertiCoq plugin](https://github.com/PrincetonUniversity/certicoq/wiki/The-CertiCoq-plugin) to compile Gallina to C and interfacing with the generated C code.

The Wiki also gives an [overview](https://github.com/PrincetonUniversity/certicoq/wiki/The-CertiCoq-pipeline) of the compiler and its verification status. 


## Publications 

- *[Compiling with Continuations, Correctly](https://doi.org/10.1145/3485491)*, by Zoe Paraskevopoulou and Anvay Grover, Proc. ACM Program. Lang. Vol. 5, No. OOPSLA, Article 114 (29 pages), October 2021.

- *[Compositional Optimizations for CertiCoq](https://doi.org/10.1145/3473591)*, by Zoe Paraskevopoulou, John M. Li, and Andrew W. Appel, Proc. ACM Program. Lang. Vol. 5, No. ICFP, Article 86 (30 pages), August 2021.

- *[Deriving Efficient Program Transformations from Rewrite Rules](https://doi.org/10.1145/3473579)*, by John M. Li and Andrew W. Appel, Proc. ACM Program. Lang. Vol. 5, No. ICFP, Article 74 (29 pages), August 2021.

- *[Coq Coq Correct! Verification of Type Checking and Erasure for Coq, in Coq](https://metacoq.github.io/coqcoqcorrect)*, by Matthieu Sozeau, Simon Boulier, Yannick Forster, Nicolas Tabareau and Théo Winterhalter. Proc. ACM Program. Lang. Vol. 4, No. POPL, Article 8 (28 pages), August 2021.

- *[Certified Code Generation from CPS to C](https://www.cs.princeton.edu/~appel/papers/CPStoC.pdf)*, by Olivier Savary Belanger, Matthew Z. Weaver, and Andrew W. Appel, October 2019.

- *Certifying Graph-Manipulating C Programs via Localizations within Data Structures*. Shengyi Wang, Qinxiang Cao, Anshuman Mohan, and Aquinas Hobor. OOPSLA: Conference on Object-Oriented Programming Systems, Languages, and Applications (OOPSLA 2019), Athens, Greece, October 2019.

- *Closure Conversion is Safe for Space*. Zoe Paraskevopoulou and Andrew W. Appel. Proceedings of the ACM on Programming Languages, vol. 3, no. ICFP, article 83, 29 pages, doi 10.1145/3341687, August 2019.

- *Shrink Fast Correctly!*. Olivier Savary Belanger and Andrew W. Appel. Proceedings of International Symposium on Principles and Practice of Declarative Programming (PPDP'17), pages 49-60, ACM Press, October 2017 (PPDP’17).

- *CertiCoq: A verified compiler for Coq*. Abhishek Anand, Andrew Appel, Greg Morrisett, Zoe Paraskevopoulou, Randy Pollack, Olivier Savary Belanger, Matthieu Sozeau, and Matthew Weaver. In CoqPL'17: The Third International Workshop on Coq for Programming Languages, January 2017.


## Funding

The project has been supported by the National Science Foundation, grants CCF-1407790,  CCF-1407794,  CCF-2005545, and the CIFellows program.


## License 

TRust2 is open source and distributed under the [MIT license](LICENSE.md).

## Bugs 

We use github's [issue tracker](https://github.com/PrincetonUniversity/certicoq/issues) to keep track of bugs and feature requests.

<p align="center">
<a href="https://clustrmaps.com/site/1c34d" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=TTJIp2Z710NHOwDUNesA6uMqU3dX8kAJiL7b36c4rK0&cl=ffffff"></a>
</p>
