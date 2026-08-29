# GPU 计算与机器学习

## 简介

CFD 数值模拟计算量巨大，GPU 并行与数据驱动方法是加速研究的重要手段。

主要关注点：

- **CUDA** 并行编程与 GPU 上的 CFD-DEM 框架（NVIDIA A100）
- **Neural Operator** 等神经网络算子方法，加速流体建模
- TensorFlow 在风功率预测、碳排预测中的应用
- 降阶模型（reduced-order model）与高保真模拟的结合

## 相关论文

1. Jiahui Yu, **Shuai Wang**\*, Kun Luo\*, Jianren Fan. CFD-DEM modeling of dense gas-solid reacting flows in the framework of GPU. *Chemical Engineering Journal*, 2024.
2. Yuhang Ban, Xiaofei Li, **Shuai Wang**\*, Kun Luo, Jianren Fan. A reduced-order model of chemical looping gasification process in fluidized beds. *Chemical Engineering Science*, 2026.

## 学习路线

1. 掌握 Python 与 NumPy，理解向量化计算
2. 学习 CUDA 基础（内存模型、线程组织）
3. 从简单 kernel 开始，再改造 CFD-DEM 的关键模块
4. 学习 TensorFlow / PyTorch，尝试 Neural Operator 对流体场建模
