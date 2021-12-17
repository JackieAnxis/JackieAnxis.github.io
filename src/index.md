---
# Language (Optional)
lang: en
# Site Keywords & Description
keywords: Resume, Visualization
description: It is Jiacheng Pan's personal resume.
# Resume Title
resume_title: Jiacheng Pan's Resume
# Job Applicant Name
name: Jiacheng Pan
# Contact
contact:
    # URL
    - icon: fas fa-globe-europe
      text: http://panjiacheng.site/
      url: http://panjiacheng.site/
    # Email
    - icon: fas fa-envelope
      text: panjiacheng@zju.edu.cn
      url: mailto:panjiacheng@zju.edu.cn
    # Github
    - icon: fab fa-github-alt
      text: JackieAnxis
      url: https://github.com/JackieAnxis
    # Blog
    - icon: fas fa-blog
      text: Blog
      url: http://panjiacheng.site/blog
---

{% raw %}
<grid>
<avatar><img src="https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_12-03-42.png"></avatar>

<h1>Jiacheng Pan</h1>
<center>
<a href='/'>English</a> | <a href='/zh-cn/'>简体中文</a>
</center>
<br>
</grid>
{% endraw %}

<div class="btns">

[`🌏 Homepage`](http://panjiacheng.site) [`✉️ panjiacheng@zju.edu.cn`](mailto:panjiacheng@zju.edu.cn) <a href="https://github.com/JackieAnxis"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a> [`💻 Blog`](http://panjiacheng.site/blog)

</div>

## 👻 Personal Information

Jiacheng Pan is now a Ph.D. student in [State Key Lab of CAD&CG](http://www.cad.zju.edu.cn/) at [Zhejiang University](http://www.zju.edu.cn/), China. His current research interests include visualization, visual analytics. From 2013 to 2017, he was an undergraduate student in Zhejiang University. Thereafter he received his Bachelor's degree and became a Master student in State Key Lab of CAD&CG at Zhejiang University. In September, 2019, he became a Ph.D. student under Professor [Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/index.html).

-   Personal Page: http://panjiacheng.site/
-   Github: https://github.com/JackieAnxis
-   Visual Analytics Group of ZJU: https://zjuvag.org/

## 📚 Education

### 2017 ~ Present: Master-Ph.D. <h4 style="display:inline-block;float:right;">Zhejiang University</h4>

Major: Visualization and Visual Analytics

-   Mentor: Professor [Wei Chen](http://www.cad.zju.edu.cn/home/chenwei/index.html)
-   Lab: [State Key Lab of CAD&CG](http://www.cad.zju.edu.cn/index.html)
-   College: [College of Computer Science and Technology](http://www.cs.zju.edu.cn/)

### 2013 ~ 2017: Bachelor <h4 style="display:inline-block;float:right;">Zhejiang University</h4>

Major: Software Engineering

-   College: [College of Computer Science and Technology](http://www.cs.zju.edu.cn/)

Minor: Intensive Training Program of Innovation and Entrepreneurship

-   College: [Chu Kochen Honors College](http://ckc.zju.edu.cn/)

## 📜 Publications

Jiacheng Pan has published seven papers, two of which are published as the first author. These papers mainly focus on **graph visual exploration**, **graph embeddings**, **interactions of graph layout**, **graph visualization authoring** and **anomaly analytics of graph data**.

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

<div class="keywords">

`Semantics` `Deep learning` `Visual analytics` `Topology` `Task analysis` `Computational modeling`

</div>

Dongming Han, <u>**Jiacheng Pan**</u>, Cong Xie, Xiaodong Zhao and Wei Chen

<div class="btns">

[`IEEE CG&A`](https://ieeexplore.ieee.org/document/9490333) <a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPXZC20,
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
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPXZC20" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPXZC20">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/%E5%9B%BE%E7%89%871.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: IFAC-PapersOnLine
**Keywords**: `Semantics` `Deep learning` `Visual analytics` `Topology` `Task analysis` `Computational modeling`

**Abstract**: Representing and analyzing structural differences among graphs help gain insight into the difference related patterns such as dynamic evolutions of graphs. Conventional solutions leverage representation learning techniques to encode structural information, but lack an intuitive way of studying structural semantics of graphs. In this article, we propose a representation-and-analysis scheme for structural differences among graphs. We propose a deep-learning-based embedding technique to encode multiple graphs while preserving semantics of structural differences. We design and implement a web-based visual analytics system to support comparative study of features learned from the embeddings. One distinctive feature of our approach is that it supports semantics-aware construction, quantification, and investigation of latent relations encoded in graphs. We validate the usability and effectiveness of our approach through case studies with three datasets.

</div>
</div>
<br>

#### NetV.js: A web-based library for high-efficiency visualization of large-scale graphs and networks

<div class="keywords">

`Graph` `Graph Visualization` `Network Visualization` `Node-link diagram`

</div>

Dongming Han, <u>**Jiacheng Pan**</u>, Xiaodong Zhao and Wei Chen

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
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPZC21" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" class="hidden-content" id="hidden-content-HanPZC21">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Snipaste_2021-04-20_11-09-06.jpg' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: Visual Informatics
**Keywords**: `Graph` `Graph Visualization` `Network Visualization` `Node-link diagram`
**Abstract**: Graph visualization plays an important role in several fields, such as social media networks, protein–protein interaction networks, and traffic networks. A number of visualization design tools and programming toolkits have been widely used in graph-related applications. However, a key challenge remains in the high-efficiency visualization of large-scale graph data. In this study, we present NetV.js, an open-source and WebGL-based JavaScript library that supports the fast visualization of large-scale graph data (up to 50 thousand nodes and 1 million edges) at an interactive frame rate with a commodity computer.

</div>

</div>

---

### 2020

#### Exemplar-based Layout Fine-tuning for Node-link Diagrams

<div class="keywords">

`Node-link Diagram` `Graph Layout` `Graph Visualization` `User Interactions`

</div>

<u>**Jiacheng Pan**</u>, Wei Chen, Xiaodong Zhao, Shuyue Zhou, Wei Zeng, Minfeng Zhu, Jian Chen, Siwei Fu, Yingcai Wu

<div class="btns">

[`IEEE TVCG`](https://ieeexplore.ieee.org/document/9240072) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/7d531afa561ac4fa5febffe0cb95e38477f73241.pdf) [`🎥 VIDEO`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/29b5e20e480a3e49d58e60aeac01a005ab8f0d32.mp4) [`🎥 PREVIEW`](https://www.youtube.com/watch?v=FdYxjdApGAM&ab_channel=IEEEVisualizationConference) [`📌 SUPPL.`](http://www.cad.zju.edu.cn/home/vagblog/images/photo_bed/2020/8/19/cca9e7fdb68b9cc8de1f7e808c57cfbb1877f3bf.pdf) [`👨‍🏫 PRESENTATION`](https://youtu.be/qpsBOtN2kcQ?t=1130) [`🔗 ARXIV`](https://arxiv.org/abs/2008.00666) <a href="javascript:"  onclick="copyToClipboard(this)" value="@ARTICLE{PanCZZZZCFW21,
  author={Pan, Jiacheng and Chen, Wei and Zhao, Xiaodong and Zhou, Shuyue and Zeng, Wei and Zhu, Minfeng and Chen, Jian and Fu, Siwei and Wu, Yingcai},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  title={Exemplar-based Layout Fine-tuning for Node-link Diagrams},
  year={2021},
  volume={27},
  number={2},
  pages={1655-1665},
  doi={10.1109/TVCG.2020.3030393}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-PanCZZZZCFW21" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-PanCZZZZCFW21">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_19-29-50.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: IEEE Transactions on Visualization and Computer Graphics
**Keywords**: `Node-link Diagram` `Graph Layout` `Graph Visualization` `User Interactions`

**Abstract**: We design and evaluate a novel layout fine-tuning technique for node-link diagrams that facilitates exemplar-based adjustment of a group of substructures in batching mode. The key idea is to transfer user modifications on a local substructure to other substructures in the entire graph that are topologically similar to the exemplar. We first precompute a canonical representation for each substructure with node embedding techniques and then use it for on-the-fly substructure retrieval. We design and develop a light-weight interactive system to enable intuitive adjustment, modification transfer, and visual graph exploration. We also report some results of quantitative comparisons, three case studies, and a within-participant user study.

</div>
</div>
<br>

#### iNet: Visual Analysis of Irregular Transition in Multivariate Dynamic Networks

<div class="keywords">

`Multivariate Dynamic Networks` `Rare Categories` `Anomaly Detection` `Visual Analysis`

</div>

Dongming Han, <u>**Jiacheng Pan**</u>, Rusheng Pan, Dawei Zhou, Nan Cao, Jingrui He, Mingliang Xu, Wei Chen

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
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPPZCHXC22" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPPZCHXC22">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_23-59-37.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: Frontiers of Computer Science
**Keywords**: `Multivariate Dynamic Networks` `Rare Categories` `Anomaly Detection` `Visual Analysis`

**Abstract**: Multivariate dynamic networks indicate networks whose topology structure and vertex attributes are evolving along time. They are common in multimedia applications. Anomaly detection is one of the essential tasks in analyzing these networks though it is not well addressed. In this paper, we combine a rare category detection method and visualization techniques to help users to identify and analyze anomalies in multivariate dynamic networks. We conclude features of rare categories and two types of anomalies of rare categories. Then we present a novel rare category detection method, called DIRAD, to detect rare category candidates with anomalies. We develop a prototype system called iNet, which integrates two major visualization components, including a glyph-based rare category identifier, which helps users to identify rare categories among detected substructures, a major view, which assists users to analyze and interpret the anomalies of rare categories in network topology and vertex attributes. Evaluations, including an algorithm performance evaluation, a case study, and a user study, are conducted to test the effectiveness of proposed methods.

</div>
</div>
<br>

#### RCAnalyzer: Visual Analytics of Rare Categories in Dynamic Networks

<div class="keywords">

`Rare Category Detection` `Dynamic Network` `Visual Analytics`

</div>

<u>**Jiacheng Pan**</u>, Dongming Han, Fangzhou Guo, Dawei Zhou, Nan Cao, Jingrui He, Wei Chen

<div class="btns">

[`FITEE`](http://www.jzus.zju.edu.cn/article.php?doi=10.1631/FITEE.1900310) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/RCAnalyzer-Visual%20Analytics%20of%20Rare%20Categories%20in%20Dynamic%20Networks.pdf) [`🎥 VIDEO`](http://www.cad.zju.edu.cn/home/vagblog/videos/RCAnalyzer-Visual%20Analytics%20of%20Rare%20Categories%20in%20Dynamic%20Networks.mp4) <a href="javascript:" onclick="copyToClipboard(this)" value="@article{PanHGZCHXC20,
  title={RCAnalyzer: visual analytics of rare categories in dynamic networks},
  author={Jia-cheng Pan, Dong-ming Han, Fang-zhou Guo, Da-wei Zhou, Nan Cao, Jing-rui He, Ming-liang Xu, Wei Chen},
  journal={Frontiers of Information Technology & Electronic Engineering},
  volume={21},
  number={4},
  pages={491-506},
  year={2020},
  publisher={Zhejiang University Press & Springer},
  doi={10.1631/FITEE.1900310}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-PanHGZCHXC20" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-PanHGZCHXC20">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-15_23-56-28.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: Frontiers of Information Technology & Electronic Engineering
**Keywords**: `Rare Category Detection` `Dynamic Network` `Visual Analytics`

**Abstract**: A dynamic network refers to a graph structure whose nodes and/or links dynamically change over time. Existing visualization and analysis techniques focus mainly on summarizing and revealing the primary evolution patterns of the network structure. Little work focuses on detecting anomalous changing patterns in the dynamic network, the rare occurrence of which could damage the development of the entire structure. In this study, we introduce the first visual analysis system RCAnalyzer designed for detecting rare changes of sub-structures in a dynamic network. The proposed system employs a rare category detection algorithm to identify anomalous changing structures and visualize them in the context to help oracles examine the analysis results and label the data. In particular, a novel visualization is introduced, which represents the snapshots of a dynamic network in a series of connected triangular matrices. Hierarchical clustering and optimal tree cut are performed on each matrix to illustrate the detected rare change of nodes and links in the context of their surrounding structures. We evaluate our technique via a case study and a user study. The evaluation results verify the effectiveness of our system.

</div>

</div>

---

<!--
#### Visualization for Federated Learning: Challenges and Framework.

[`JCAD`](http://www.jcad.cn/jcadcms/news/100000/2020/1c16369247014edeacfb7a338e401db2.shtml) [`📄 PDF`](http://www.jcad.cn/jcadcms/document/attach_manager!download.action?id=4ad554247177d170017196ed8f40000a)

- Authors: Rusheng Pan, Dongming Han, **Jiacheng Pan**, Honghui Mei, Shuyue Zhou, Wei Chen
- Publication: Journal of Computer-Aided Design & Computer Graphics (Chinese)
- Keywords: `Federated Learning` `Explainable Machine Learning` `Data Privacy` `Anomaly detection`

--- -->

### 2019

#### Structure-based suggestive exploration: A new approach for effective exploration of large networks

<div class="keywords">

`Large Network Exploration` `Structure-Based Exploration` `Suggestive Exploration`

</div>

Wei Chen, Fangzhou Guo, Dongming Han, <u>**Jiacheng Pan**</u>, Xiaotao Nie, Jiazhi Xia, Xiaolong Zhang

<div class="btns">

[`IEEE TVCG`](https://ieeexplore.ieee.org/abstract/document/8440813/) [`📄 PDF`](http://www.cad.zju.edu.cn/home/vagblog/VAG_Work/Structure-Based%20Suggestive%20Exploration.pdf) [`🎥 VIDEO`](http://www.cad.zju.edu.cn/home/vagblog/videos/Structure-Based%20Suggestive%20Exploration-A%20New%20Approach%20for%20Effective%20Exploration%20of%20Large%20Networks.mp4) [`📰 SLIDES`](http://www.cad.zju.edu.cn/home/vagblog/slides/201907/vis2018berlin.pdf) [`👨‍🏫 PRESENTATION`](https://vimeo.com/299856392) [`👨‍💻 CODE`](https://github.com/ZJUVAG/S3) <a href="javascript:"  onclick="copyToClipboard(this)" value="@ARTICLE{ChenGHPNXZ19,
  author={Chen, Wei and Guo, Fangzhou and Han, Dongming and Pan, Jacheng and Nie, Xiaotao and Xia, Jiazhi and Zhang, Xiaolong},
  journal={IEEE Transactions on Visualization and Computer Graphics},
  title={Structure-Based Suggestive Exploration: A New Approach for Effective Exploration of Large Networks},
  year={2019},
  volume={25},
  number={1},
  pages={555-565},
  doi={10.1109/TVCG.2018.2865139}
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-ChenGHPNXZ19" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-ChenGHPNXZ19">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_00-32-59.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: IEEE Transactions on Visualization and Computer Graphics
**Keywords**: `Large Network Exploration` `Structure-Based Exploration` `Suggestive Exploration`

**Abstract**: When analyzing a visualized network, users need to explore different sections of the network to gain insight. However, effective exploration of large networks is often a challenge. While various tools are available for users to explore the global and local features of a network, these tools usually require significant interaction activities, such as repetitive navigation actions to follow network nodes and edges. In this paper, we propose a structure-based suggestive exploration approach to support effective exploration of large networks by suggesting appropriate structures upon user request. Encoding nodes with vectorized representations by transforming information of surrounding structures of nodes into a high dimensional space, our approach can identify similar structures within a large network, enable user interaction with multiple similar structures simultaneously, and guide the exploration of unexplored structures. We develop a web-based visual exploration system to incorporate this suggestive exploration approach and compare performances of our approach under different vectorizing methods and networks. We also present the usability and effectiveness of our approach through a controlled user study with two datasets.

</div>

</div>

<br>

#### RankBrushers: interactive analysis of temporal ranking ensembles

<div class="keywords">

`Visualization` `Temporal Ranking Ensembles` `Uncertainty`

</div>

Dongming Han, <u>**Jiacheng Pan**</u>, Fangzhou Guo, Xiaonan Luo, Yingcai Wu, Wenting Zheng, Wei Chen

<div class="btns">

[`JOV`](https://link.springer.com/article/10.1007/s12650-019-00598-x) [`📄 PDF`](https://www.researchgate.net/profile/Dongming_Han/publication/336005458_RankBrushers_interactive_analysis_of_temporal_ranking_ensembles/links/5eba2dec92851cd50dab5b36/RankBrushers-interactive-analysis-of-temporal-ranking-ensembles.pdf) [`🎥 VIDEO`](https://jackie-files.oss-cn-hangzhou.aliyuncs.com/9999/ChinaVis_1185.mp4) <a href="javascript:"  onclick="copyToClipboard(this)" value="@article{HanPGLWZC19,
  author= {Dongming Han and Jiacheng Pan and Fangzhou Guo and Xiaonan Luo and Yingcai Wu and Wenting Zheng and Wei Chen},
  title = {RankBrushers: interactive analysis of temporal ranking ensembles},
  journal = {J. Vis.},
  volume = {22},
  number = {6},
  pages = {1241--1255},
  year = {2019},
  url = {https://doi.org/10.1007/s12650-019-00598-x},
  doi = {10.1007/s12650-019-00598-x},
}"><code>✒️ BIBTEX</code></a> <a data-fancybox data-src="#hidden-content-HanPGLWZC19" href="javascript:;"><code>🎈 MORE INFO</code></a>

<div style="display: none; width: 80%;" id="hidden-content-HanPGLWZC19">
	<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/Snipaste_2020-09-16_00-45-04.png' style="width: 80%; max-width: max-content; margin: 0 auto;
    display: table;">

**Publication**: Journal of Visualization
**Keywords**: `Visualization` `Temporal Ranking Ensembles` `Uncertainty`

**Abstract**: Temporal ranking ensembles indicate time-evolving multivariate rankings. Such data can be commonly found in our daily life, for example, different rankings of universities (QS, ARWU, THE, and USNews) over year and those of NBA players over season. Effective analysis and tracking of rankings allow users to gain insights into the overall ranking change over time and seek the explanation for the change. This paper introduces a novel visual analytics approach for characterizing and visualizing the uncertainty, dynamics, and differences of ranking ensemble data. A novel visual design is proposed to characterize the evolution pattern, distribution, and uncertainty of a large number of temporal ranking ensembles. The evolutionary ranking ensembles are progressively explored, tracked, and compared by means of an intuitive visualization system. Two case studies and a task-driven user study conducted on real datasets demonstrate the effectiveness and feasibility of the implemented system.

</div>
</div>

<!--

---

#### Visual Exploration of Topological Structure for Bitcoin Trading Network

[`JOS`](http://www.jos.org.cn/1000-9825/5780.htm) [`📄 PDF`](http://www.jos.org.cn/jos/ch/reader/create_pdf.aspx?file_no=5780&journal_id=jos)

- Authors: **Jiacheng Pan**, Dongming Han, Fangzhou Guo, Wenting Zheng, Jinhui Yu, Wei Chen
- Publication: Journal of Software (Chinese)
- Keywords: `Bitcoin Network` `Trading Pattern` `Topological Structure`

---

### 2018

#### Visual Analysis for Anomaly Detection in Time-Series: A Survey

[`CRAD`](http://crad.ict.ac.cn/EN/abstract/abstract3761.shtml) [`📄 PDF`](http://crad.ict.ac.cn/EN/article/downloadArticleFile.do?attachType=PDF&id=3761)

- Authors: Dongming Han, Fangzhou Guo, **Jiacheng Pan**, Wenting Zheng, Wei Chen
- Publication: Journal of Computer Research and Development (Chinese)
- Keywords: `Anomaly Detection` `Visual Analysis` `Visualization` `Time-series Data` `Data Mining`

--- -->

## 🌏 Open Source Contributions

<!-- {% raw %}
<btns rounded>
<a href='https://github.com/ZJUVAG/NetV.js/'>
<img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/20-09-15/NetV.png'>
NetV.js</a>
</btns><br>
{% endraw %} -->

### NetV.js

<div class="btns">

<a href="https://github.com/ZJUVAG/NetV.js/"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a> [`📄 Paper`](https://www.sciencedirect.com/science/article/pii/S2468502X21000048) [`🌏 Homepage`](https://netv.zjuvag.org/)

</div>

A GPU-based large scale **net**work **v**isualization library.

-   Mainly developed using `TypeScript` with `WebGL`
-   Providing customized APIs for graph data
-   Corresponding to plenty of basic interaction events

<br />

### OGDF.js

<div class="btns">

<a href="https://github.com/JackieAnxis/ogdf.js"><code><img src='https://jackie-image.oss-cn-hangzhou.aliyuncs.com/Octocat_inline.png' height=18 style="display: inline; vertical-align: sub;"> Github</code></a>

</div>

A JavaScript graph layout library which encapsulates layout algorithms from [OGDF](https://ogdf.uos.de/).

-   Providing unified APIs for different layout algorithms
-   Containing penlenty of different layouts (in progress)
-   Supporting web worker

## 👨‍💻 Work & Research Experience

#### 2018: VIS talk

<div class="btns">

[`📰 Slides`](http://www.cad.zju.edu.cn/home/vagblog/slides/201907/vis2018berlin.pdf) [`👨‍🏫 PRESENTATION`](https://vimeo.com/299856392)

</div>

-   Presenting Structure-Based Suggestive Exploration at IEEE VIS 2018 with Dongming Han

#### 2020: VIS talk

<div class="btns">

[`👨‍🏫 PRESENTATION`](https://www.youtube.com/watch?v=qpsBOtN2kcQ&ab_channel=IEEEVisConference2020)

</div>

-   Presenting Exemplar-based Layout Fine-tuning for Node-link Diagrams at IEEE VIS 2020 (online)

#### 2019 ~ 2021: Intern of [Zhejiang Lab](http://www.zhejianglab.com/)

-   Mainly responsible for a large scale network visualization project.

#### 2021: VIS 2021 Reviewer

-   Reviewer of IEEE VIS 2021

## 🏆 Awards & Scholarships

#### Master-Ph.D. Period (2017-2022)

-   Freshmen Scholarship of Zhejiang University
-   Jiang Zhen Scholarship of Zhejiang University
-   Certificate of Zhejiang University Academic Star
-   Merit Graduate Student of Zhejiang University
-   Excellent Graduate Student of Zhejiang University
-   Guorui Scholarship of Zhejiang University

#### Bachelor Period (2013-2017)

-   Gold Award of the Second China College Students' Entrepreneurship Competition
-   Silver Award of the Second China "Internet+" College Students Innovation and Entrepreneurship Competition
-   Second-Class Scholarship for Outstanding Merits of Zhejiang University
-   Certificate of Excellence Engineer Training Program
-   Leadership and Service Star Awards of College of Computer Science and Technology
-   Zhejiang Daily & Alibaba New Media Scholarship
