---
title: 《自然·免疫》 - 利用单细胞转录组学揭示新冠肺炎患者整体免疫反应特征
tags: TeXt
show_date: true
pageview: true
key: Blog:自然-免疫
sharing: true
show_author_profile: true
---

今年年初，新冠肺炎(__The coronavirus disease 2019, COVID-19__)疫情在世界范围内快速暴发。根据世界卫生组织(__World Health Organization, WHO__)最新统计数据显示，截止到2020年8月11日，新冠肺炎在全球已导致累计近2000万确诊病例和超过73万死亡病例，平均每天新增俞20万确诊病例和4000死亡病例[1]。新冠肺炎在有些国家仍呈大流行趋势，尚未得到有效控制，目前针对新冠肺炎还没有特效药物和疫苗。因此，揭示疾病进程、阐明发病机制对临床诊治十分重要，尤其是对药物和疫苗的研发尤为关键。针对此科学问题，中国人民解放军总医院第五医学中心__王福生院士__团队与北京大学生物医学前沿创新中心(BIOPIC)、生命科学学院__白凡研究员__团队开展合作研究，应用单细胞测序技术，全面揭示了轻中型、重型新冠肺炎患者及其从发病期到康复期机体整体免疫学变化特征、机制和规律。研究论文"__Single-cell landscape of immunological responses in patients with COVID-19__"于2020年8月12日，在线发表于国际免疫学顶级期刊__Nature Immunology__

![Fig.0](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.0.png)

在本项研究中，研究团队通过对13名新冠肺炎感染者的17例（轻中型7例，重型4例和康复期6例）外周血单个核细胞(Peripheral blood mononuclear cell, PBMC)样本进行高通量单细胞测序，结合单细胞转录组以及免疫组学数据，详细描绘了新冠肺炎轻中型、重型和康复患者的免疫反应图谱。对新冠肺炎临床的研究，治疗和疫苗研发等方面具有重要意义和价值。

![Fig.1](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.1.png)

__图 1: 研究流程示意图与PBMC免疫图谱细胞类型__

首先，研究人员通过整合健康人和新冠肺炎患者的样本，一共获得了122542个高质量的单细胞数据。进一步聚类识别出14种主要的细胞类群，包括T、B淋巴细胞、自然杀伤细胞、单核细胞和树突状细胞等(__图一__)。通过与健康人对比，研究团队在新冠肺炎患者PBMC中发现了与特异性免疫应答相关的细胞占比大幅度上升，如处于激活状态和增殖状态的T细胞以及浆细胞等；而处于未激活状态下的T细胞(naïve T)和单核细胞状来源的树突细胞(Mono DCs)等细胞相对健康人明显下降，这提示新冠肺炎患者存在广泛的免疫激活(__图二__)。尽管处于康复期的新冠肺炎患者的许多临床指标恢复正常，但是像naïve T等细胞类群并没有恢复到健康人的比例。接着为了探究SARS-CoV-2病毒感染导致的患者抗病毒免疫响应情况，团队在进一步研究中发现，在新冠肺炎患者PBMC中，包括天然免疫细胞和适应性免疫细胞等多种细胞类型均存在非常强烈的I型干扰素响应以及较强的急性炎症反应。同时细胞凋亡和迁移能力也有所升高，并且这些现象在重型新冠肺炎患者中尤为明显(__图二__)。

![Fig.2](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.2.png)

__图二：PBMC各种细胞比例与细胞状态比较__

为了更加深入地探究适应性免疫细胞的免疫特点，研究人员对T、B细胞主群进行了进一步的分析和研究，揭示了T、B细胞亚群成分在健康人及新冠肺炎感染不同症状患者中的动态变化、克隆扩增特点等免疫反应特征。首先研究人员将55655个T淋巴细胞细分为12个细胞亚群(__图三__)。发现相比于健康人，处于未激活状态的细胞类群比例在新冠肺炎患者中明显下降，例如CD4+ Naive, CD4+ Memory, CD4+ Effector Memory, Treg, CD8+ Naive 和 NKT Naive 亚群。即使在康复期，CD4+ Naive, CD8+ Naive 和Treg 细胞亚群仍没有恢复到健康人的水平。然而，新冠肺炎患者的激活状态T细胞比例明显增加，包括CD4+ Effector-GNLY, CD8+ Effector-GNLY, NKT CD56 和 NKT CD160 细胞亚群。特别地，研究人员发现了一群在轻中型患者中显著的富集的特异性表达CD160的NKT细胞，这群NKT细胞的转录组特征与之前报道的可以有效抗病毒的NKT /Vδ1 T细胞类似[2-5]，提示这群细胞可能与SARS-CoV-2感染的疾病严重程度相关。通过对T细胞杀伤活性和耗竭状态进行评估，研究人员发现在轻中型患者中效应T细胞表现出更强的细胞杀伤毒性和更低的耗竭状态。然而在重型新冠肺炎患者中效应T细胞展现出更高的耗竭状态(__图三__)。
团队通过整合T细胞转录组与免疫组TCR序列数据，发现相比健康人，新冠肺炎患者T细胞发生了明显的克隆扩增，克隆扩增主要发生在效应T细胞亚群CD4+ Effector-GNLY, CD8+ Effector-GZMK和CD8+ Effector-GNLY中。并且轻中型新冠肺炎患者相比重型展现出更明显有效的克隆扩增(__图四__)。以上结果提示，效应T细胞比例和活性的增加以及有效的克隆扩增等特点可能是轻中型新冠肺炎患者相比重型能更有效控制病毒的原因。

