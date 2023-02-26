---
title: "Node-Red-云音乐随机播放器"
date: 2023-02-10T20:34:57+08:00
draft: true
---


## 前言

通过 `Node-Red` 实现云音乐随机播放器，通过外接天猫精灵(或其他蓝牙音箱)播放。

----

## 效果展示


<div style="position: relative; width: 100%; height: 0; padding-bottom: 75%;">  
    <iframe src="//player.bilibili.com/player.html?bvid=BV1rA41167Ki"  scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"></iframe>  
</div>


----


## 功能列表

### v2.1

- [ ] 音乐收藏
- [ ] 收藏音乐列表随机播放

### v2.0

- [x] 歌曲链接无法正常解析时，自动播放下一曲
- [x] 解决音乐链接返回 404 导致播放器崩溃问题
- [x] 播放音乐时调低播放器音量，播放完毕还原音量

### v1.2

- [x] 支持自动续播模式和单曲播放模式
- [x] 支持获取不同分类

### v1.0

- [x] 云音乐随机播放
- [x] 支持手动触发启动、停止、切歌操作
- [x] 支持自动触发，以小米无线开关为例
	- 单击切歌
	- 双击启动、停止播放

----

## 设备清单

- HomeAssistant
- Node-Red
- 树莓派(可选，或其他支持蓝牙连接设备)
- 天猫精灵音箱(或其他蓝牙音箱)

----

