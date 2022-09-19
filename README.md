# 用 Rust 开发编程语言

引个流先：

- *KusionStack一站式可编程配置技术栈(Go实现): <https://github.com/KusionStack/kusion>*
- *KusionStack内置的KCL配置语言(Rust实现): <https://github.com/KusionStack/KCLVM>*

## 序言

写这个电子书是因为最近在做 KusionStack、KCLVM 项目中编译器研发的相关工作，发现虽然编译器的基本原理不变，但是将学校中学习的内容应用在工作中开发编译器还远远不够，想要创造一种新的编程语言不仅仅需要了解编译原理，还需要了解与编译器相关的整个周边生态，因此，在[柴大](https://github.com/chai2010)的建议下打算开一个坑，通过一个玩具语言 Tiny-Lang，将整个语言编译生态的开发过程串联起来，使用Rust语言开发一个完成的编译工具集。

KCLVM 是我们在 Kusion 这个项目中使用 Rust 开发的语言编译器，书中的部分内容在这个项目中也有对应的应用。对云原生生态、技术感兴趣的同学可以了解下  &#x1F449; [KusionStack](https://github.com/KusionStack/kusion) 这个项目；对 Rust、编程语言、编译器感兴趣的同学可以看下 &#x1F449; [KCLVM](https://github.com/KusionStack/KCLVM)。

最后，这些文章中的内容大部分是我在日常开发过程中进行的总结和凝练，本人水平有限，所以可能会有一些不准确甚至错误的地方，也欢迎大家提 PR/Issue/Discussion，或者下方扫码加群讨论。如果对 Rust 源码有自己分析和见解，同样欢迎提 PR 投稿。

---

## 电子书

目标：使用 Rust 为一个玩具语言 Toy-Lang 开发一个完整的编译工具生态。

![cover](cover.png)

- 代码仓库: [https://github.com/awesome-kusion/rust-toy-lang-book](https://github.com/awesome-kusion/rust-toy-lang-book)
- 在线阅读: [https://awesome-kusion.github.io/rust-toy-lang-book](https://awesome-kusion.github.io/rust-toy-lang-book)

## 目录

---

[![Star History Chart](https://api.star-history.com/svg?repos=awesome-kusion/rust-toy-lang-book&type=Date)](https://star-history.com/#awesome-kusion/rust-toy-lang-book&Date)

