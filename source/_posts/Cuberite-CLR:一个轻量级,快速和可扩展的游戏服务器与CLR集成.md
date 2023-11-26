---
title: 如何使用Cuberite服务端
date: 2023-08-16 19:45
tags: [我的世界,Minecraft,Cuberite]
categories: [Cuberite]
---
Cuberite-CLR
Cuberite-CLR,它允许通过直接集成到CLR开发C#中的插件。

做了什么:
使用函数指针的基本双向互操作通信
命令约束支持
收益依赖
插件服务系统
用钩处理参考/外参数

剩下的和计划的:
实施所有API
实现所有挂钩
热重载CLR插件
例外处理
全自动绑定生成

剩下的但现在还没有计划:
挂钩同步支持

Cuberite是一款与Minecraft兼容的多人游戏服务器，用C++编写，设计为高效使用内存和CPU，并具有灵活的Lua插件API。Cuberite与Java Edition Minecraft客户端兼容。

Cuberite在Windows、*nix和Android操作系统上运行。这包括安卓手机和平板电脑以及树莓派。
目前，我们支持1.8-1.12.2版Minecraft协议版本。

安装
编译

请参阅"存储库(https://github.com/vfrz/cuberite-clr)"中的 "COMPILING.md(https://github.com/vfrz/cuberite-clr/blob/clr/COMPILING.md)"。
