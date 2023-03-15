# lock-free
Something about lock-free.

## Why?
在学习 lock-free programming 的过程中，我看过视频、博客、书籍之类的学习资料，但是感觉非常的杂乱，所以我想写一本小书来梳理和总结学习的知识，内容大概包括：
* 内存一致性模型：线性一致性 & 顺序一致性 & 因果一致性 & 弱一致性。
* 宽松内存并发：relaxed behaviors( CPU/Compiler reordering ) & C11/C++11/LLVM/Rust memory model & promising semantics。
* 基本的同步模式：Positive Release/Acquire & Negative Release/Acquire & SeqCst interleaving 等。
* 什么是 lock-free？ lock-free 的好处？ lock-free 的设计模式？
* 无锁数据结构：Treiber’s stack & Michael-Scott’s queue 等等。
* 无锁数据结构的正确性定义？线性一致？如果证明？
* 并发垃圾内存回收：hazard pointers、EBR 等。

## When?

在完成 mit6.824 和 cmu15-445 后开始写，预计时间 7月-9月。
