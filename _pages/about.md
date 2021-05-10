---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# About me

I am a full-time research assistant at [Tsinghua University Natural Language Processing Lab (THUNLP)](http://nlp.csai.tsinghua.edu.cn/site2/index.php/en), advised by Prof. [Zhiyuan Liu](http://nlp.csai.tsinghua.edu.cn/~lzy/). Prior to joining THUNLP, I received my B.Eng. Degree in Computer Science & Technology from Zhejiang University City College (ZUCC). In ZUCC, I worked on Nested NER and SimRank, advised by Prof. [Lin Sun](http://jsxy.zucc.edu.cn/art/2020/4/8/art_2788_194362.html) and Prof. [Fanwei Zhu](http://jsxy.zucc.edu.cn/art/2013/4/18/art_265_94143.html), respectively. They both are Associate Professors at ZUCC and Zhejiang University (ZJU) Master student mentors.

**Note that ZUCC is an independent college, which is neither a branch of ZJU nor one of the campuses of  ZJU. It is directly managed by the People's Government of Zhejiang Province while ZJU belongs to the Ministry of Education of the People’s Republic of China.**

My general research interest lies in Natural Language Processing and Data Mining.

# News

- 2021/05  One paper about attention head mask on multi and cross-lingual tasks is accepted by ACL-IJCNLP 2021. 

- 2021/03  One paper about open hierarchical relation extraction is accepted by NAACL-HLT 2021. [code in here](https://github.com/thunlp/OHRE)



<details>
  <summary>折叠文本</summary>
  此处可书写文本
  嗯，是可以书写文本的
</details>

​     









# Selected Publications

(\*  indicates equal contribution)

<details>
<summary>Contributions of Transformer Attention Heads in Multi- and Cross-lingual Tasks</summary>
	This paper studies the relative importance of attention heads in Transformer-based models to aid their interpretability in cross-lingual and multi-lingual tasks. Prior research has found that only a few attention heads are important in each mono-lingual Natural Language Processing (NLP) task and pruning the remaining heads leads to comparable or improved performance of the model. However, the impact of pruning attention heads is not yet clear in cross-lingual and multi-lingual tasks. Through extensive experiments, we show that (1) pruning a number of attention heads in a multi-lingual Transformer-based model has, in general, positive effects on its performance in cross-lingual and multi-lingual tasks and (2) the attention heads to be pruned can be ranked using gradients and identified with a few trial experiments. Our experiments focus on sequence labeling tasks, with potential applicability on other cross-lingual and multi-lingual tasks. For comprehensiveness, we examine two pre-trained multi-lingual models, namely multi-lingual BERT (mBERT) and XLM-R, on three tasks across 9 languages each. We also discuss the validity of our findings and their extensibility to truly resource-scarce languages and other task settings.
</details>

​    Weicheng Ma\*, **Kai Zhang\***, Renze Lou, Lili Wang and Soroush Vosoughi. 

​	ACL-IJCNLP 2021, Long Paper. (To appear) 

<details>
<summary>Open Hierarchical Relation Extraction</summary>
Open relation extraction (OpenRE) aims to extract novel relation types from open-domain corpora, which plays an important role in completing the relation schemes of knowledge bases (KBs). Most OpenRE methods cast different relation types in isolation without considering their hierarchical dependency. We argue that OpenRE is inherently in close connection with relation hierarchies. To address the bidirectional connections between OpenRE and relation hierarchy, we propose the task of open hierarchical relation extraction and present a novel OHRE framework for the task. To effectively integrate hierarchy information into relation representations for better novel relation extraction, we propose a dynamic hierarchical triplet objective and hierarchical curriculum training paradigm. We also present a top-down hierarchy expansion algorithm to add the extracted relations into existing hierarchies with reasonable interpretability. Comprehensive experiments show that OHRE outperforms state-of-the-art models by a large margin on both relation clustering and hierarchy expansion. The source code and experiment details of this paper can be obtained from https://github.com/thunlp/OHRE.
</details>

​	**Kai Zhang\***, Yuan Yao*, Ruobing Xie, Xu Han, Zhiyuan Liu, Fen Lin, Leyu Lin and Maosong Sun. 

​	NAACL-HLT 2021, Long Paper. (To appear) \[[code](https://github.com/thunlp/OHRE)\]

- MORE: A Metric Learning Based Framework for Open-Domain Relation Extraction. 

  Yutong Wang\*, Renze Lou\*, **Kai Zhang\***, Maoyan Chen and Yujiu Yang. 

  ICASSP 2021. (To appear) \[[code](https://github.com/RenzeLou/MORE)\]

- Improving Social Media NER via Entity Type-Compatible Unknown Word Substitution. 

  Jian Xie\*, **Kai Zhang\***, Lin Sun, Yindu Su and Chenxiang Xu. 

  ICASSP 2021. (To appear) 

- Adversarial Language Games for Advanced Natural Language Intelligence. 

  Yuan Yao, Haoxi Zhong, Zhengyan Zhang, Xu Han, Xiaozhi Wang, **Kai Zhang**, Chaojun Xiao, Guoyang Zeng, Zhiyuan Liu and Maosong Sun.

  AAAI 2021, Long Paper. (To appear) \[[code](https://github.com/Multimodal-NER/RpBERT)\]

- RpBERT: A Text-image Relation Propagation-based BERT Model for Multimodal NER. 

  Lin Sun\*, Jiquan Wang\*, **Kai Zhang**, Fangsheng Weng and Yindu Su. 

  AAAI 2021, Long Paper. (To appear) [[code](https://github.com/Multimodal-NER/RpBERT)]

- A TOI based CNN with Location Regression for Insurance Contract Analysis.

  **Kai Zhang**, Lin Sun, Fule Ji.

  IJCNN 2019, Long & Oral. \[[code](https://github.com/ETIP-team/ETIP-Project)\] [[paper](https://ieeexplore.ieee.org/abstract/document/8852052/)]

- TOI-CNN: A Solution of Information Extraction on Chinese Insurance Policy.

  Lin Sun\*, **Kai Zhang\***, Fule Ji and Zhenhua Yang. 

  NAACL-HLT 2019, Industry Track. \[[code](https://github.com/ETIP-team/ETIP-Project)\] [[paper](https://www.aclweb.org/anthology/N19-2022.pdf)]



## Seleted Honors & Awards

2020, Honor for Seeking Truth & Giving Commencement Address, ZUCC (Top 1)

2019, Special Assessment National Scholarship, Ministry of Education of the Peoples Republic of China (Top 10 in Zhejiang Province)

2019, National Scholarship, Ministry of Education of the Peoples Republic of China (Top 1%)

2019, Chinese College Students Self-Improvement Stars, All-China Students’ Federation (Top 200 in China for Technological Innovation)