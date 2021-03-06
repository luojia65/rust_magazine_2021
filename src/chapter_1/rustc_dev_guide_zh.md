---
pub_date: Sat, 30 Jan 2021 16:00:00 GMT
description: The translate of Rustc develop guide

---

# Rustc Dev Guide 中文翻译启动

作者：张汉东

---

[Rust编译器开发指南（Rustc Dev Guide）](https://github.com/rust-lang/rustc-dev-guide) 的中文翻译已经启动。因为原项目还在变动期，为了翻译方便，所以此翻译项目组织结构就不和原项目保持一致了。

- [官方原文在线阅读](https://rustc-dev-guide.rust-lang.org/)
- [中文版在线阅读](https://rustcrustc.github.io/rustc-dev-guide-zh/)
- [中文版翻译仓库地址](https://github.com/RustcRustc/rustc-dev-guide-zh)

#### 志愿者招募要求：

- 热爱 Rust，对 Rust 已经有一定了解
- 想深入了解 Rust 编译器
- 想为 Rust 编译器做贡献
- 业余时间充足

#### 如何参与

1. 认领感兴趣到章节
2. 找到对应到 markdown 文件
3. 直接发 PR
4. 或者帮忙审校别人的 PR

### Q & A:

1. 如何避免每个人翻译上的冲突呢，需要提前pr说翻译哪一章节吗？

    其实没必要怕冲突，对于参与翻译的来说，翻译本身也是一次学习过程，是有收获的。了解编译器工作原理对理解 Rust 概念也有帮助的。如果同一篇有多个翻译，那我这边选翻译更好的就可以了。

    这个项目倡导参与者自组织，但为了更加方便大家协作，还是来设置一个规则避免大家冲突。为了大家认领方便，特别创建了认领打卡的 issues，都去这里打一下卡：[【翻译认领】避免翻译冲突，来此打卡](https://github.com/RustcRustc/rustc-dev-guide-zh/issues/1)。

    如果你想发一个自己专属的「认领issue」也没问题，可以给该issue打上「已认领」标签。开一个独立的issue好处是可以有一个专属的地方讨论你翻译章节内容里的各种问题。

2. 为什么要翻译 《Rust 编译器开发指南》  ？

    年初的时候，我立下一个五年的 Flag ： 五年内要为 Rust 语言发 1000 个 PR。
    
    然后社区里的朋友就帮我做了一个计算：五年 1000 个，那么每年 200 个，那么一天就得 0.5 个。也有朋友说，Rust 的 PR 每次 Review 周期都很长，就算你能一年提 200 个 PR，官方也不可能给你合并那么多。

    这样的计算，确实很有道理。这个目标，确实很难完成。但其实这个 Flag 我并没有打算个人完成，而是想推动社区对 Rust 感兴趣对朋友一起完成。如果五年内，我能推动 1000 个人参与，那么每个人只提交一个 PR，那么这个 1000 个 PR 的 Flag 就轻松完成了。

    所以，翻译 《Rust 编译器开发指南》就成了我完成这个 Flag 的第一步。希望大家踊跃参与。