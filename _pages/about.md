---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<br>

你好，我叫刘俊，是一名来自中国矿业大学信息与控制工程学院的大三学生，现攻读人工智能专业。

我目前的研究兴趣包括深度学习和机器学习，并且在图像分类以及时间序列预测方向进行了一些尝试....

具体的个人情况请看[个人简历]()

<span class='anchor' id='publications'></span>
<br>
# Publications

## 1. Deep transfer learning based on residual network fusing spatial and channel dual attention mechanism for recognizing spatter degree of converter

- 状态：在投；申请了名为《一种迁移学习和双重注意力机制残差网络的转炉喷溅识别方法》的国家发明专利一项\(学生一作，已受理)。
- 个人贡献：学生一作，主要负责识别算法的设计和实现以及论文的撰写。
- 描述：基于迁移学习技术提出了一种融合双重注意力机制}的残差神经网络以实现高精度转炉火焰喷溅程度自动识别。

## 2. Multivariable system prediction based on TCN-LSTM networks with self-attention mechanism and LASSO variable selection

- 状态：发表于ACS omega，IF:4.1，JCR 二区；[详情](https://pubs.acs.org/doi/full/10.1021/acsomega.3c06263)
- 个人贡献：学生二作，主要负责预测算法的实现和调优。
- 描述：通过利用LASSO 算法对输入变量进行主元分析，设计了融合多头注意力机制的 TCN-LSTM网络，实现对多变量特征序列进行预测。

## 3. Investigation of flexible graphene hybrid knitted sensor for posture recognition based on CNN-LSTM network

- 状态：发表于Journal of Industrial Textiles，IF:3.2，JCR 二区；[详情](https://journals.sagepub.com/doi/full/10.1177/15280837231225827)
- 个人贡献：学生二作，主要负责识别算法的设计和实现以及部分论文的撰写。
- 描述：针对柔性可穿戴传感织物的人体姿势关节变化信号，提出了一种融合自注意力机制的多层CNN-LSTM神经网络智能识别策略。

## 4. LGD-LSTM network with VMD for prediction  nonlinear system subject to input noise

- 状态：被2024年中国控制与决策会议(CCDC)录用
- 个人贡献：第一作者，主要负责预测算法的设计和实现以及论文的撰写。
- 描述：提出了一种基于带有变分模态分解（VMD）降噪的LGD-LSTM网络用于预测带有输入噪声的非线性系统。VMD技术有效的去除了输入信号的噪声；LGD(Local and Global Diffusion)提高了网络对特征的提取能力；LSTM网络提取了时间序列中的长期依赖关系。

## 5. Multivariable system prediction based on parallel GRU-LSTM neural network

- 状态：被2023年中国自动化会议(CAC)录用,已被收录 IEEE 数据库；[详情](https://ieeexplore.ieee.org/abstract/document/10452106)
- 个人贡献：学生一作，主要负责预测算法的设计和实现以及论文的撰写。
- 描述：针对复杂的多输入/输出系统，提出了一种具有\textbf{自注意力机制}的\textbf{并行GRU-LSTM神经网络}预测策略。对两条支路分配不同的权重，使网络能兼顾 LSTM 和 GRU 两种模型的优点，提高了神经网络在处理序列数据时的效果。
