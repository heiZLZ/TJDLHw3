

# 卷积神经网络(CNN)

2053066 大数据 朱励钊

## 问题描述：

利用卷积神经网络，实现对MNIST 数据集的分类问题。




## 数据集: 

 	MNIST数据集包括60000张训练图片和10000张测试图片。图片样本的数量已经足够训练一个很复杂的模型（例如 CNN的深层神经网络）。它经常被用来作为一个新 的模式识别模型的测试用例。而且它也是一个方便学生和研究者们执行用例的数据集。除此之外，MNIST数据集是一个相对较小的数据集，可以在你的笔记本CPUs上面直接执行





## 题目要求： 

tensorflow版的卷积神经网路 conv2d() 和max_pool_2x2()函数，然后补全两层卷积的 8个空；

pytorch版本的卷积神经网络 需要补齐  self.conv1 中 nn.Conv2d( )  和 self.conv2( ) 的参数，还需要填写 x = x.view( )中的内容。

两个版本的训练精度都应该在 96% 以上。