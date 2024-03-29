# 0. 前言 | Benny Huo 的专栏

[https://www.bennyhuo.com/book/swift-coroutines/00-foreword.html](https://www.bennyhuo.com/book/swift-coroutines/00-foreword.html)

经过几年的打磨，Swift 已经成为一门成熟度非常高的语言。

作为 Kotlin 布道师，Android 从业者，我本人对 Swift 的发展也保持了持续的关注。Swift 与 Kotlin 在外形上有着极高的相似度，学习 Swift 的一些特性有时候也可以帮助我更好的理解 Kotlin 的语法。

在协程这个特性上，Kotlin 还是走得比较靠前，我当时在写《深入理解 Kotlin 协程》这本书的时候也查阅过 Swift 的一些第三方协程实现，不过当时因为官方一直都没有消息，因此在书中没有提及。

这下好了，Swift 终于在 5.5 当中正式支持了协程，作为现代语言必备的特性，Swift 总算是补齐了自己的短板。

我计划写几篇文章来介绍一下 Swift 协程的特性，内容会以 Swift 协程的基本概念、语法设计、使用场景等方面为基础展开，也会与大前端开发者常见的 Kotlin、JavaScript 做对比，希望能给大家一个更多元化的视角来理解这个语法特性。

> 说明：最初在 Xcode 13.0 刚发布的时候，Swift 协程需要 iOS 15.0、macOS 12.0 以上；随后在 Xcode 13.2 发布以后，最低版本要求降低到 iOS 13.0、 macOS Catalina（10.15），这样看来线上项目也终于有机会尝试这个新特性了。
> 

## 关于作者

**霍丙乾 bennyhuo**，Google 开发者专家（Kotlin 方向）；**《深入理解 Kotlin 协程》** 作者（机械工业出版社，2020.6）；**《深入实践 Kotlin 元编程》** 作者（机械工业出版社，预计 2023 Q3）；前腾讯高级工程师，现就职于猿辅导

- GitHub：https://github.com/bennyhuo
- 博客：https://www.bennyhuo.com
- bilibili：**[霍丙乾 bennyhuo**open in new window](https://space.bilibili.com/28615855)
- 微信公众号：**霍丙乾 bennyhuo**