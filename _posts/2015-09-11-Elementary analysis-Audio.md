---
layout: post
title: 浅析Audio（1）
category: android
comments: true
---

## Audio
Audio系统是Android平台的重要组成部分，它主要包括三方面的内容：
·  AudioRcorder和AudioTrack：这两个类属于Audio系统对外提供的API类，通过它们可以完成Android平台上音频数据的采集和输出任务。
·  AudioFlinger：它是Audio系统的工作引擎，管理着系统中的输入输出音频流，并承担音频数据的混音，以及读写Audio硬件以实现数据的输入输出等工作。
·  AudioPolicyService，它是Audio系统的策略控制中心，具有掌管系统中声音设备的选择和切换、音量控制等功能。
