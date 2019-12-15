# Terraria电路文档
[pdf下载](https://github.com/putianyi889/TerrariaWiringTutorial/releases) | [下载量统计](http://www.somsubhra.com/github-release-stats/?username=putianyi889&repository=TerrariaWiringTutorial)

本文档旨在整合目前已知的所有电路知识，为国内的TR玩家提供电路方面全面可靠的参考，节省大家搜索各种教程的时间。我们欢迎任何形式的贡献，包括教程编写、研究成果、文档美化、资料整理、制作插图等。如果你希望贡献但是不知道做什么，在[Issues](https://github.com/putianyi889/TerrariaWiringTutorial/issues)里我们会提供当下的一些任务，这些任务大多是不需要任何游戏知识的。如果你有任何问题、想法和建议，也可以至[Issues](https://github.com/putianyi889/TerrariaWiringTutorial/issues)提。

所有修改可以直接提交PR([Pull request](https://github.com/putianyi889/TerrariaWiringTutorial/pulls))也可以在[Issues](https://github.com/putianyi889/TerrariaWiringTutorial/issues)中询问后提交PR。对于整段整节的贡献请在PR中署名，未署名作匿名处理。小贡献会整理在附录中。

## 编辑指引
主文件`main.tex`。

各章节存放在`chapters`。

物品贴图存放在`figures/`。

NPC贴图存放在`npcs/`。

截图存放在`images/`并编号。有墙的区域尽量使用刷白漆的钻石晶莹宝石墙，并且使用CheatSheet或HERO's mod将光照打到100%，以达到白色背景效果。无墙的区域，可以在截图设置里关闭背景以达到透明背景效果。

模板在`elegantbook-cn`和`elegantbook-en`，请勿编辑模板。

`figure`和`image`存放原模板使用的图片，请勿修改。

### 生成wiki链接
使用`\wiki{词条}`将生成指向中文wiki的链接，例如`\wiki{铜短剑}`将生成[铜短剑](https://terraria-zh.gamepedia.com/铜短剑)。

使用`\wikii{词条}{文本}`将生成词条与文本不一致的链接，例如`\wikii{铜短剑}{同志短剑}`将生成[同志短剑](https://terraria-zh.gamepedia.com/铜短剑)。

### 代码环境
涉及源码中的数据、变量名、函数名等，请使用代码环境。行内的代码环境为`\lstinline{代码}`。表格中代码环境为`{\lstinline!代码!}`，注意外面要大括号。数学公式中代码环境为`\mathtt{代码}`。需断词换行的代码环境为`\path{代码}`。

### 交叉引用
所有使用过的label列举在`label used.txt`中，以防止label重复。早期文档使用的label并未列举出，包括插图的i+数字格式和其他一些拼音格式，请注意规避。目前常用的引用方式有`\hyperref`、`\href`、`\autoref`、`\nameref`、`\url`、`\subref`。除`\subref`属于`subfig`宏包，其他命令均属于`hyperref`宏包。

### 浮动体
除特殊情况下使用`[!htp]`，所有浮动体的放置方式统一为`[!ht]`。浮动体建议插入在对应文本之前以防止被放置在过于靠后的位置。

### 其他
关于单元格内的换行，请参考`makecell`宏包相关。关于可分页的表格，请参考`longtable`宏包相关。关于算法环境，请参考`algorithm2e`宏包相关。关于子浮动体生成，请参考`subfig`宏包相关。关于旋转90度的浮动体，请参考`rotating`宏包相关。关于嵌入文字的浮动体，请参考`wrapfig`宏包相关。其余问题请参考`LaTeX`教程和模板文档。

### 修改过的文件名
|原文件名|新文件名|
|:-|:-|
|Hanging_Jack_'O_Lantern.png|Hanging_Jack_O_Lantern.png|
|Jack_'O_Lantern.png|Jack_O_Lantern.png|
|Music_Box_(Old_One's_Army).png|Music_Box_(Old_Ones_Army).png|

# 关于模板

<!-- Author : Dongsheng Deng & Liam Huang-->
<!-- Program Email: elegantlatex2e@gmail.com -->

## ElegantBook

[Homepage](https://elegantlatex.org/) | [Github](https://github.com/ElegantLaTeX/ElegantBook) | [CTAN](https://ctan.org/pkg/elegantbook) | [Download](https://github.com/ElegantLaTeX/ElegantBook/releases) | [Wiki](https://github.com/ElegantLaTeX/ElegantBook/wiki) | [Weibo](https://weibo.com/elegantlatex)

![License](https://img.shields.io/ctan/l/elegantbook.svg)
![CTAN Version](https://img.shields.io/ctan/v/elegantbook.svg)
![Github Version](https://img.shields.io/github/release/ElegantLaTeX/ElegantBook.svg)
![Repo Size](https://img.shields.io/github/repo-size/ElegantLaTeX/ElegantBook.svg)

ElegantBook is designed for books. Just enjoy it! If you have any questions, suggestions or bug reports, you can create issues, pull requests or contact us at elegantlatex2e@gmail.com.

如果你有其他问题、建议或者报告 bug，可以提交 issues 或者给我们发邮件：elegantlatex2e@gmail.com。最近我们新建了一个 QQ 用户交流群（Q 群：692108391），欢迎加入。

**注意：** 由于新版本进行了重构，3.x 版本并不兼容 2.x 版本，如果你想把 2.x 版本的文件转为 3.x 版本，请查看[跨版本转换](https://github.com/ElegantLaTeX/ElegantBook/wiki/convert)。

## License

This work is released under the LaTeX Project Public License, v1.3c or later. 

本模板发布遵循 LaTeX 项目公共许可证 1.3 c 或更高版本。
