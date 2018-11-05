# Kotlin-Index
## 搜集Kotlin的博客，文档，分类索引出来，方便查找



在学习Kotlin语言的过程中，发现了很多不错的学习资源，包括基本语法、一些惯例或者好的用法、RxKotlin、DSL、用Kotlin写gradle脚本、android KTX等等。

有关Kotlin的好文已经越来越多，初学者实在没有必要去自己写一些文档，但是文档的搜集和分类还是要做，所以就有了本篇索引

————————————————————————————————————————————————————

 - 官网中文版： https://www.kotlincn.net/docs/reference/
 -  EduTools 一个JetBrains IDEA插件，可以安装完后在File->Browse Courses中搜索Kotlin Koans，包含很多测试题，用来测试自己的语法很好
 - Kotlin Android Extensions 一个简化代码的插件 ： https://kotlinlang.org/docs/tutorials/android-plugin.html
 - ReactiveX/RxKotlin  https://github.com/ReactiveX/RxKotlin
 - github上的awesome Kotlin资源整理汇总： https://github.com/KotlinBy/awesome-kotlin
 - githubwing/GankClient-Kotlin wing写的Gank客户端： https://github.com/githubwing/GankClient-Kotlin
 - 官网给出的更多资源 ： https://kotlinlang.org/docs/resources.html
 - android develop官网推荐的kotlin学习资源  https://developer.android.com/kotlin/resources






### 感觉一些写的不错的博客：

 

#### 语法相关
 
