# BDCI 2018-汽车评论主题情感预测

*赛事主页：https://www.datafountain.cn/competitions/310/details/rule*

*队伍ID:USTC_BDCI*



**针对传统的机器学习方法和现在较为流行的深度学习方法分别尝试了两个模型：**
- single_topic中假设每条评论只涉及一个主题，采用的模型是传统的机器学习模型SVM

- multi-topic中针对10种主题和3类情感一共设计了10*3=30个类，采用的是双向RNN+Capsule Network的神经网络模型
