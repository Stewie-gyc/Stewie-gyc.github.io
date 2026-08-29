# CFD-DEM 气固两相流

## 简介

CFD-DEM 把流体用连续介质方法求解（CFD），把颗粒用离散元方法追踪（DEM），是研究**流化床、气力输送等稠密气固两相流**的重要方法。

我主要关注：

- 流化床内生物质与煤的**共气化**
- **化学链气化**过程的降阶建模（reduced-order model）
- 非球形颗粒（chip-like / super-quadric）的模拟
- GPU 框架下的稠密气固**反应流**

## 相关论文

1. Mengyu Wang, **Shuai Wang**\*, Junjie Lin, Kun Luo, Jianren Fan. Computational study of biomass and coal co-gasification in a bubbling fluidized bed. *Chemical Engineering Journal*, 2026.
2. Yuhang Ban, Xiaofei Li, **Shuai Wang**\*, Kun Luo, Jianren Fan. A reduced-order model of chemical looping gasification process in fluidized beds. *Chemical Engineering Science*, 2026.
3. **Shuai Wang**, Yansong Shen\*. CFD-DEM modelling of dense gas-solid reacting flow: Recent advances and challenges. *Progress in Energy and Combustion Science*, 2025.
4. Jiahui Yu, **Shuai Wang**\*, Kun Luo\*, Jianren Fan. CFD-DEM modeling of dense gas-solid reacting flows in the framework of GPU. *Chemical Engineering Journal*, 2024.
5. **Shuai Wang**, Yansong Shen\*. Super-quadric CFD-DEM simulation of chip-like particles flow in a fluidized bed. *Chemical Engineering Science*, 2022.
6. **Shuai Wang**, Yansong Shen\*. Coarse-grained CFD-DEM modelling of dense gas-solid reacting flow. *International Journal of Heat and Mass Transfer*, 2022.

## 学习路线

1. 先掌握 OpenFOAM 基本求解流程（网格 → 求解 → 后处理）
2. 学习 DEM 基础与 CFDEM / 自研耦合框架
3. 从简单算例（单颗粒沉降）开始，逐步过渡到流化床鼓泡
4. 再进阶 GPU 并行（CUDA）与反应流耦合

!!! tip "建议"
    每学一个知识点，保留一个可复现的小算例，方便以后回看。
