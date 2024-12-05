# 离开的人们 Zero -Prologue-

> 您需要最新的 AIR Runtime：[Air](https://airsdk.harman.com/download) 才能启动游戏，请点击上述链接下载。

1. 此处发布离开的人们 Zero -Prologue- 汉化补丁；
2. `.swf` Patch 脚本；
3. 汉化所用工具。

## 使用方法

> [!WARNING]
> 有关读档、存档、快进、历史对话和译注的逻辑或功能不再更新，这些功能也并非由 K2Cee 实现，而是汉化组在其之上添加的功能。其引擎代码限制，维护较为困难，程序不保证此类功能的完备性。
>
> 此外，您不得向 K2Cee 汇报（通过 Discord，X，邮箱或其他联系方式）有关读档、存档、快进、历史对话、译注和汉化感言页面所引起的错误，再次提醒，这些功能的最终实现并非出自 K2Cee。如果出现无法使游戏继续的情况（指无法继续操作，对于历史对话中出现全部文本、结尾文本无法快进等问题不再受理）请加入测试群（下午）或提交 Issue 汇报。
>
> 另，此后若是有文本补丁，因引擎限制，过去的存档或无法使用，请使用「章节选择」功能跳转至想读的位置后存档即可。

前往 Release 页面下载最新汉化包：

- Windows 用户：下载「Windows 硬盘版」文件夹，解压后，双击「去人たちZERO -prologue-.exe」启动游戏。
- 其他操作系统：自行前往官网下载[游戏安装包](https://k2cee.com/downloads/KYOJIN_ZERO_prologue.zip)，解压后进行安装（压缩包编码为 Shift-JIS），随后按照以下步骤替换文件：
  1. 备份并替换 `KyojinZeroPrologue.swf`；
  2. 备份并替换整个 `font/`, `config/` 和 `META-INF/` 文件夹；
  3. 进入 `data/`，备份并替换 `text.dat`, `system.dat` 和 `img.dat`，最后拖入 `wiki.json` 即可。
- 非桌面端操作系统用户：该汉化补丁暂不支持 Android 或 iOS 端，因多端适配问题，暂不做移动端的考虑。

如果您无法启动游戏，诸如出现白屏、报错，请见下文（「AIR SDK 启动方法」）启动游戏。

如果您发现了游戏中的问题，请加入测试 QQ 群 821150410 向我们反馈，或在此处的 Issues 页面向我们汇报错误。

## 发布

### 2024.12.05

发布第一章体验版，该版本仅提供 Windows 硬盘版本，12 月 25 日（UTC+08:00）发布全包（正式版）并开源工具。

## AIR SDK 启动方法

如果您遇到了白屏、闪退、无法安装的问题，请按照以下方式启动序章：

1. Air SDK 需要 JDK 前置。如果你安装过了 JDK 并配置好了系统环境，请继续阅读，否则请先安装 JDK；
2. 进入 [Harman AIRSDK](https://airsdk.harman.com/download) 下载您的操作系统所对应的 SDK；
3. 解压 SDK 后，将 SDK 下的 `bin` 文件夹添加到您的环境变量：
  1. 对于 Windows 用户，搜索「环境变量」，点击「编辑系统环境变量」，随后点击「环境变量」，在「系统变量」中找到 `Path` 变量点击并点击「编辑」，在「编辑环境变量」中点击「新建」后在新的文本框中粘贴 SDK 的 `bin` 路径；
  2. 对于其他操作系统用户，在您的 Profile 中添加：`export PATH="/path/to/AIRSDK/bin:$PATH"`
5. 进入汉化文件夹，您可以使用「Windows 硬盘版」或自行解压官方安装包（即解压 `KYOJIN_ZERO.air` 文件）并手动安装补丁；
6. 随后在此文件夹下打开终端，输入 `adl META-INF/AIR/application.xml .` 执行即可启动。

## 斑猫研汉化组成员

- 组长：米拉比利斯
- 翻译：歯医
- 校润：Zero Strelka、白斩鸡、SCHOEMATT、DJ Godot、夢見る魚
- 程序：DJ Godot
- 美工：kyoshi
- 测试：全体汉化组成员、Borillo、黑白小人、乐正君、梦的逢破、上光末宴
- K2Cee 联络：歯医、kyoshi
- WIKI 及译注：全体汉化组成员
- 特别感谢：Rien（虚航汉化组）、翳、名为 ok 绷的创可贴

## 声明

该汉化补丁非 K2Cee 官方翻译，由「斑猫研汉化组」制作完成。请勿用于商业目的，违者后果自负。

- [K2Cee 官方网站](http://k2cee.com/)
- [官方 X（推特）](https://x.com/kyojintachi)
- [离开的人们 YouTube 频道](https://www.youtube.com/channel/UCirKaOCFxZmwpbjc5GD2eBQ)
- [离开的人们 Ⅰ/Ⅱ 官方网站](http://kyojintachi.k2cee.com/)

还请各位去人玩家请遵守 [K2Cee 版权指南](https://x.com/KYOJINTACHI/status/1727871376554709247)！
