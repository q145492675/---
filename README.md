# 机器学习&深度学习深度好文汇总（BLOG）
## 机器学习
* 机器学习性能提高： URL:http://blog.csdn.net/han_xiaoyang/article/details/53453145
* 数据预处理:
  * 特征选择：
    * 去除方差较小的特征。
    * 正则化。L1正则化能够生成稀疏的模型。L2正则化的表现更加稳定，由于有用的特征往往对应系数非零。
    * 随机森林，对于分类问题，通常采用基尼不纯度或者信息增益，对于回归问题，通常采用的是方差或者最小二乘拟合。
    * 稳定性选择，是在不同的数据子集和特征子集上运行特征选择算法，不断的重复，最终汇总特征选择结果。
  * 归一化数据： 
    *  把数变为（0，1）之间的小数主要是为了数据处理方便提出来的，把数据映射到0～1范围之内处理，更加便捷快速。
    *  把有量纲表达式变为无量纲表达式 归一化是一种简化计算的方式，即将有量纲的表达式，经过变换，化为无量纲的表达式，成为纯量。
  * 标准化数据:
     * 将数据按比例缩放，使之落入一个小的特定区间。由于信用指标体系的各个指标度量单位是不同的，为了能够将指标参与评价计算，需要对指标进行规范化处理，通过函数变换将其数值映射到某个数值区间。
 * Support Vector Machine (支持向量机)
   *  在CNN中使用SVM进行分类-Keras实现。 URL: http://blog.csdn.net/ying86615791/article/details/71366184
* 神仙打架：CIFAR10和MNIST 数据库判别准确率Ranking。  URL：http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html#4d4e495354
## 深度学习
* 怎么训练/预测 Variable Size 的数据：  URL:https://github.com/keras-team/keras/issues/1920
* 深度学习性能提高:   URL: http://blog.csdn.net/han_xiaoyang/article/details/52654879
* 生成对抗网络(GANs):
  * GANs科普： URL: http://blog.csdn.net/c2a2o2/article/details/54408072
  *   Cycle-GANs 科普: URL: http://blog.csdn.net/c2a2o2/article/details/73338026
  * GANs training trick: https://github.com/soumith/ganhacks  (GANHACKs)
  * GANs training expression: https://medium.com/@utk.is.here/keep-calm-and-train-a-gan-pitfalls-and-tips-on-training-generative-adversarial-networks-edd529764aa9
* 卷积神经网络(CNN):
  *  CNN的调优方法:  URL:http://blog.csdn.net/app_12062011/article/details/64439627
* 残差网络(ResNet):
  *  ResNet 科普:  URL:  http://blog.csdn.net/scety/article/details/52957991
* 激活函数(Activation):
  *  ReLU/LReLU/PReLU等函数定义：  URL:http://blog.csdn.net/qq_20909377/article/details/79133981
* 什么问题不适合用深度学习的方法解决？
  * 数据集太小，数据样本不足时，深度学习相对其它机器学习算法，没有明显优势。
  *  数据集没有局部相关特性，目前深度学习表现比较好的领域主要是图像／语音／自然语言处理等领域，这些领域的一个共性是局部相关性。图像中像素组成物体，语音信号中音位组合成单词，文本数据中单词组合成句子，这些特征元素的组合一旦被打乱，表示的含义同时也被改变。对于没有这样的局部相关性的数据集，不适于使用深度学习算法进行处理。举个例子：预测一个人的健康状况，相关的参数会有年龄、职业、收入、家庭状况等各种元素，将这些元素打乱，并不会影响相关的结果卷积神经网络。
* Attention Machanism:  URL:https://distill.pub/2016/augmented-rnns/
## 不断添加，未完待续~~ :)
