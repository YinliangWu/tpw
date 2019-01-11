---
layout: post
title: 2018 ML和 NLP 学术论文统计
author:  
tags: [ 资讯, 人工智能, 机器学习, 自然语言处理]
excerpt: ddd...
category:
- 资讯 
image: 
  path: http://www.cnv4.com/images/aiindex2018.png
  width: 1200
  height: 630
comments: true 
---

####  导读

今年的统计数据包括以下会议/期刊：ACL、EMNLP、NAACL、EACL、COLING、TACL、CL、CoNLL、NeurIPS、ICML、ICLR 和 AAAI。这种选择是为了覆盖机器学习和语言技术领域最知名和高级别的会议。和去年相比，我移除了 SemEval，因为它很大一部分是关注共享任务的论文，我在其它会议中也没有包括这些主题。此外，我添加了 AAAI，它在过去的排名中并没有出现。NeurIPS 去年改名了（原名为 NIPS），在这里将使用最新的名称。
这个分析是通过一系列脚本自动完成的，这些脚本多年来一直在不断改进。论文列表是从在线论文集中抓取的，通常也可以在那里找到作者姓名。组织名称需要直接从 PDF 中提取，这可能会导致相当多的噪声。我创建了各种方法来检测和映射不同类型的名称。

虽然这篇文章重点介绍了近年发表论文最多的研究者和组织，但我想指出，我不认为论文发表数量是一个领域应该追求或奖励的东西。如下图所示，该领域正变得越来越流行，而且论文数量的快速增长伴随着质量参差不齐。写一篇开创性的论文总比发布 10 篇完全可忘记的充数论文更好。这篇文章旨在对目前发表论文的研究者和组织以及发表会议的情况提供一个高级视图，说不定能为具有好创意的新研究人员提供一些灵感。

#### 会议：

我们首先看一下所有会议在 2012-2018 年间的论文发表数量。大多数机器学习会议的论文发表数都在继续增长，其中 AAAI 和 NeurIPS 超过了 1000 篇。EMNLP 和 NAACL 相比往届也有大幅增长，而 ACL 和 COLING 的发表数和往届差不多。EACL 今年没有举行，TACL 和 CL 的论文发表数多年来一直保持平稳。（注意图中为零的点表示会议在该年份没有举行。）


<img src='/images/mlnlpstat/01.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

#### 作者

下面，我们来看看 2018 年在这些大会上发表论文最多的作者。有三位研究人员的论文发表数量惊人，均为 22 篇。这三人分别是周明（微软）、Graham Neubig（卡耐基梅隆大学）和 Sergey Levine（UC 伯克利）。紧随其后的是张潼（腾讯 AI，近期离职）、孙茂松（清华大学）和 Iryna Gurevych（达姆施塔特工业大学）。
 
<img src='/images/mlnlpstat/02.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

从 2012-2018 年的总发表量来看，Chris Dyer（DeepMind）仍位居前列，一共发表了 97 篇论文。紧随其后的是周明（微软）、Yoshua Bengio（蒙特利尔大学）、张岳（西湖大学）和 Noah A. Smith（华盛顿大学）。大部分作者都有所偏好，要么偏爱 NLP 领域，要么重点在核心 ML。只有 Percy Liang 大概是个例外，两边不偏不倚。
 
<img src='/images/mlnlpstat/03.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

我们还可以查看每个作者在不同年份发表的论文数量。Chris Dyer 在 2015、2016 这两年的论文数增长幅度令人瞩目。

<img src='/images/mlnlpstat/04.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

#### 一作

接下来看一下关于一作的统计数据。前面所提到的作者大部分是团队领导人，而通常一作才是实际研究、做实验和撰写论文大部分内容的人。这类作者当中的佼佼者当属南洋理工大学的 Yi Tay。他已读博三年，2018 年在几个主要大会上共发表 10 篇一作论文。其次是微软研究院的朱泽园，共发表 6 篇一作论文。紧随其后的有香港大学的 Mikel Artetxe、Jiatao Gu，杜克大学的 Dinghan Shen 和康奈尔大学的 Nathan Kallus，每人亦发表 5 篇一作论文。

<img src='/images/mlnlpstat/05.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>
 
再看看总发表量，李纪为（香侬科技）发表了 22 篇一作论文。其后是朱泽园（微软）、Young-Bum Kim（亚马逊）、Ryan Cotterell（剑桥大学）和 Ivan Vulić（剑桥大学）。

<img src='/images/mlnlpstat/06.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>
 
#### 组织机构

接下来是关于组织机构的统计数据。和前两年一样，CMU 仍位居榜首。谷歌和微软仍然是业界领头羊。清华、斯坦福、北大、MIT 和伯克利紧随其后。
值得一提的是，来自中国的机构中，清华大学、北京大学、中国科学院大学、中国科学院、上海交大、香港中文大学在发表论文最多的机构中名列前茅。其中清华大学名列第四，北京大学名列第六，中国科学院大学和中国科学院分别是第九和第十一。
 
<img src='/images/mlnlpstat/07.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

我们再来看一下 2012-2018 年的组织排名，结果是类似的。CMU 仍然占据首位，微软和谷歌分列第二、第三位，和 2018 年的数据翻了个个儿。普林斯顿大学、法国国家信息与自动化研究所（INRIA）、杜克大学似乎主要关注核心机器学习，在 NLP 领域发表的文章很少。相反，清华、中科院和爱丁堡大学主要聚焦于语言应用。
 
<img src='/images/mlnlpstat/08.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

从下图时间线中，我们可以看到 CMU 多年来维持大量的论文输出，且仍在继续增长。谷歌和微软竞争激烈，目前似乎谷歌稍占上风。中国大学（如清华、北大）目前的论文输出数量正在飞速增长。

<img src='/images/mlnlpstat/09.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

#### 主题聚类

最后，我对作者和机构进行了主题聚类。我收集了与特定作者/机构有关的所有论文，把它们统一处理为小写并 token 化，然后用 LDA 处理这些论文并用 t-SNE 进行可视化。排名靠前的论文实体有非常好的可视化结果，显示出了他们的论文内容与图中其他人内容的相似关系。

<img src='/images/mlnlpstat/10.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

<img src='/images/mlnlpstat/11.jpg' alt="" class="img-responsive" style="margin:0 auto;"/>

#### 参考文献：

原文：http://www.marekrei.com/blog/ml-and-nlp-publications-in-2018/

#### 下载：

<br/>

<h5 class="red-text text-center">长按下图关注公众号 "<b>慧识力量</b>"，发送 "<b>ai2018</b>" 获取 94 页完整报告</h5>

<img src='/images/powertoknow_x.png' alt="关注慧识力量" class="img-responsive" style="margin:0 auto;"/>

