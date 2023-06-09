---
date created: 2022-08-02
date modified: 2023-03-14
title: mac分辨率、启动磁盘吃啥问题 - 重置PRAM
---

x:: [[mac充电和键盘灯异常 - 重置SMC]]

## NVRAM / PRAM

**[2]**NVRAM（非易失性随机访问存储器）是一小部分内存，Mac 使用这些内存来储存某些设置并对其进行快速访问。PRAM（参数 RAM）储存着类似的信息，且 NVRAM 和 PRAM 的重置步骤相同。

可储存在 NVRAM 中的设置包括音量、显示屏分辨率、启动磁盘选择、时区，以及最近的内核崩溃信息。储存在 NVRAM 中的设置取决于您的 Mac 以及与这台 Mac 搭配使用的设备。

如果您遇到与这些设置或其他设置有关的问题，那么重置 NVRAM 可能会有帮助。例如，如果 Mac 并非从“启动磁盘”偏好设置中选定的磁盘启动，或者在 Mac 启动前短暂地显示了一个问号图标，则可能需要重置 NVRAM。

**重置方法如下：**

将 Mac 关机，然后开机并立即同时按住以下四个按键：Option、Command、P 和 R。您可以在大约 20 秒后松开这些按键，在此期间您的 Mac 可能看似在重新启动。

![](https://img2.oldwinter.top/mac分辨率、启动磁盘吃啥问题%20-%20重置PRAM_image_1.jpg)

在会发出启动声的 Mac 电脑上，您可以在两次启动声之后松开这些按键。

在配有 Apple T2 安全芯片的 Mac 电脑上，您可以在 Apple 标志出现并再次消失后松开这些按键。
