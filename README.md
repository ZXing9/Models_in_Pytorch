# Models_in_Pytorch
KG models implementation in pytorch

训练神经网络的过程:

1. 通过网络向前传递

2. 使用网络输出来计算损失

3. 使用loss.backward()在网络中执行向后传播来计算梯度

4. 与优化器一起执行更新权重的步骤

# 使用过程中最麻烦的部分：

1. 评估函数，如何评估预测结果。
2. 数据预处理以及输出结果处理
