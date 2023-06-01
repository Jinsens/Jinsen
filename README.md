# 锦森-Jinsen
![Header](https://github.com/Jinsens/Jinsen/blob/main/Jinsen.png "Header")
## 模块介绍
使用独创技术去除云控

使用shell实现

适用于MIUI12.5+的所有机型

使用本地云控下发技术

## 如何实现的？

使用pm指令启动Joyose/电量和性能下发本地云控配置并阻断云端配置

替换本地云控数据

## 疑惑或困惑

为什么要下发本地云控配置？

因为从小米12系列开始采用了云控调度方法，云控调度方式必须下发本地云控配置，不然会导致调度失效或者大核睡死现象

## 使用说明

magisk/kernel su刷入模块即可

请不要删除Joyose，电量和性能，不然模块不会生效
