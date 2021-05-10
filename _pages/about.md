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

I was a full-time research assistant at [Tsinghua University Natural Language Processing Lab (THUNLP)](http://nlp.csai.tsinghua.edu.cn/site2/index.php/en), advised by Prof. [Zhiyuan Liu](http://nlp.csai.tsinghua.edu.cn/~lzy/). Prior to joining THUNLP, I received my B.Eng. Degree in Computer Science & Technology from Zhejiang University City College (ZUCC). In ZUCC, I worked on Nested NER and SimRank, advised by Prof. [Lin Sun](http://jsxy.zucc.edu.cn/art/2020/4/8/art_2788_194362.html) and Prof. [Fanwei Zhu](http://jsxy.zucc.edu.cn/art/2013/4/18/art_265_94143.html), respectively. They both are Associate Professors at ZUCC and Zhejiang University (ZJU) Master student mentors.

**Note that ZUCC is an independent college, which is neither a branch of ZJU nor one of the campuses of  ZJU. It is directly managed by the People's Government of Zhejiang Province while ZJU belongs to the Ministry of Education of the People’s Republic of China.**

My general research interest lies in Natural Language Processing and Data Mining.

# News

- 2021/05  One paper about attention head mask on multi and cross-lingual tasks is accepted by ACL-IJCNLP 2021.
- 2021/03  I quit my RA job in THUNLP and start to study English, I have to apply this year. QAQ
- 2021/03  One paper about open hierarchical relation extraction is accepted by NAACL-HLT 2021. [code in here](https://github.com/thunlp/OHRE)

- 2021/01  Two papers got accepted by ICASSP 2021.
- 2020/12  Two papers got accepted by AAAI 2021.



# Selected Publications

(\*  indicates equal contribution)

- Contributions of Transformer Attention Heads in Multi- and Cross-lingual Tasks

  Weicheng Ma\*, **Kai Zhang\***, Renze Lou, Lili Wang and Soroush Vosoughi. 

  ACL-IJCNLP 2021, Long Paper. (To appear) 

  <details>
  <summary>Abstract</summary>
    This paper studies the relative importance of attention heads in Transformer-based models to aid their interpretability in cross-lingual and multi-lingual tasks. Prior research has found that only a few attention heads are important in each mono-lingual Natural Language Processing (NLP) task and pruning the remaining heads leads to comparable or improved performance of the model. However, the impact of pruning attention heads is not yet clear in cross-lingual and multi-lingual tasks. Through extensive experiments, we show that (1) pruning a number of attention heads in a multi-lingual Transformer-based model has, in general, positive effects on its performance in cross-lingual and multi-lingual tasks and (2) the attention heads to be pruned can be ranked using gradients and identified with a few trial experiments. Our experiments focus on sequence labeling tasks, with potential applicability on other cross-lingual and multi-lingual tasks. For comprehensiveness, we examine two pre-trained multi-lingual models, namely multi-lingual BERT (mBERT) and XLM-R, on three tasks across 9 languages each. We also discuss the validity of our findings and their extensibility to truly resource-scarce languages and other task settings.
  </details>

- Open Hierarchical Relation Extraction

  **Kai Zhang\***, Yuan Yao*, Ruobing Xie, Xu Han, Zhiyuan Liu, Fen Lin, Leyu Lin and Maosong Sun. 

  NAACL-HLT 2021, Long Paper. (To appear) \[[code](https://github.com/thunlp/OHRE)\]

  <details>
  <summary>Abstract</summary>
  Open relation extraction (OpenRE) aims to extract novel relation types from open-domain corpora, which plays an important role in completing the relation schemes of knowledge bases (KBs). Most OpenRE methods cast different relation types in isolation without considering their hierarchical dependency. We argue that OpenRE is inherently in close connection with relation hierarchies. To address the bidirectional connections between OpenRE and relation hierarchy, we propose the task of open hierarchical relation extraction and present a novel OHRE framework for the task. To effectively integrate hierarchy information into relation representations for better novel relation extraction, we propose a dynamic hierarchical triplet objective and hierarchical curriculum training paradigm. We also present a top-down hierarchy expansion algorithm to add the extracted relations into existing hierarchies with reasonable interpretability. Comprehensive experiments show that OHRE outperforms state-of-the-art models by a large margin on both relation clustering and hierarchy expansion. The source code and experiment details of this paper can be obtained from https://github.com/thunlp/OHRE.
  </details>

- MORE: A Metric Learning Based Framework for Open-Domain Relation Extraction. 

  Yutong Wang\*, Renze Lou\*, **Kai Zhang\***, Maoyan Chen and Yujiu Yang. 

  ICASSP 2021. (To appear) \[[code](https://github.com/RenzeLou/MORE)\]

  <details>
  <summary>Abstract</summary>
  TODO
  </details>

- Improving Social Media NER via Entity Type-Compatible Unknown Word Substitution. 

  Jian Xie\*, **Kai Zhang\***, Lin Sun, Yindu Su and Chenxiang Xu. 

  ICASSP 2021. (To appear) 

  <details>
  <summary>Abstract</summary>
  Named entity recognition (NER) is a fundamental task for information extraction (IE), and current state-of-the-art methods try to address this issue and achieve high performance on clean text (e.g., newswire genres). However, most of these algorithms do not generalize well when they transit to the noisy domain such as social media. To alleviate the noisy expression in social media data, we present a novel word substitution strategy based on constructing an entity type-compatible (ETC) semantic space. We substitute unknown words with the ETC words found by deep metric learning (DML) and nearest neighbor (NN) search. Comprehensive experiments show that the proposed framework achieves state-of-the-art performance on the W-NUT2017 dataset and the novel strategy brings good generality to multiple NER tools and previous works.
  </details>

- Adversarial Language Games for Advanced Natural Language Intelligence. 

  Yuan Yao, Haoxi Zhong, Zhengyan Zhang, Xu Han, Xiaozhi Wang, **Kai Zhang**, Chaojun Xiao, Guoyang Zeng, Zhiyuan Liu and Maosong Sun.

  AAAI 2021, Long Paper. (To appear) \[[code](https://github.com/Multimodal-NER/RpBERT)\]

  <details>
  <summary>Abstract</summary>
  We study the problem of adversarial language games, in which multiple agents with conflicting goals compete with each other via natural language interactions. While adversarial language games are ubiquitous in human activities, little attention has been devoted to this field in natural language processing. In this work, we propose a challenging adversarial language game called Adversarial Taboo as an example, in which an attacker and a defender compete around a target word. The attacker is tasked with inducing the defender to utter the target word invisible to the defender, while the defender is tasked with detecting the target word before being induced by the attacker. In Adversarial Taboo, a successful attacker and defender need to hide or infer the intention, and induce or defend during conversations. This requires several advanced language abilities, such as adversarial pragmatic reasoning and goal-oriented language interactions in open domain, which will facilitate many downstream NLP tasks. To instantiate the game, we create a game environment and a competition platform. Comprehensive experiments on several baseline attack and defense strategies show promising and interesting results, based on which we discuss some directions for future research. The code and datasets of this paper can be obtained from https://github.com/thunlp/AdversarialTaboo.
  </details>

- RpBERT: A Text-image Relation Propagation-based BERT Model for Multimodal NER. 

  Lin Sun\*, Jiquan Wang\*, **Kai Zhang**, Fangsheng Weng and Yindu Su. 

  AAAI 2021, Long Paper. (To appear) [[code](https://github.com/Multimodal-NER/RpBERT)]

  <details>
  <summary>Abstract</summary>
    Recently multimodal named entity recognition (MNER) has utilized images to improve the accuracy of NER in tweets. However, most of the multimodal methods use attention mechanisms to extract visual clues regardless of whether the text and image are relevant. Practically, the irrelevant text-image pairs account for a large proportion in tweets. The visual clues that are unrelated to the texts will exert uncertain or even negative effects on multimodal model learning. In this paper, we introduce a method of text-image relation propagation into the multimodal BERT model. We integrate soft or hard gates to select visual clues and propose a multitask algorithm to train on the MNER datasets. In the experiments, we deeply analyze the changes in visual attention before and after the use of text-image relation propagation. Our model achieves state-of-the-art performance on the MNER datasets.
  </details>

- A TOI based CNN with Location Regression for Insurance Contract Analysis.

  **Kai Zhang**, Lin Sun, Fule Ji.

  IJCNN 2019, Long & Oral. \[[code](https://github.com/ETIP-team/ETIP-Project)\] [[paper](https://ieeexplore.ieee.org/abstract/document/8852052/)]

  <details>
  <summary>Abstract</summary>
  	Contract analysis with AI techniques can significantly ease the work for humans. This paper shows a problem of Element Tagging on Insurance Policy (ETIP). We present a novel Text-Of-Interest (TOI) convolutional neural network for the ETIP solution. We introduce a TOI pooling layer to replace traditional pooling layer for processing the nested phrasal or clausal elements in insurance policies. The advantage of TOI pooling layer is that the nested elements from one sentence could share computation and context in the forward and backward passes. The computation of backpropagation through TOI pooling is also demonstrated in the paper. In addition, a location regressor is trained to improve the precision of element localization, called TOI-CNN+LR. In the detection, we devise a novel non-maximum suppression method with the fusion of length and score metrics, called LS-NMS. A large Chinese insurance contract dataset was collected to test the performance of the proposed method. An extensive set of experiments is performed to investigate how TOI- CNN+LR can work effectively in insurance elements tagging and outperforms other state-of-the-art nested NER models.
  </details>

- TOI-CNN: A Solution of Information Extraction on Chinese Insurance Policy.

  Lin Sun\*, **Kai Zhang\***, Fule Ji and Zhenhua Yang. 

  NAACL-HLT 2019, Industry Track. \[[code](https://github.com/ETIP-team/ETIP-Project)\] [[paper](https://www.aclweb.org/anthology/N19-2022.pdf)]
  
  <details>
  <summary>Abstract</summary>
  Contract analysis can significantly ease the work for humans using AI techniques. This paper shows a problem of Element Tagging on Insurance Policy (ETIP). A novel Text-Of-Interest Convolutional Neural Network (TOI- CNN) is proposed for the ETIP solution. We introduce a TOI pooling layer to replace traditional pooling layer for processing the nested phrasal or clausal elements in insurance policies. The advantage of TOI pooling layer is that the nested elements from one sentence could share computation and context in the forward and backward passes. The computation of backpropagation through TOI pooling is also demonstrated in the paper. We have collected a large Chinese insurance contract dataset and labeled the critical elements of seven categories to test the performance of the proposed method. The results show the promising performance of our method in the ETIP problem.
  </details>



## Seleted Honors & Awards

2020, Honor for Seeking Truth & Giving Commencement Address, ZUCC (Top 1)

2019, Special Assessment National Scholarship, Ministry of Education of the Peoples Republic of China (Top 10 in Zhejiang Province)

2019, National Scholarship, Ministry of Education of the Peoples Republic of China (Top 1%)

2019, Chinese College Students Self-Improvement Stars, All-China Students’ Federation (Top 200 in China for Technological Innovation)