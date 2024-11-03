# 推搜算法论文总结
这些论文都是经过实战检验的论文，新手入门必看。

## 召回专项：
### Deep Neural Networks for YouTube Recommendations
提出 softmax loss , 必看。 [链接](https://research.google.com/pubs/archive/45530.pdf)
### Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations
提出高热样本在负样本内要打压一下，保持等概率的当负样本。[链接](https://research.google/pubs/sampling-bias-corrected-neural-modeling-for-large-corpus-item-recommendations/) 。附其在NLP的原始paper。[链接](https://arxiv.org/abs/1412.2007)
### Matrix factorization techniques for recommender systems
经典算法。
### ItemCf : Item-Based Collaborative Filtering Recommendation Algorithms 
经典算法，必看。选看 Item-Based Top-N Recommendation Algorithms
### Usercf : User-Based Collaborative-Filtering Recommendation Algorithms on Hadoop
经典算法，必看。
### swing : Large Scale Product Graph Construction for Recommendation in E-commerce
经典算法，必看。 [链接](https://arxiv.org/pdf/2010.05525)
### Mind : Multi-Interest Network with Dynamic Routing for Recommendation at Tmall
经典算法mind，必看。[链接](https://arxiv.org/abs/1904.08030).附胶囊网络paper，[Dynamic Routing Between Capsules](https://arxiv.org/abs/1710.09829)

## attention专项：
### Neural Machine Translation by Jointly Learning to Align and Translate
提出 attention，必看。
### Effective Approaches to Attention-based Neural Machine Translation
总结了几种attention，必看。[链接](链接)
### Attention Is All You Need
懂得都懂。
### BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
同上。
### GPT-3: Language Models are Few-Shot Learners
这能不看？

## 推荐模型专项（包含gate专项，实在是拆不开了，大家都用gate）
### moe : Adaptive Mixtures of Local Experts
必看，万恶之源，通过gate来解决多个expert的融合问题。[链接](https://www.cs.toronto.edu/~hinton/absps/jjnh91.pdf)
### mmoe : Modeling Task Relationships in Multi-task Learning with Multi-gate Mixture-of-Experts
进一步，把moe推广到多任务。 [链接](https://dl.acm.org/doi/abs/10.1145/3219819.3220007)
### ple : Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations
继续，尝试去解决跷跷板问题。[链接](https://dl.acm.org/doi/10.1145/3383313.3412236)
### pepnet : PEPNet: Parameter and Embedding Personalized Network for Infusing with Personalized Prior Information
gate is all you need 。。。 [链接](https://arxiv.org/pdf/2302.01115.pdf)
### poso : POSO: Personalized Cold Start Modules for Large-scale Recommender Systems
同上。。。[链接](https://arxiv.org/abs/2108.04690)

## 推荐基础知识

### 指标
#### 蛤老师文档：https://arxiv.org/pdf/2308.01204.pdf

### 实验平台
#### 快手DID : https://en.wikipedia.org/wiki/Difference_in_differences
#### 微软调平 : The Anatomy of a Large-Scale Online Experimentation Platform
#### CUPED : Improving the Sensitivity of Online Controlled Experiments by Utilizing Pre-Experiment Data

持续更新，后续有时间我会把为什么能拿到收益写出来
