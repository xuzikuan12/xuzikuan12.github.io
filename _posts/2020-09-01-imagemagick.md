---
title:  "Imagemagick 的使用"
date:   2020-09-01
tags:
  - windows
  - imagemagick
---

Imagemagick 是一个强大的命令行图片处理工具，它可以实现众多的功能。

但是，作为一个合格的小白，我只使用它的批量转换功能，惭愧。

可以看这个链接学习各种命令行：https://imagemagick.org/script/command-line-processing.php

## 1. jpeg to jpg

把当前目录的jpeg图片转换成jpg，并且按照数字000-999来命名

```
magick *.jpeg %03d.jpg
```

