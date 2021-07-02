# README

## 前言

**整体框架：layui**
网站的整体思路参考了：[zjun的在线工具](https://tools.zjun.info/googlehacking/)

编码模块参考了： [P神的代码审计知识星球](https://govuln.com/tool/). 甚至某些都是照抄的。。
笑。。。

二维码生成引用了： [qrcodejs](https://github.com/davidshimjs/qrcodejs)

随机密码生成参考了百度的一些站点的样式。。。

XXXX生成也是参考了百度的一些站点。。。然后根据规律写了一下。。。

Google hacking模块参考了：[zjun的在线工具](https://tools.zjun.info/googlehacking/)

Windows杀软识别模块参考了：[zjun的在线工具](https://tools.zjun.info/googlehacking/)并且自己去
重组合了一下两个项目的字典 r00tSe7en的[get_AV](https://github.com/r00tSe7en/get_AV) 和 
gh0stkey 的[avList](https://github.com/gh0stkey/avList)

Windows提权辅助模块使用了：[gh0stkey / 的peAssist](https://github.com/gh0stkey/peAssist)

反弹shell工具模块参考了：[反弹shell生成](http://8.210.235.249/)

常用资料模块来自于百度还有朋友以及浏览器插件[hacktools](https://github.com/s7ckTeam/HackTools)

当然很多还用了很多其他的东西吧，我也有点记不住了

这个项目我有时候比较需要的，有时候去到客户现场，没网络的情况下需要使用到某些功能，来回切换网络有点儿烦，而且还有广告（这个真不是主要原因）

当然，这也是个重复造轮子的项目，可能还没甚鸟用。。。

## 截图

![image-20210702175142523](img/image-20210702175142523.png)

![image-20210702175158812](img/image-20210702175158812.png)

![image-20210702175215586](img/image-20210702175215586.png)

![image-20210702175230800](img/image-20210702175230800.png)

![image-20210702175250021](img/image-20210702175250021.png)

![image-20210702175302776](img/image-20210702175302776.png)

## docker版本

docker版本的我也上传了

```bash
docker pull c1o2a3/bug
docker run -d -p 80:80 c1o2a3/bug
```

