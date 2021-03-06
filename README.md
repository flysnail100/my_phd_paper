# NJU-Thesis

　　本项目是在南京大学学位论文LaTeX模板的基础上进行了修改，并撰写我的毕业论文。  

## 使用说明:
* 安装环境为Windows系统，由于原先LaTeX版本已经是几年之前的了，且CTeX也已很久没有更新，所以本模版不再使用CTeX，而是安装**Tex Live 2020**，并安装**TeXstudio**作为编辑器，以上两款软件均可在网上free获取。
* 由于旧的LaTeX模版老旧，使用**Tex Live 2020**编译存在bug，所以对原模版就行修改，主要修改了njuthesis.cls文件，已可进行正常编译。查找资料参考https://www.overleaf.com/blog/tex-live-2020-now-available和https://github.com/njuHan/njuthesis-nju-thesis-template/issues/8。
* 因需对中文编译，所以必须配置使用**XeLaTeX**作为编译方式（一般英文编译，默认使用**pdfLaTeX**进行编译）。且在**编译前记得关闭所有pdf阅读器**，否则无法生成pdf文件。
* 切换本科生、研究生、博士生论文模版，需修改.tex文件中\documentclass[参数]，如博士论文模版，对应参数中填写phd。
* 参数twoside/oneside指定排版的文档为双面/单面格式，如果论文双面打印，则建议用twoside（twoside会使得chapter章节从奇数页开始，即纸张的正面开始，因此会出现一些空白的页面）。
* 使用bibtex文献管理，用编辑器编辑sample.bib文件即可。或使用[JabRef](http://www.jabref.org/)打开

## 文件说明:
|文件(夹)|说明|
|-|-|
|sample.tex | 示例文档，可作为学位论文的基本模板|
|sample.bib | 示例文档的参考文献数据库|
|njuthesis.cls | 模板类文件|
|njuthesis.cfg | 模板配置文件|
|njulogo.eps | 南京大学校徽图片|
|njuname.eps | 南京大学校名图片|
|gbt7714-2005.bst | 符合国标GB/T 7714-2005 的参考文献样式文件|
|figures/ | 示例文档图片目录|

## 参考文献格式说明
严格遵循中国国家标准[《GB/T 7714-2005: 文后参考文献著录规则》][gbt7714-2005]   
详细信息见该项目：[GBT7714-2005-BibTeX-Style](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style)

[gbt7714-2005]: https://github.com/njuHan/njuthesis-nju-thesis-template/blob/master/%E3%80%90GB_T%207714-2005%E3%80%91%E6%96%87%E5%90%8E%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE%E8%91%97%E5%BD%95%E8%A7%84%E5%88%99.pdf
