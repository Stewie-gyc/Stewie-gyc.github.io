# 风能与风电场

## 简介

风能方向关注**风力机尾流**与**风电场**的数值建模，结合气象数据与机器学习提升风功率预测精度。

主要关注点：

- 尾流模型：Jensen、Gauss、Gauss-Curl Hybrid、Smart-FARM 等
- 复杂地形风电场的**多目标布局优化**
- 海上风电**超短期功率预测**（融合模型）
- WRF-CFD 耦合模拟

## 相关论文

1. Qiang Wang, Feiyan Xu, Jiahua He, Kun Luo\*, Jianren Fan. A new fusion model for enhanced ultra-short-term offshore wind power forecasting. *Renewable Energy*, 2026.
2. Xiaofeng Zhang, Qiang Wang\*, Xuanxuan Ming, Kun Luo, Jianren Fan. Multi-objective layout optimization in complex terrain wind farms using an improved Non-dominated Sorting Genetic Algorithm. *Energy Conversion and Management*, 2025.
3. Xuanxuan Ming, Qiang Wang, Kun Luo\*, Xiaofeng Zhang, Jianren Fan. Multi-scenario carbon emission forecasting through boosting-assisted logarithmic mean divisia index and low emission analysis platform in Zhejiang, China. *Journal of Cleaner Production*, 2025.

## 学习路线

1. 掌握风力机空气动力学与致动盘/致动线模型
2. 熟悉常见尾流模型与开源工具
3. 学习机器学习（TensorFlow）做功率预测
4. 结合 WRF 气象数据开展耦合研究
