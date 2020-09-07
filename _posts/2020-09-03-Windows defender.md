---
title:  "Windows defender 使用心得"
date:   2020-09-03
tags:
  - defender
  - windows
---

电脑日常裸奔，所以希望能够利用好自带的defender。

## 1. 文件夹限制访问

![folder limit](https://xuzikuan12.github.io/images/defender/1.png)

希望可以通过这个功能来防止病毒篡改系统文件。

![folder limit](https://xuzikuan12.github.io/images/defender/2.png)

默认会保护Windows系统文件夹，同时还是添加User文件夹。

我自己添加了自己的工作文件。

这时一些工作要用的软件会被defender限制访问，可以通过添加允许来保证正常使用。

但是，如果是代码脚本运行的话，会报错，尝试了添加python.exe，代码可以正常使用。

但是*2，git不能用，结果都不行。看这报错。

![error](https://xuzikuan12.github.io/images/defender/3.png)

后来想起来，我用scoop管理软件，默认目录是current连接符，而不是真实的目录。

于是一波添加，问题解决。

![exception](https://xuzikuan12.github.io/images/defender/4.png)