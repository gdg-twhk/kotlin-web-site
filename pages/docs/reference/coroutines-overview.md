---
type: doc
layout: reference
category: "Introduction"
title: "Coroutines 概觀"
---

# 用在非同步程式設計的 Coroutines

非同步 (Asynchronous) 或 非等待式 (non-blocking) 的程式設計是一種新的實作方法。無論我們在架設伺服器端、桌面或是行動裝置的應用時，它的重要性不只在使用者所感受到的流暢度，更涵蓋到當有需求擴展發生時。

有諸多方式可以解決上述的狀況，而在 Kotlin 這邊，提供了支援程式語言層級的 [Coroutine](https://en.wikipedia.org/wiki/Coroutine)，它可以靈活地委派許多的功能讓函式庫使用，這也是 Kotlin 的一種設計哲學。

值得一提的是，coroutines 不只為非同步程式設計開了一扇門，還提供了更多地可能性，像是 concurrency、actors 等等。


## How to Start

<div style="display: flex; align-items: center; margin-bottom: 20px">
    <img src="{{ url_for('asset', path='images/landing/native/book.png') }}" height="38p" width="55" style="margin-right: 10px;">
    <b>教學與文件</b>
</div>

剛認識 Kotlin 嗎？來看看 [Getting Started](/docs/reference/basic-syntax.html) 吧。

精選文件：
- [Coroutines 指南](/docs/reference/coroutines/coroutines-guide.html)
- [基礎](/docs/reference/coroutines/basics.html)
- [Channels](/docs/reference/coroutines/channels.html)
- [Coroutine 的 Context 與 Dispatchers](/docs/reference/coroutines/coroutine-context-and-dispatchers.html)
- [共享變重狀態與 Concurrency](/docs/reference/coroutines/shared-mutable-state-and-concurrency.html)
- [非同步流程](/docs/reference/coroutines/flow.html)

推薦教學：
- [你的第一個 Kotlin coroutine](../tutorials/coroutines/coroutines-basic-jvm.html)
- [非同步程式設計](../tutorials/coroutines/async-programming.html)
- [Coroutines 以及 Channels 簡介](https://play.kotlinlang.org/hands-on/Introduction%20to%20Coroutines%20and%20Channels/01_Introduction) 的 hands-on lab

<div style="display: flex; align-items: center; margin-bottom: 10px;">
    <img src="{{ url_for('asset', path='images/landing/native/try.png') }}" height="38p" width="55" style="margin-right: 10px;">
    <b>範例專案</b>
</div>

- [kotlinx.coroutines 範例與原始碼](https://github.com/Kotlin/kotlin-coroutines/tree/master/examples)
- [KotlinConf app](https://github.com/JetBrains/kotlinconf-app) 

更多範例在 [GitHub](https://github.com/JetBrains/kotlin-examples)
