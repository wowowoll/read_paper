# read_paper

day 01

Scene Graph Prediction with Limited Labels

``
这一篇是半监督学习，用少量标记示例将概率关系标记分配给大量未标记图像。
即使用部分标签数据以及未标注的数据，
使用Mask R-CNN以将位标注的数据进行训练，
找到特征部分然后进行数据的进一步处理，最终找到数据的场景图。
在本篇论文中，提出了：
1、通过找到缺失的视觉关系介绍第一种方法来完善视觉知识库。
2、展示了生成的标签在训练现有场景图预测模型中的效用。
3、引入了一种指标来表征视觉关系的复杂性，并表明它是半监督方法相对于迁移学习的改进的有力指标
``

主要算法：

Semi-supervised Alg. to Label Relationships

![这图片: img/SPG0.png SPF1.png](https://github.com/wowowoll/read_paper/tree/master/img/SGP0.png)








