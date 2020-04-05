# SEU-master-thesis

东南大学硕士研究生学位论文 LaTeX 模版。

## 简介

本模版基于许元的 [SeuThesis](http://seuthesis.googlecode.com/) 和樊智猛的 [SeuThesix](https://github.com/zhimengfan1990/seuthesix)，并在他们工作的基础上进行了修改以适应东南大学新的学位论文要求。目前本模版只支持学术型硕士研究生，对工程型硕士研究生的支持将在后续完善。

本模版中参考文献部分的BST文件来自南京大学的胡海星同学提供的 [GB/T 7714-2015 BibTeX Style](https://github.com/CTeX-org/gbt7714-bibtex-style)，在此对他的工作表示感谢。

## 文档的编译

进行全文编译需要按照下述顺序调用编译引擎：

```
XeLaTeX -> BibTeX -> MakeIndex -> XeLaTeX -> XeLaTeX
```

为了方便文档编译，本模版也提供了自动化编译脚本。Windows 用户请执行根目录下的 make.bat 批处理文件，Linux 和 MacOS 用户请在命令行中执行根目录下的 make.sh 脚本。

## 模版的使用

为了方便你快速上手本模版，我们撰写了一份针对本模版的使用手册，你可以阅读根目录下的 manual.pdf 文件以获取更多的模版使用方法和 LaTeX 使用技巧。此外，我们还提供了东南大学硕士研究生学位论文相关的说明文件以供参考，你可以在本模版的根目录下找到它们。它们分别是：

- 附件1：东南大学教务处和东南大学研究生院印发的《东南大学研究生学位论文格式规定》，该文档详细规定了硕士研究生撰写学位论文需要遵守的规则与注意事项；

- 附件2：东南大学研究生院印发的《学位论文独创性和使用授权声明》；

- 附件3：中华人民共和国国家质量监督检验检疫总局和中国国家标准化管理委员会印发的《中华人民共和国国家标准 GB/T 7714-2015 信息与文献 参考文献著录规则》，该规则规定了中文论文类文本中参考文献著录所需要遵守的规则。

## 更新历史
- __3.2.5__：添加了对模板参数的介绍；添加了对子图的支持。

- __3.1.1__：舍弃了 CLS 文件的一些暴露参数；添加了 Windows 操作系统的编译脚本；撰写文档使用手册，正式开放源代码。

- __3.0.3__：调整了参考文献的格式，使其符合 GB/T 7714 - 2015 国家标准。

- __3.0.1__：大幅调整了 CLS 文件的结构与布局，取消了原模版对博士研究生学位论文的支持。

## 开源许可证

[GPL - v3 © wurahara](https://github.com/wurahara/SEU-master-thesis/blob/master/LICENSE)