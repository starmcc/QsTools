# QsTools 秋水工具箱

![img](./ui.png)

## 前言

香港/台湾游戏橘子`Beanfun`登录工具箱，一体化新枫之谷台服网页登录优秀解决方案。

本工具由易语言`5.9`版本编写，遵循`MIT`协议。

感谢下面的开源大神提供思路和代码

- [pungin/TwMS-Helper](https://github.com/pungin/TwMS-Helper)
- [**InWILL/Locale_RemulatorV1.4.3**](https://github.com/InWILL/Locale_Remulator)


## 如何食用？

请移步到发布区下载本工具

[Releases点击进入下载页](https://github.com/starmcc/QsTools/releases)

**强烈建议使用3.1.1版本以上**

> 3.1.1 版本以上（包括3.1.1）

1. 将`QsTools.exe`放置在游戏目录内，与`MapleStory.exe`同级。
2. 第一次下载请先自行打开一次工具，**会自动将游戏启动路径改为本工具**。
3. 打开橘子官网登录，点启动游戏，即可弹出本工具。


## 实现功能

1. 免输入模式，省去复制粘贴账号密码的烦恼。
2. 简体环境下运行游戏（基于[**InWILL/Locale_RemulatorV1.4.3**](https://github.com/InWILL/Locale_Remulator)）
3. 装备星力卷轴计算器（25星暂不准确）
4. 自动关闭Play窗弹出
5. 自动输入功能（省去复制粘贴啦）
6. 内置纸娃娃系统（[MapleStory-GM-Client-Github](https://github.com/Elem8100/MapleStory-GM-Client)）
7. 增加联盟摆放模拟器（[来自此网站](https://xenogents.github.io/LegionSolver/)）
8. 增加关闭`NGS`强制结束进程功能（某些加速器卡`NGS`解决方案）
9. 一些实用网站收录快速导航
10. 可更换游戏默认字体

## 程序依赖

1. [UPX 3.96](https://github.com/upx/upx/)
1. [精益模块-10.3.5](http://ec.125.la/)
2. [EXUI++界面库-20220526 VIP](https://www.iexui.com/)
3. [InWILL/Locale_RemulatorV1.4.3](https://github.com/InWILL/Locale_Remulator)
4. [纸娃娃系统（MapleStory-GM-Client-Github）](https://github.com/Elem8100/MapleStory-GM-Client)


## 安全问题

从`3.2.3`开始，将会在发布`Release`当中贴出工具的(Hash)哈希值

请各位下载工具后校验Hash值是否安全

怎么查询哈希值？

```
certutil -hashfile 该程序路径
```

回车后会出现hash值。

**熟悉易语言的朋友可以自行下载源码自行编译**

## 犒劳打赏

免费开源实属不易，需要大量的时间、精力去调试和维护。

如果您资金充裕，望君能慷慨解囊给与我一些鼓励与支持。

每一笔打赏，都将让小梦铭记于心，感恩有你。

![image](./sponsor.png)