![Fig.3](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.3.png)

__图三：T细胞亚群比例变化与状态比较__

![Fig.4](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.4.png)

__图四：T细胞亚群克隆特征__

针对B淋巴细胞，研究人员将11377个B淋巴细胞细分为6个细胞亚群(__图五__)。相比健康人，新冠肺炎患者记忆B细胞亚群比例明显低于健康人，而生发中心B细胞(Germinal Center B)、浆细胞(Plasma B)和处于增殖状态下的浆细胞(Dividing Plasma B)亚群比例上升。特别是在重型患者中发现了更高比例的浆细胞和正在增殖的浆细胞。在进一步整合B细胞转录组与免疫组BCR序列数据之后，研究团队发现新冠肺炎重型患者的B淋巴细胞中存在IGHV和IGKJ等基因的使用偏好性和明显克隆扩增现象。尤其是浆细胞扩增现象更为明显(__图六__)。以上结果提示体液免疫高度活化是重型患者的典型免疫响应特点。

![Fig.5-1](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.5-1.png)
![Fig.5-2](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.5-2.png)

__图五：B细胞亚群鉴定和比例变化__

![Fig.6](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/BlogPictures/NI/Fig.6.png)

__图六：B细胞亚群克隆特征__

该研究基于高通量单细胞转录组数据及配对的TCR/BCR序列数据，全面刻画了在新冠肺炎感染不同症状患者中，先天性免疫细胞和T、B细胞亚群的动态变化、克隆特点等免疫反应特征。为进一步理解、控制和攻克新冠肺炎疫情提供了宝贵的数据参考和资源。更为关键的是为免疫治疗特别是干细胞治疗奠定了坚实的基础。

### __论文作者信息__

解放军总医院第五医学中心__王福生__院士和北京大学生物医学前沿创新中心(BIOPIC)、生命科学学院__白凡__研究员为本文的共同通讯作者。解放军总医院第五医学中心__张纪元__博士、__徐哲__博士，北京大学生物医学前沿创新中心(BIOPIC)、生命科学学院博士研究生__王湘铭__和清华大学生命科学学院博士研究生__邢旭东__为本文的共同第一作者。该研究受到科技部应急攻关项目和国家自然科学基金创新研究群体项目资助。

### __引用论文__

Zhang, J., Wang, X., Xing, X. et al. __Single-cell landscape of immunological responses in patients with COVID-19.__ __*Nat Immunol*__ 21, 1107–1118 (2020). <https://doi.org/10.1038/s41590-020-0762-x>

### __参考文献__

1. https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports

2. Pizzolato, G. et al. Single-cell RNA sequencing unveils the shared and the distinct cytotoxic hallmarks of human TCRVδ1 and TCR    Vδ2 γδ T lymphocytes. Proc. Natl Acad. Sci. USA 116, 11906–11915 (2019).

3. Couzi, L. et al. Common features of γδ T cells and CD8+ αβ T cells responding to human cytomegalovirus infection in kidney tran    splant recipients. J. Infect. Dis. 200, 1415–1424 (2009).

4. Déchanet, J. et al. Implication of γδ T cells in the human immune response to cytomegalovirus. J. Clin. Invest. 103, 1437–1449     (1999).

5. Farnault, L. et al. Clinical evidence implicating γδ T cells in EBV control following cord blood transplantation. Bone Marrow Tr   anspl. 48, 1478–1479 (2013)

<!--more-->

---

If you like, don't forget to [Follow and Star Me](https://github.com/SeadonXing?tab=stars). :star2:

你的支持就是我的动力。你可以通过以下方式支持我：

[微  信扫码支付赞赏/提问](https://cloud.tsinghua.edu.cn/f/c194e6fe98a64ad3aff5/) --- --- --- [支付宝扫码支付赞赏/提问](https://cloud.tsinghua.edu.cn/f/ba13a434e9b8451e9685/)

![微信扫码支付赞赏](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/Wechat.jpg "Image@141x192"){:width="141px" height="192px"} --- --- --- --- --- --- ![支付宝扫码支付赞赏](https://raw.githubusercontent.com/SeadonXing/SeadonXing.github.io/master/docs/assets/images/Alipay.jpg "Image@128x192"){:width="128px" height="192px"}
