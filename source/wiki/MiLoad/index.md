---
wiki: mi-load
title: 写在前面
type: story
indent: true
---

## 什么是MiLoad

MiLoad是一款高稳定性的支持快速部署的Unturned Rocket Plugin云提供者，使用Rocket和asp.net进行构建。



## 为什么开发MiLoad

​	因为本人之前也开过Unturned服务器，之前最令我崩溃的就是在插件多起来之后不同插件之间的依赖冲突，甚至有的时候完全找不到插件对应版本的依赖。还得去clone别人的git仓库自己build。更有甚者插件作者自己用的依赖版本都是人家仓库clone下来自己改了之后build拿来用的，没有push，根本找不到有对应版本和功能的依赖库。

​	到了现在，我也不开服了，尝试去做一个服务提供者，但是被问到最多的问题任然是一些插件之间依赖冲突的报错和一大群找我要依赖的伸手党。

​	为了帮助广大新服主撑伞（虽然Unturned现在已经快要凉透了），尝试去开发了这个小工具。

## MiLoad的用途

​	用于给各位服务提供者提供一个快速搭建和部署远程插件源（我构想中的是，各个服务提供者可以自己反编译一套插件库和依赖库并统一版本，然后服主那边直接填写源的url通过插件clone并加载就行了），并且本套件也提供了对应的rocket plugin端进行插件和插件依赖的下载和加载。

