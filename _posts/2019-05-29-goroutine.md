---
layout: post
title: go routine 相关
---

非抢占式 由协程自己在切换点交出cpu控制权

Goroutine 可能的切换点

- I/O, select
- channel
- 等待锁
- 函数调用(有时)
- runtime.Gosched()
- 等待锁

