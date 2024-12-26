# 离开的人们 Zero -Prologue-

> 您需要最新的 [AIR Runtime](https://airsdk.harman.com/runtime) 才能启动游戏，请点击上述链接下载。

此处发布离开的人们 Zero -Prologue- 汉化包体发布页面，因版权考虑，补丁 ActionScript Patch 及所用工具暂无法开源。

## 使用方法

> [!WARNING]
> 有关读档、存档、快进、历史对话和译注的逻辑或功能不再更新新功能，这些功能也并非由 K2Cee 实现，而是汉化组在其之上添加的功能。其引擎代码限制，维护较为困难，程序不保证此类功能的完备性。
>
> 此外，您不得向 K2Cee 汇报（通过 Discord，X，邮箱或其他联系方式）有关读档、存档、快进、历史对话、译注和汉化感言页面所引起的错误，再次提醒，这些功能的最终实现并非出自 K2Cee。如果出现无法使游戏继续的情况（指无法继续操作，而对于历史对话中出现全部文本、结尾文本无法快进等问题不再受理）请加入测试群（下文）或提交 Issue 汇报。
>
> 另，此后若是有文本补丁，因引擎限制，过去的存档或无法使用，请使用「章节选择」功能跳转至想读的章节后存档即可。

前往 Release 页面下载最新汉化包：

- Windows 用户：下载「Windows.zip」，解压后，双击「去人たちZERO -prologue-.exe」启动游戏。
- 其他操作系统：自行前往官网下载[游戏安装包](https://k2cee.com/downloads/KYOJIN_ZERO_prologue.zip)，解压后进行安装（压缩包编码为 Shift-JIS），随后按照以下步骤替换文件：
  1. 下载 `OtherOS.zip`；
  2. 备份并替换 `KyojinZeroPrologue.swf`；
  3. 备份并替换整个 `font/`, `config/` 和 `META-INF/` 文件夹；
  4. 进入 `data/`，备份并替换 `text.dat`, `system.dat` 和 `img.dat`，最后拖入 `wiki.json` 即可。
- 非桌面端操作系统用户：该汉化补丁暂不支持 Android 或 iOS 端，因多端适配问题，暂不做移动端的考虑。

如果您无法启动游戏，诸如出现白屏、报错，请见下文（「AIR SDK 启动方法」）启动游戏。

如果您发现了游戏中的问题，请加入测试 QQ 群 1006184061 向我们反馈，或在此处的 Issues 页面向我们汇报错误。

## 发布

### 2024.12.25

正式版 1.0.0 发布。

### 2024.12.05

发布第一章体验版，该版本仅提供 Windows 硬盘版本，~~12 月 25 日（UTC+08:00）发布全包（正式版）并开源工具~~。

## AIR SDK 启动方法

如果您遇到了白屏、闪退、无法安装的问题，请按照以下方式启动序章：

1. AIR SDK 需要 JDK 前置。如果你安装过了 JDK 并配置好了系统环境，请继续阅读，否则请先安装 JDK；
2. 进入 [Harman AIRSDK](https://airsdk.harman.com/download) 下载您的操作系统所对应的 SDK；
3. 解压 SDK 后，将 SDK 下的 `bin` 文件夹添加到您的环境变量：
    1. 对于 Windows 用户，搜索「环境变量」，点击「编辑系统环境变量」，随后点击「环境变量」，在「系统变量」中找到 `Path` 变量点击并点击「编辑」，在「编辑环境变量」中点击「新建」后在新的文本框中粘贴 SDK 的 `bin` 路径；
    2. 对于其他操作系统用户，在您的 Profile 中添加：`export PATH="/path/to/AIRSDK/bin:$PATH"`
4. 进入汉化文件夹，您可以使用「Windows 硬盘版」或自行解压官方安装包（即解压 `KYOJIN_ZERO.air` 文件）并手动安装补丁；
5. 随后在此文件夹下打开终端，输入 `adl META-INF/AIR/application.xml .` 执行即可启动。

## 斑猫研汉化组成员

- 组长：米拉比利斯
- 翻译：歯医
- 校润：Zero Strelka、白斩鸡、SCHOEMATT、DJ Godot、夢見る魚
- 程序：DJ Godot
- 美工：kyoshi
- 测试：全体汉化组成员、Borillo、黑白小人、乐正君、梦的逢破、上光末宴
- K2Cee 联络：歯医、kyoshi
- WIKI 及译注：全体汉化组成员
- 特别感谢：Rien（虚航汉化组）、驎之个人汉化、名为 ok 绷的创可贴

## 声明

该汉化补丁非 K2Cee 官方翻译，由「斑猫研汉化组」制作完成。请勿用于商业目的，违者后果自负。

- [K2Cee 官方网站](http://k2cee.com/)
- [官方 X（推特）](https://x.com/kyojintachi)
- [离开的人们 YouTube 频道](https://www.youtube.com/channel/UCirKaOCFxZmwpbjc5GD2eBQ)
- [离开的人们 Ⅰ/Ⅱ 官方网站](http://kyojintachi.k2cee.com/)

还请各位去人玩家遵守 [K2Cee 版权指南](https://x.com/KYOJINTACHI/status/1727871376554709247)！

## 汉化感言

> 排名不分先后，谁先写好就先复制谁的。

### 歯医

从初春到寒冬，总算是焊完端上来了！第一次处理这么大的文本量，就像先挖出故事的骨架，再用针线一点点缝制出故事的样貌一样，学艺不精，但也算是尽力而为了。

做翻译只是一小部分初期的工作，多亏群里文字功底坚实的校润大佬们，不懈地将我那苍白的文本润色修改了一遍又一遍，组内的所有人反复阅读、校对，最终才形成优美而流畅的语言。是大家携手的努力才促成了本作汉化的实现。

另外，如负责程序的 DJ Godot 所言，我们在这个汉化补丁版本中复原了 backlog、添加了 save、load 等功能，可以切换游戏窗口大小，并且为游戏内文字演出添加了模仿语气的停顿效果，使其更能在现如今的时代里拥有更好的游玩感受。

最值得注目的地方想必您也已有体验，我们联合「电波脚注」项目，在游戏中建立了去人世界中的知识库系统，使您在游玩中可以直接阅读某些专业用词的译注解释，也可以点击词条进行页面跳转，直接在网页中浏览知识库的内容。这个功能设计非常大胆，在无数个投入心血的日夜之下逐步建成，不论是对文本的琢磨，赋予详尽的解说，还是网站的构建，都超越了「翻译」的性质，将本作的补丁打造成为了由爱浇筑的系列艺术品。

握着手枪的少年，会将枪口指向何处？
灰色灵魂消逝前，脑内还曾映着色彩斑斓的世界？
期待 zero 系列在未来的演绎，也请大家多多支持原作 K2Cee。

### DJ Godot

谢谢大家的品鉴！能和汉化组的各位一起共事真是幸福至极啊！从搜查一课令人昏昏欲睡的会议到去另一个世界抓捕斑猫的行动，这个非日常的故事，大家觉得怎么样呢？

啊啊，先不提剧情了，还是先来说说和这部作品相遇的过程吧。最早下载这部作品，解压后一看竟然是 Adobe Air 这样的东西，也是有些感慨，转而一看最早发布时间是 2015 年，估计实际开工时间还要更早，不由得会心一笑，释然了。虽然在今天 ActionScript 什么的也已经如斑猫的手枪一般不中用了，但就这几个月的工作而来，也是从这种老古董身上嗅到了陈年香气，虽然初看上去有种那晚 JavaScript 和 Java 喝醉了的美，但一旦开始进行编写，便不觉得有多大阻碍。

好在终于是做好了存档-读档功能，也可能是大概，顺手修复了一下 Backlog 的调用，尽管可能是某种败笔，但更进一步的修改还是算了，总之，瑕不掩瑜，这样相信就好了。

此外译注功能也是稍稍花了点功夫，也是在代码里面塞入了一定量的电子垃圾，能跑起来也已是至善。最后，鄙人精力有限无法照顾到 Android 玩家，如果有需要可以尝试自己移植！

啊，感谢各位玩家能读完我的文字，届时还请让我听听你的感受！

### Schoematt

感谢您的游玩！也感谢您这么久的等待，我是参与了本次校对工作的 Schoematt。

虽说是“参与了”，但是实际上我也只是做了些非常微小的工作。大多数艰难而繁琐的任务还是依赖其他兢兢业业的 labman 们完成的，我只是个在极少的细节处做了些小修小补的庸人裱糊匠。忝列于此，惭愧之至。

老实说来，校润的过程并不能说全都是愉快的。本人的哲学素养基本为 0，平时也很少会接触电波感这么强的作品。先不提部分章节中电波感极强，甚至完全不知所云的大段内心独白翻起来多么让人头疼；光是许多写者或无心，译者需有意的细节之处的推敲，就能把我们都搞的焦头烂额。但是当我们为了搞清楚一个专业名词的含义而查找资料的时候；当我们为了用这个语词还是那个语词而交流探讨的时候；当我们真正完成了这个并不轻松的工作的时候……我相信至少在那些瞬间，我们都如同初次见面时在 Fabliau 中抛下了一切尘世的烦恼，交杯相庆的渡边与班猫般，是愉悦而满足的。

“自惭衰病心神耗，赖有群公鉴裁精。”我们的物语已经告一段落，剩下的感受还希望各位能够挥笔补足。再次感谢您能看到这里，期待与您在没有黑暗的世界再见！

### Kyoshi

众里寻他千百度，蓦然回首，那人却在灯火阑珊处。

往昔，往昔。

### 白斩鸡

嗨各位好啊，欢迎游玩我们汉化的第一个游戏！虽然我参与的部分也并不多，但是实际打开游戏，总能看到各种地方的只言片语是过去和大家讨论过如何翻译，如何修改的，还是很有感触。再次打开游戏，也能像追忆往昔一般，寻回过去点点。希望游玩《离开的人们 Zero -prologue-》的你同样可以感受到游戏故事的魅力。我们下次见！

### 黑白小人

十分有幸能参与到本作的测试中，十分有幸的第一次与汉化组接触，文学是一棵树撼动另一棵树，一个灵魂撼动另一个灵魂的，我想，汉化也是如此。曾以为，汉化就是简单的拼单词。登山一章给我留下了深刻印象，而在很有幸的与米拉比利斯哥交流时，我也了解到了「信达雅」是何其艰难的过程，村上春树风格的故事与段落需要如何表达，和作者本身文字风格的配适……二周目阅读时，我感受到了汉化组的心血，真的十分感谢汉化组的无私付出，电波类作品本身拥有强烈的语言风格，晦涩难懂的表达方式如何在保证阅读体验时最大程度的还原，如何保证原作的电波感，是汉化组呕心沥血的付出让我们看到了这个十分有狂气的作品。

### Borillo

第一次进入汉化组，处于熟悉运作方式的阶段。本人出力不能说没有，只能说小到可以算作误差，希望能带给玩家愉快的游玩体验（

### 夢見る魚

（感谢科长带我玩啥的，）从最初的汉化到一次次校对再到最后写程序，看到组员日日夜夜的辛勤劳作将这部作品的汉化成功变成了现实，对此表示敬佩和祝贺。

### 乐正君

大家好我是参与汉化测试的乐正君！很久以前就是去人的粉丝，非常有幸能参与汉化测试工作！当时为了能第一时间看到被完整翻译出来的关于舍密部的故事，我毫不犹豫地加入了汉化组，尽我所能提供一些微不足道的帮助。

非常感谢汉化组的大佬们能把这么晦涩难懂的文本翻译出来。汉化组的大家都很厉害，也很友善，非常期待未来能和大家再次合作。

游玩过程中，整个游戏自始至终给我一种超脱现实的感觉，甚至在关掉电脑后这种感受仍然缠绕了我许久。在给汉化组的翻译捉虫的过程中，我常常忘乎所以地沉浸在故事和剧情里无法自拔。

希望以后还能玩到更多这样与众不同的优秀作品。

### 梦的逢破

我对去人系列非常喜欢一直希望 Prologue 能早点汉化游玩，当得知可以参加 Prologue 的汉化测试很激动和开心，随着一章章的测试作品也一步步完善，就这一转眼的功夫已经临近尾声了，很感谢能让我参加测试的大家伙儿，是他们的热爱和努力才让这个作品早早的呈现在大家面前，最后也希望大家游玩的时候也开开心心的。

### 上光末宴

很感激「斑猫研」的大家让我在这次的汉化测试工作中尽一份微薄之力，我测试的时间比较早，从第一章汉化刚出开始就试玩了，一开始第一章文本中存在着大量的问题，文本的间隔时大时小，字体生硬的同时还存在着大量的漏翻，但是经过半年时间的努力文字也开始变得生动流畅起来了。

去人应该是我的毒电波启蒙，一开始是经过朋友「威逼利诱」打开了这款游戏，一开始推的时候感觉很无聊，但是迫于朋友的压力只好继续推着，直到看见安西学姐的日记时让我改观了，看着这些乱七八糟毫无逻辑但又充满狂气的文字仿佛有「无形的大手」把我按在电脑桌面前让我无比期待接下来文字要向我说些什么，推完的时候觉得意犹未尽一直找一些类似的狂气毒电波作品来找到当时推的那种感觉，这些作品共同的特点就是抓住一个观点持续不断的扭曲拓展最后变得抽象起来，所以我很难体会汉化组在翻译润色中的工作该有多么艰辛，当组长邀请我参与测试时我很激动的就答应了。

我认为去人系列的角色描写都非常生动，从爱丽丝的「我，帮助不了哥哥。但是，哥哥也没有帮助我」到去人 2 里十多名精神病的各持己见，最后再到 zero-prologue 里满月下的斑猫流着眼泪向着渡边颤抖的说出自己的悲伤（玩到这里我真的很感激汉化组的多月以来的努力付出），闭上眼睛这群没有后续内容的「离开的人们」在我的大脑里面鲜活了起来，我仿佛又在脑海里看到了偏执的渡边，认真的吉住小姐，天然呆的小凯还有像「米拉比利斯」这个名字一样神秘危险的斑猫先生。

最后，再次感谢一下「斑猫研」的大家以及屏幕前看着我发牢骚的你，希望你能坐在安静舒适的房间开心的游玩这款游戏。

### Zero Strelka

人是一个谜，需要解开它。
