# 锦森-Jinsen
![Header](https://github.com/Jinsens/Jinsen/blob/main/Jinsen.png "Header")
## 模块介绍
使用独创技术去除云控

适用于MIUI12.5+的所有机型

使用本地云控下发技术

## 如何实现的？

启动Joyose/电量和性能下发本地云控配置并阻断云端配置

替换本地云控数据

## 疑惑或困惑

为什么要下发本地云控配置？

因为从小米12系列开始采用了云控调度方法，云控调度方式必须下发本地云控配置，不然会导致调度失效或者大核睡死现象

## 是否能配合潘多拉使用？

可以配合使用的，会导致无法锁原神的分辨率

如果是第三方其他内核的话，放心使用，因为不会有任何影响

## 是否能配合第三方云控使用？

很明显是不可以的，温控之类的，这些可以配合使用，不然会发生冲突之类的这些

## 我的手机卡第一屏或者第二屏了，有没有和你的模块有关系？

没有，添加了开机检测，不开机这个模块是不会运行的

只要不是跳电 温控 调度上的问题，一律都不是我这个模块导致的

## 使用说明

配置文件在/data/jinsen/config.conf

Magisk/Kernel SU刷入模块即可

请不要删除/冻结 Joyose/电量和性能 否则模块不会生效