- 官网 一些好的惯例：https://kotlinlang.org/docs/reference/idioms.html
- JakeWharton 大神写的博客 [Android Kotlin Guides] (https://android.github.io/kotlin-guides/)
 - [用Kotlin去提高生产力:汇总Kotlin相对于Java的优势，以及怎么用Kotlin去简洁、务实、高效、安全开发的Tips]( https://github.com/heimashi/kotlin_tips) 
- [31 天，从浅到深轻松学习 Kotlin](https://mp.weixin.qq.com/s?__biz=MzAwODY4OTk2Mg==&mid=2652046391&idx=1&sn=46efa48076a4533f355af6351b76c012&chksm=808ca472b7fb2d64afc89edf6beba1540e5a6ff49ad6346bd5d72b3957fa5f9323e07b8aab03&mpshare=1&scene=24&srcid=0529N1WlH39WIW7deU1t5Gl1&key=b9d043dd6cb75d29c59a34f21c9ef5f00d6661af000e38b630272a95cf61e10b8e4d27e81d9a0f512c5ce2d0330c7550dc0f0035d988d8eb7b68cd53e1dc104a23d5297459068a5fe44e35f6f370a829&ascene=0&uin=MzE4NzMxMTM1&devicetype=iMac+MacBookPro13%2C3+OSX+OSX+10.13.3+build(17D47)&version=12020510&nettype=WIFI&lang=ko&fontScale=100&pass_ticket=FaGLTv1uvlqk1nYxnoFqbLSHDIdr3lGMbYWugIHF9KqwF9ljdGLA7hYQOMaMAF2w)

- [6个能让你的 Kotlin 代码库更有意思的“魔法糖” —— 第一部分](https://www.oschina.net/translate/6-magic-sugars-make-your-kotlin-codebase-happier-part-1)
- [6个能让你的 Kotlin 代码库更有意思的“魔法糖” —— 第二部分](https://www.oschina.net/translate/6-magic-sugars-make-your-kotlin-codebase-happier-part-2)
- https://medium.com/grand-parade/6-magic-sugars-that-can-make-your-kotlin-codebase-happier-part-3-6319a451cd5d
- [Kotlin —  最佳实践](https://www.jianshu.com/p/b9cba3aa8f8a)

#### inline reified Generic
- [Kotlin的独门秘籍Reified实化类型参数(上篇)](https://juejin.im/post/5bd1d590518825288b398f46)
- [Kotlin的独门秘籍Reified实化类型参数(下篇)](https://juejin.im/post/5bd45ae16fb9a05d2a1db51b)
- [Kotlin泛型中何时该用类型形参约束?](https://juejin.im/post/5bceb5915188255c6b654cec)


#### typealias 
- [有关Kotlin类型别名(typealias)你需要知道的一切](https://juejin.im/post/5b052f806fb9a07ac0229ce3)


#### 讨论List、Sequence、Rxjava在操作数据流时的性能对比分析
- [Kotlin中是应该使用序列(Sequences)还是集合(Lists)?](https://juejin.im/post/5b13fdace51d450696590828)
- [Kotlin中的龟(List)兔(Sequence)赛跑](https://juejin.im/post/5b28f4946fb9a00e3a5a9b8c)
- [Declarative Kotlin: Lists, Sequences and RxJava](https://medium.com/@tpolansk/declarative-kotlin-lists-sequences-and-rxjava-7301da36bc52)

#### Effective Kotlin
##### 当我们遇到构造器中有很多参数的时，我都会考虑使用Builder模式来替代它。当然这只是Java中常见操作，但是Kotlin是不是得按部就班照着Java来呢？显然不是，Kotlin中有着更为优雅和强大的实现方式构造器+默认值参数，或者尝试下一代的Builder模式-DSL
- [Effective Kotlin系列之考虑使用静态工厂方法替代构造器(一)](https://juejin.im/post/5b78f805e51d4538c2108951)
- [Effective Kotlin系列之遇到多个构造器参数要考虑使用构建器(二)](https://juejin.im/post/5b8698bce51d4538a423dd70)

&nbsp;
- [Kotlin中是应该定义函数还是定义属性?](https://juejin.im/post/5afc23446fb9a07ab979abdf)
- [如何在你的Kotlin代码中移除所有的!!(非空断言)](https://juejin.im/post/5afd9090f265da0ba46a0429)

#### 标准库函数 standard.kt
- [掌握Kotlin中的标准库函数: run、with、let、also和apply](https://juejin.im/post/5b0048ed518825428a2619ed)
- [Kotlin系列之let、with、run、apply、also函数的使用](https://blog.csdn.net/u013064109/article/details/78786646)

#### 代理 delegate
- [Kotlin的属性代理你真的理解了吗](https://blog.csdn.net/u013064109/article/details/82794410)
- [Kotlin学习之委托机制](https://blog.csdn.net/u014134488/article/details/51123805)

#### 协程 Kotlin Coroutines
- [Advanced Kotlin Coroutines tips and tricks - Learn about a few snags and how to get around them](https://proandroiddev.com/coroutines-snags-6bf6fb53a3d1)
- [I exchanged RxJava for coroutines in my Android application. Why you probably should do the same](https://proandroiddev.com/i-exchanged-rxjava-for-coroutines-in-my-android-application-why-you-probably-should-do-the-same-5526dfb38d0e)

#### 语法成本相关

-  [探索 Kotlin 的隐性成本（Part 1）](https://www.oschina.net/translate/exploring-kotlins-hidden-costs-part-1) 

-  [探索 Kotlin 的隐性成本（Part 2）](https://www.oschina.net/translate/exploring-kotlins-hidden-costs-part-2)

-  [探索 Kotlin 的隐性成本（Part 3）](https://www.oschina.net/translate/exploring-kotlins-hidden-costs-part-3) 

#### Kotlin DSL相关
-  [Kotlin 中的领域特定语言](https://www.oschina.net/translate/creating-dsl-with-kotlin)

-  [Gradle Kotlin DSL](https://github.com/gradle/kotlin-ds)

-  [Kotlin language support for Gradle build scripts](https://blog.gradle.org/kotlin-meets-gradle)

#### 其他博客
- Android Weekly上也经常会有一些好的博客，发现主要来自于网站[medium.com](medium.com) ，英语好的可以直接在该博客上搜索

-  英语不好的，在OSChina上，有一些就是Java和Kotlin相关的，https://www.oschina.net/translate/list/11

最后，毕竟Kotlin是Java的超集，要学好Kotlin, Java也要多学习一些基础知识和新特性，比如学好Java范型，动态代理等。






