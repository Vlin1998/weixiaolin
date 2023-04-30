# GPCR-KD

这个代码是GPCR-KD方法的程序。

## 摘要

### 动机

由于新发现的和增量的大规模GPCRs的功能预测一直是生物学研究中的一个热点，大量基于机器学习的算法已经被开发出来用于G-蛋白偶联受体（GPCRs）的分类。 这些前期研究的高准确率揭示了提取有价值的特征和过滤掉冗余是决定整体准确率的关键挑战。为了得到一个更有效的模型，本研究进一步考虑了特征同义词的情况，提出了一种基于功能词聚类和整合的新方法。 该方法背后的本质是新颖的特征知识挖掘策略。与之前的研究不同，所提出的策略在提取的特征和分类器之间增加了一层，利用基于残余物替换矩阵的进化假设来评估每个候选特征的独立性，对候选特征进行聚类，并通过选择主要的功能词来整合它们。这些词是最终的特征，并被用来组成一个特征知识库。然后，GPCR序列被知识库转变成特征向量并被分类器使用。

###结果

该研究对12,731个GPCR序列进行了分类。采用了四种经典的机器学习算法--奈夫贝叶斯算法（NB）、随机森林算法（SF）、支持向量机算法（SVM）和多层感知算法（MLP）--对所有GPCR等级进行分类。令人惊讶的是，新颖的特征知识挖掘策略帮助所有的分类器在所有的测试案例中都取得了显著的改善。 与之前使用相同数据集的方法相比，分类误差降低了。


###用户指南
如果你是第一次使用这个程序，请下载代码并选择 "GPCR-KD-PRO/GPCR-KD-master/seqToResult "文件夹并按照其中的readme操作。


