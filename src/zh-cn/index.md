---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
关键词: 简历, 可视化
description: 这是潘嘉铖的个人主页。
# 简历标题
resume_title: 潘嘉铖的个人主页
# 应聘者姓名
name: 潘嘉铖
# 联系方式
contact:
    - icon: fas fa-globe-asia
      text: http://panjiacheng.site/
      url: http://panjiacheng.site/zh-cn/
    # 邮箱
    - icon: fas fa-envelope
      text: panjiacheng@zju.edu.cn
      url: mailto:panjiacheng@zju.edu.cn
    # Github
    - icon: fab fa-github-alt
      text: JackieAnxis
      url: https://github.com/JackieAnxis
    # Blog
    - icon: fas fa-blog
      text: 博客
      url: http://panjiacheng.site/blog
---

{% raw %}
<grid>
<avatar><img src="https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_12-03-42.png"></avatar>

<h1>潘嘉铖</h1>
<center>
<a href='/'>English</a> | <a href='/zh-cn/'>简体中文</a>
</center>
<br>
</grid>
{% endraw %}

<div class="btns">

[`🌏 主页`](http://panjiacheng.site/zh-cn) [`✉️ panjiacheng@zju.edu.cn`](mailto:panjiacheng@zju.edu.cn) <a href="https://github.com/JackieAnxis"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a> [`💻 博客`](http://panjiacheng.site/blog)

</div>

## 👻 个人信息

潘嘉铖目前是一名[浙江大学](http://www.zju.edu.cn/)[计算机辅助设计与图形学（CAD&CG）国家重点实验室](http://www.cad.zju.edu.cn/)的博士生。他当前的研究兴趣包括可视化和可视分析。从 2013 年到 2017 年，他是浙江大学的一个本科学生。之后，他获得了工学学士学位，然后成为了一名 CAD&CG 实验室的硕士学生。2019 年 9 月，他成为了[陈为](http://www.cad.zju.edu.cn/home/chenwei/index.html)教授的一名博士学生。

-   个人主页: http://panjiacheng.site/
-   Github: https://github.com/JackieAnxis
-   浙江大学可视分析小组: https://zjuvag.org/

## 📚 教育经历

### 2017 ~ 现在: 硕博连读 <h4 style="display:inline-block;float:right;">浙江大学</h4>

研究方向: 可视化与可视分析

-   导师：[陈为](http://www.cad.zju.edu.cn/home/chenwei/index.html)教授
-   实验室: [CAD&CG 国家重点实验室](http://www.cad.zju.edu.cn/index.html)
-   学院: [计算机科学与技术学院](http://www.cs.zju.edu.cn/)

### 2013 ~ 2017: 本科 <h4 style="display:inline-block;float:right;">浙江大学</h4>

主修: 软件工程

-   学院: [计算机科学与技术学院](http://www.cs.zju.edu.cn/)

辅修: 创新与创业管理强化班

-   学院: [竺可桢荣誉学院](http://ckc.zju.edu.cn/)

## 📜 论文发表

潘嘉铖至今以一作身份发表论文 2 篇，以非一作身份发表论文 5 篇，相关内容主要包括：**图可视化探索**、**图嵌入**、**图布局交互**、**图可视化创作**以及**图数据的异常可视分析**。

<script>
function copyToClipboard(that) {
    const brRegex = /<br\s*[\/]?>/gi
    const $temp = $("<input>")
    $("body").append($temp)
    $temp.val(that.getAttribute("value").replace(brRegex, "\r\n")).select()
    document.execCommand("copy")
    $temp.remove()
    const title = that.getElementsByTagName("code")[0]
    title.textContent = title.textContent.split("✔️")[0] + "✔️"
    setTimeout(function () {
        title.textContent = title.textContent.split("✔️")[0]
    }, 2000)
}
</script>

### 2021

#### A Visual Analytics Approach for Structural Differences Among Graphs via Deep Learning

#### 一种通过深度学习对结构差异进行可视分析的方法

<div class="keywords">

`语义` `深度学习` `可视分析` `拓扑` `任务分析` `可计算模型`

</div>

韩东明, <u>**潘嘉铖**</u>, 解聪, 赵晓冬, 陈为

<div class="btns">

[`IEEE CG&A`](https://ieeexplore.ieee.org/document/9490333)<a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPXZC20,
  title = {A Visual Analytics Approach for Structural Differences among Transportation Networks},
  journal = {IFAC-PapersOnLine},
  volume = {53},
  number = {5},
  pages = {566-571},
  year = {2020},
  note = {3rd IFAC Workshop on Cyber-Physical & Human Systems CPHS 2020},
  issn = {2405-8963},
  doi = {https://doi.org/10.1016/j.ifacol.2021.04.226},
  url = {https://www.sciencedirect.com/science/article/pii/S2405896321004110},
  author = {Dongming Han and Jiacheng Pan and Cong Xie and Xiaodong Zhao and Wei Chen}, 
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPXZC20" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPXZC20">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/%E5%9B%BE%E7%89%871.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: IFAC-PapersOnLine
**关键词**: `Semantics` `Deep learning` `Visual analytics` `Topology` `Task analysis` `Computational modeling`

**摘要**: 表示和分析网络之间的结构差异有助于深入了解网络动态演化等与差异相关的模式。传统的解决方案利用表示学习来编码结构信息，但缺乏直观的方法来研究网络的结构语义。 本文提出了一种图结构差异的表示和分析方案。我们提出了一种 Delta2vec 嵌入技术来编码多个图，同时保留结构差异的语义。我们设计并实现了一个基于网页的可视化分析系统，支持对从嵌入中学习到的特征的比较研究。我们方法的一个显著特点是它支持构造和量化语义感知，以研究图数据中的潜在关系。我们通过三个数据集的案例研究来验证我们方法的可用性和有效性。

</div>
</div>
<br>

#### NetV.js: A web-based library for high-efficiency visualization of large-scale graphs and networks

#### NetV.js: 一款基于 Web 的支持大规模图和网络高效可视化的库

<div class="keywords">

`图` `图可视化` `网络可视化` `节点链接图`

</div>

韩东明, <u>**潘嘉铖**</u>, 赵晓冬, 陈为

<div class="btns">

[`Visual Informatics`](https://www.sciencedirect.com/science/article/pii/S2468502X21000048) [`📄 PDF`](https://www.sciencedirect.com/science/article/pii/S2468502X21000048/pdfft?md5=e26957f0ca1bde3d2ecb06f2fe857519&pid=1-s2.0-S2468502X21000048-main.pdf) [`🔗 NetV.js`](http://netv.zjuvag.org/) <a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPZC21,
  title = {NetV.js: A web-based library for high-efficiency visualization of large-scale graphs and networks},
  journal = {Visual Informatics},
  volume = {5},
  number = {1},
  pages = {61-66},
  year = {2021},
  issn = {2468-502X},
  doi = {https://doi.org/10.1016/j.visinf.2021.01.002},
  url = {https://www.sciencedirect.com/science/article/pii/S2468502X21000048},
  author = {Dongming Han and Jiacheng Pan and Xiaodong Zhao and Wei Chen},
  keywords = {Graph, Graph visualization, Network visualization, Node-link diagram},
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPZC21" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" class="hidden-content" id="hidden-content-HanPZC21">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Snipaste_2021-04-20_11-09-06.jpg' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: Visual Informatics
**关键词**: `图` `图可视化` `网络可视化` `节点链接图`
**摘要**: 图可视化在诸如社交媒体网络，蛋白质相互作用网络，交通网络等多个领域都发挥着重要的作用。许多可视化设计和变成工具都已经广泛应用于图相关的应用领域中。然而，针对大规模图数据进行高性能可视化仍具有挑战性。NetV.js 是一个基于 WebGL 的 JavaScript 库，旨在解决对大规模图数据进行高性能渲染（最高支持大约 5 万节点，100 万边），以提供足够的帧率以便用户交互。NetV.js 使用了 WebGL 接口，启用了 GPU 作为底层渲染引擎，加速了大规模图数据的绘制速度，并且通过一系列交互和插件机制，丰富了 NetV.js 的功能，以方便用户构建交互式图可视化。

</div>
</div>

---

### 2020

#### Exemplar-based Layout Fine-tuning for Node-link Diagrams

#### 基于范例的节点链接图布局微调技术

<div class="keywords">

`节点链接图` `图布局` `图可视化` `用户交互`

</div>

<u>**潘嘉铖**</u>, 陈为, 赵晓冬, 周舒悦, 曾伟, 朱闽峰, 陈健, 傅四维, 巫英才

<div class="btns">

[`IEEE TVCG`](https://ieeexplore.ieee.org/document/9240072) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/7d531afa561ac4fa5febffe0cb95e38477f73241.pdf) [`🎥 视频`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/29b5e20e480a3e49d58e60aeac01a005ab8f0d32.mp4) [`📌 附录`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/cca9e7fdb68b9cc8de1f7e808c57cfbb1877f3bf.pdf) [`🔗 ARXIV`](https://arxiv.org/abs/2008.00666) <a href="javascript:"  onclick="copyToClipboard(this)" value="@ARTICLE{PanCZZZZCFW21,
  author={Pan, Jiacheng and Chen, Wei and Zhao, Xiaodong and Zhou, Shuyue and Zeng, Wei and Zhu, Minfeng and Chen, Jian and Fu, Siwei and Wu, Yingcai},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  title={Exemplar-based Layout Fine-tuning for Node-link Diagrams},
  year={2021},
  volume={27},
  number={2},
  pages={1655-1665},
  doi={10.1109/TVCG.2020.3030393}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-PanCZZZZCFW21" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-PanCZZZZCFW21">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_19-29-50.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: IEEE Transactions on Visualization and Computer Graphics
**关键词**: `节点链接图` `图布局` `图可视化` `用户交互`

**摘要**: 文章设计并验证了一种新的节点链接图布局的微调技术，该技术能够基于样例，以批处理模式简化了一组子结构的调整。关键思想是将用户对局部子结构的修改转移到整个图中与样例具有相似拓扑的其它子结构。我们首先使用节点嵌入技术为每个子结构预计算向量化表示，然后将其用于即时子结构检索。我们设计和开发了一个交互式原型系统，通过一个定量比较的实验，三个案例研究和一个参与者内部用户研究验证了方法的有效性。

</div>
</div>
<br>

#### iNet: Visual Analysis of Irregular Transition in Multivariate Dynamic Networks

#### iNet: 一种多属性动态网络不规则变换的可视分析方法

<div class="keywords">

`多属性动态网络` `稀有类` `异常检测` `可视分析`

</div>

韩东明, <u>**潘嘉铖**</u>, 潘如晟, 周大为, 曹楠, 何京芮, 徐明亮, 陈为

<div class="btns">

[`FCS`](https://link.springer.com/article/10.1007%2Fs11704-020-0013-1) <a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPPZCHXC22,
  author    = {Dongming Han and
               Jiacheng Pan and
               Rusheng Pan and
               Dawei Zhou and
               Nan Cao and
               Jingrui He and
               Mingliang Xu and
               Wei Chen},
  title     = {iNet: visual analysis of irregular transition in multivariate dynamic networks},
  journal   = {Frontiers of Computer Science},
  volume    = {16},
  number    = {2},
  pages     = {162701},
  year      = {2022},
  url       = {https://doi.org/10.1007/s11704-020-0013-1},
  doi       = {10.1007/s11704-020-0013-1}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPPZCHXC22" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPPZCHXC22">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_23-59-37.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: Frontiers of Computer Science
**关键词**: `多属性动态网络` `稀有类` `异常检测` `可视分析`

**摘要**: 多元动态网络是指拓扑结构和节点属性随时间变化的网络。它们在多媒体应用中很常见。异常检测是分析这些网络的重要任务之一，但目前还没有得到很好的解决。在本文中，我们结合了一种稀有类检测方法和可视化技术来帮助用户识别和分析多变量动态网络中的异常。我们总结了稀有类的特征和两种异常类型。在此基础上，提出了一种新的稀有类别检测方法 DIRAD，用于检测具有异常的稀有类别候选。我们开发了一个名为 iNet 的原型系统，它集成了两个主要的可视化组件，包括一个基于 glyph 的稀有类别标识符，它帮助用户在检测到的子结构中识别稀有类别，以及一个主视图，帮助用户分析和解释网络拓扑和节点属性中稀有类别的异常。我们还进行了评估，包括一个算法性能评估，一个案例研究，和一个用户研究，以测试提出方法的有效性。

</div>
</div>
<br>

#### RCAnalyzer: Visual Analytics of Rare Categories in Dynamic Networks

#### RCAnalyzer: 一种动态网络中稀有类的可视分析方法

<div class="keywords">

`稀有类检测` `动态网络` `可视分析`

</div>

<u>**潘嘉铖**</u>, 韩东明, 郭方舟, 周大为, 曹楠, 何京芮, 陈为

<div class="btns">

[`FITEE`](http://www.jzus.zju.edu.cn/article.php?doi=10.1631/FITEE.1900310) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/RCAnalyzer-Visual%20Analytics%20of%20Rare%20Categories%20in%20Dynamic%20Networks.pdf) [`🎥 视频`](http://www.cad.zju.edu.cn/home/vagblog/videos/RCAnalyzer-Visual%20Analytics%20of%20Rare%20Categories%20in%20Dynamic%20Networks.mp4) <a href="javascript:" onclick="copyToClipboard(this)" value="@article{PanHGZCHXC20,
  title={RCAnalyzer: visual analytics of rare categories in dynamic networks},
  author={Jia-cheng Pan, Dong-ming Han, Fang-zhou Guo, Da-wei Zhou, Nan Cao, Jing-rui He, Ming-liang Xu, Wei Chen},
  journal={Frontiers of Information Technology & Electronic Engineering},
  volume={21},
  number={4},
  pages={491-506},
  year={2020},
  publisher={Zhejiang University Press & Springer},
  doi={10.1631/FITEE.1900310}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-PanHGZCHXC20" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-PanHGZCHXC20">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_23-56-28.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: Frontiers of Information Technology & Electronic Engineering
**关键词**: `稀有类检测` `动态网络` `可视分析`

**摘要**: 动态网络是指其节点和/或链路随时间动态变化的图形结构。现有的可视化和分析技术主要集中在总结和揭示网络结构的主要演化模式。以往很少有工作集中于检测动态网络中很少发生的异常变化模式，但这些异常可能会破坏网络结构的演化。在这项研究中，我们介绍了第一个设计用于检测动态网络子结构的罕见变化视觉分析系统 RCAnalyzer。该系统采用一种罕见的类别检测算法来识别异常变化的结构，并在上下文中可视化它们，以帮助专家检查分析结果并标记数据。我们还特别提出了一种新的可视化方法，将动态网络的快照表示为一系列连通的三角矩阵。对每个矩阵进行层次聚类和最优树切割，以说明在其周围结构的上下文中检测到的节点和链接的罕见变化。我们通过案例研究和用户研究来评估我们的技术。评价结果验证了系统的有效性。

</div>

</div>

---

<!--
#### Visualization for Federated Learning: Challenges and Framework.

[`JCAD`](http://www.jcad.cn/jcadcms/news/100000/2020/1c16369247014edeacfb7a338e401db2.shtml) [`📄 PDF`](http://www.jcad.cn/jcadcms/document/attach_manager!download.action?id=4ad554247177d170017196ed8f40000a)

- Authors: Rusheng Pan, 韩东明, **潘嘉铖**, Honghui Mei, Shuyue Zhou, Wei Chen
- 发表地: Journal of Computer-Aided Design & Computer Graphics (Chinese)
- 关键词: `Federated Learning` `Explainable Machine Learning` `Data Privacy` `Anomaly detection`

--- -->

### 2019

#### Structure-based suggestive exploration: A new approach for effective exploration of large networks

#### 基于结构的建议性大规模图可视探索新方法

<div class="keywords">

`大规模图探索` `基于结构的探索` `建议性探索`

</div>

陈为, 郭方舟, 韩东明, <u>**潘嘉铖**</u>, 聂小涛, 夏佳志, 张小龙

<div class="btns">

[`IEEE TVCG`](https://ieeexplore.ieee.org/摘要/document/8440813/) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/Structure-Based%20Suggestive%20Exploration.pdf) [`🎥 视频`](http://www.cad.zju.edu.cn/home/vagblog/videos/Structure-Based%20Suggestive%20Exploration-A%20New%20Approach%20for%20Effective%20Exploration%20of%20Large%20Networks.mp4) [`📰 报告文档`](http://www.cad.zju.edu.cn/home/vagblog/slides/201907/vis2018berlin.pdf) [`👨‍🏫 演讲视频`](https://vimeo.com/299856392) [`👨‍💻 代码`](https://github.com/ZJUVAG/S3) <a href="javascript:"  onclick="copyToClipboard(this)" value="@ARTICLE{ChenGHPNXZ19,
  author={Chen, Wei and Guo, Fangzhou and Han, Dongming and Pan, Jacheng and Nie, Xiaotao and Xia, Jiazhi and Zhang, Xiaolong},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  title={Structure-Based Suggestive Exploration: A New Approach for Effective Exploration of Large Networks},
  year={2019},
  volume={25},
  number={1},
  pages={555-565},
  doi={10.1109/TVCG.2018.2865139}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-ChenGHPNXZ19" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-ChenGHPNXZ19">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_00-32-59.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: IEEE Transactions on Visualization and Computer Graphics
**关键词**: `大规模图探索` `基于结构的探索` `建议性探索`

**摘要**: 在分析可视化网络时，用户需要探索网络的不同部分以获得洞察力。然而，有效地探索大规模网络仍然是一个挑战。虽然用户可以使用各种工具来探索网络的全局和局部特征，但这些工具通常需要大量的交互，例如重复的导航操作来追踪节点和边。在本文中，我们提出了一种基于结构的建议性探索方法，通过建议适当的结构给用户来支持对大型网络的有效探索。该方法通过将节点周围结构的信息转换到高维空间，对节点进行矢量化编码，可以在一个大的网络中识别出相似的结构，同时实现用户与多个相似结构的交互，并指导对未探测结构的探测。我们开发了一个基于 web 的可视探索系统来整合这种提示性的探索方法，并比较了在不同的矢量化方法和网络下我们的方法的性能。我们还通过两个数据集的受控用户研究，展示了方法的可用性和有效性。

</div>

</div>

<br>

#### RankBrushers: interactive analysis of temporal ranking ensembles

#### RankBrushers: 一种对时序排名集合的交互式分析方法

<div class="keywords">

`可视化` `时序排名集合` `不确定性`

</div>

韩东明, <u>**潘嘉铖**</u>, 郭方舟, 罗笑南, 巫英才, 郑文庭, 陈为

<div class="btns">

[`JOV`](https://link.springer.com/article/10.1007/s12650-019-00598-x) [`📄 PDF`](https://www.researchgate.net/profile/Dongming_Han/发表地/336005458_RankBrushers_interactive_analysis_of_temporal_ranking_ensembles/links/5eba2dec92851cd50dab5b36/RankBrushers-interactive-analysis-of-temporal-ranking-ensembles.pdf) [`🎥 视频`](https://jackie-files.oss-cn-hangzhou.aliyuncs.com/9999/ChinaVis_1185.mp4) <a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPGLWZC19,
  author= {Dongming Han and Jiacheng Pan and Fangzhou Guo and Xiaonan Luo and Yingcai Wu and Wenting Zheng and Wei Chen},
  title = {RankBrushers: interactive analysis of temporal ranking ensembles},
  journal = {J. Vis.},
  volume = {22},
  number = {6},
  pages = {1241--1255},
  year = {2019},
  url = {https://doi.org/10.1007/s12650-019-00598-x},
  doi = {10.1007/s12650-019-00598-x},
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPGLWZC19" href="javascript:;"><code>🎈 更多信息</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPGLWZC19">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_00-45-04.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**发表地**: Journal of Visualization
**关键词**: `可视化` `时序排名集合` `不确定性`

**摘要**: 时间排序集合表示时间演化的多元排序。这样的数据在我们的日常生活中很常见，例如，大学的不同排名（QS、ARWU、THE 和 USNews），以及 NBA 球员的不同赛季排名。有效的排名分析和追踪可以让用户深入了解整体排名随时间的变化，并寻求变化的解释。本文介绍了一种新的可视化分析方法，用于刻画和可视化动态排名集合数据的不确定性，动态性和差异。我们提出了一种新的视觉设计来描述大量时间排序集合的演化模式、分布和不确定性。可以通过一个直观的可视化系统对排名集合进行逐步探索，追踪，比较。两个案例研究和一个基于实际数据集的任务驱动用户研究证明了该系统的有效性和可行性。

</div>
</div>

<!--

---

#### Visual Exploration of Topological Structure for Bitcoin Trading Network

[`JOS`](http://www.jos.org.cn/1000-9825/5780.htm) [`📄 PDF`](http://www.jos.org.cn/jos/ch/reader/create_pdf.aspx?file_no=5780&journal_id=jos)

- Authors: **潘嘉铖**, 韩东明, 郭方舟, Wenting Zheng, Jinhui Yu, Wei Chen
- 发表地: Journal of Software (Chinese)
- 关键词: `Bitcoin Network` `Trading Pattern` `Topological Structure`

---

### 2018

#### Visual Analysis for Anomaly Detection in Time-Series: A Survey

[`CRAD`](http://crad.ict.ac.cn/EN/摘要/摘要3761.shtml) [`📄 PDF`](http://crad.ict.ac.cn/EN/article/downloadArticleFile.do?attachType=PDF&id=3761)

- Authors: 韩东明, 郭方舟, **潘嘉铖**, Wenting Zheng, Wei Chen
- 发表地: Journal of Computer Research and Development (Chinese)
- 关键词: `Anomaly Detection` `Visual Analysis` `Visualization` `Time-series Data` `Data Mining`

--- -->

## 🌏 开源贡献

### NetV.js

<div class="btns">

<a href="https://github.com/ZJUVAG/NetV.js/"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a> [`📄 论文`](https://www.sciencedirect.com/science/article/pii/S2468502X21000048) [`🌏 主页`](https://netv.zjuvag.org/)

</div>

一个基于 GPU 的大规模网络可视化工具库

-   主要使用 `TypeScript` 和 `WebGL` 进行开发
-   提供对于图数据的定制化 API
-   支持多种基础交互事件响应

<br />

### OGDF.js

<div class="btns">

<a href="https://github.com/JackieAnxis/ogdf.js"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a>

</div>

封装了来自[OGDF](https://ogdf.uos.de/)的多种图布局的 JavaScript 库

-   为不同的布局算法提供了统一 API
-   包含了多种不同布局（仍在实现中）
-   支持 web worker

## 👨‍💻 工作和科研经历

#### 2018: VIS talk

<div class="btns">

[`📰 报告文档`](http://www.cad.zju.edu.cn/home/vagblog/slides/201907/vis2018berlin.pdf) [`👨‍🏫 报告视频`](https://vimeo.com/299856392)

</div>

-   在 IEEE VIS 2018 国际会议上和韩东明一起报告“基于结构的建议性探索”

#### 2020: VIS talk

<div class="btns">

[`👨‍🏫 报告视频`](https://www.youtube.com/watch?v=qpsBOtN2kcQ&ab_channel=IEEEVisConference2020)

</div>

-   在 IEEE VIS 2020 线上报告“基于范例的节点链接图布局微调技术”

#### 2019 ~ 2021: [之江实验室](http://www.zhejianglab.com/)实习

-   主要负责一个大规模图可视化的项目

## 🏆 奖励和奖学金

#### 硕博连读阶段（2017-2022）

-   浙江大学博士新生奖学金
-   浙江大学蒋震奖学金
-   浙江大学学术新星荣誉

#### 本科阶段（2013-2017）

-   第二届中国大学生“创青春”创业大赛金奖
-   第二届中国大学生“互联网+”创业大赛银奖
-   卓越系列人才培养计划荣誉证书
-   计算机学院未来领袖之星
-   浙报阿里新媒体奖学金
-   浙江大学学业二等奖学金
