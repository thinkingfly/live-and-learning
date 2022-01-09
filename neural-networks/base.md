# 神经网络
## 1 神经元(neuron)模型
神经网络是由具有适应性的简单单元组成的广泛并行互连的网络，它的组织能够模拟生物神经系统对真实世界物体所做出的交互反应。
神经网络最基本的成分是神经元模型

### 1.1 M-P神经元模型
神经元接收到n个其他神经元传递过来的输入信号，这些输入信号通过带权重的连接进行传递，总输入与阈值进行比较，通过激活函数(activation function)进行输出

![M-P神经元模型](https://github.com/thinkingfly/live-and-learning/blob/main/neural-networks/picture/neuron.jpeg "M-P神经元模型")


![](http://latex.codecogs.com/gif.latex?\displaystyle\sum_{i=1}^{n}w_ix_i-\Theta)


$\displaystyle\sum_{i=1}^{n}w_ix_i-\Theta$