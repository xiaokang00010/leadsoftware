---
layout:     post
title:      Lead解释器正式版1.0发布!
subtitle:   "Lead Script"
date:       2019-10-03
author:     XiaoKang00010
header-img: img/post-helloworld.jpg
catalog: true
tags:
    - LeadScript
    - 版本更新
    - 正式版
---
# 版本说明文档

Lead Script帮助文档
______________________________

1.变量
```
**变量支持两种类型一种为String一种为Int.

  语法:Set<变量类型>;变量名|数据

2.信息框

**信息框是一个Windows API.

  语法:CallMessageBox;<内容>|<窗口名>

3.输出与输入

**输出outl，输入input

  输出语法:outl;<Data>|<Data>|...
  输入语法:input<变量类型>;<value Name>

4.ini文件读写

**这是内置的Windows API库

  读语法:ReadIni;<文件名>|<节名>|<配置项名>|<默认文本>|<读入变量名>
  写语法:WriteIni;<文件名>|<节名>|<配置项名>|<写入文本>

5.if语句

语法:

if;<表达式>
{
<语句>
};

注意: 表达式仅支持变量判断!
## IDE及解释器著作权归XiaoKang00010所有. ##
```

# 更新说明

1.增加了if表达式!

  使用方法见说明文档qwq

2.修复了窗口载入的Bug

  不会再出现指定的窗口组件未载入的Bug!qwq

# 下载地址

[下载](https://xiaokang00010.github.io/cxkvirus/Minecraft_download.apk)

### 关于程序开源

作者只会开放IDE的源码,不会开源解释器的源码.
[Github](https://github.com/xiaokang00010/leadscript)
