---
description: 了解了Java和Linux，那么Java、Web是怎么在Kernel上跑起来的呢？
cover: >-
  https://images.unsplash.com/photo-1728916855363-e25df16454ee?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHJhbmRvbXx8fHx8fHx8fDE3MzA1NTQyNTR8&ixlib=rb-4.0.3&q=85
coverY: 0
---

# ✒️ Java

## 概述

其实Java也是作为一个进程在系统中跑，它是通过自己内部的管理机制(JVM)来进一步管理的。

* 能不进行系统调用，就不进行，减少内核态的转换，自己完善管理也能细化操作，减少内存泄漏

## JVM

