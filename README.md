# EHR_PAPER
top paper list

# 2023
## Time-Aware Context-Gated Graph Attention Network for Clinical Risk Prediction
要点总结：
1


已有的方法通常过于关注时间特征或临床事件变量的内在关系，或者分两个阶段提取这些信息，导致患者的特征信息不足，从而降低预测性能。

基于异构图神经网络的现有方法通常需要手动选择元路径，这是一个缺点。

为解决上述问题，提出了一个新的模型：时间感知上下文门控图注意网络（Time-Aware Context-Gated Graph Attention Network, T-ConextGGAN）。

T-ConextGGAN包含一个具有时间感知元路径和自我注意机制的图神经网络（GNN）模块，能够同时提取EHR数据的时间语义信息和内在关系，并自动选择元路径。

通过使用来自两个开源数据集的第一次ICU入院的前48小时的EHR数据，对该模型进行了评估，同时对EHR图上的各种临床变量进行了建模。

大量的实验结果表明，T-ConextGGAN能够有效地提取信息特征，并在多个预测指标上优于现有的先进模型。

T-ConextGGAN的代码https://github.com/OwlCitizen/TContext-GGAN.

# 2022
ELDA:Learning Explicit Dual-Interactions for Healthcare Analytics # Using TensorFlow backend.

# 2021 

Cooperative Joint Attentive Network for Patient Outcome Prediction on Irregular Multi-Rate Multivariate Health Data
AttDMM: An Attentive Deep Markov Model for Risk Scoring in Intensive Care Units
