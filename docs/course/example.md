---
title: OpenFOAM 入门示例
date: 2026-08-11
---

# OpenFOAM 入门示例：一篇学习笔记应该怎么写

这篇文章既是我的第一篇 OpenFOAM 学习笔记，也是一篇"格式模板"——以后写笔记按这个格式来就行。

## 1. 这篇笔记讲了什么

OpenFOAM 的基本求解流程是：**准备网格 → 设置初始与边界条件 → 求解 → 后处理**。

## 2. 代码块怎么写

终端里输入的命令用三个反引号包起来：

```bash
blockMesh      # 生成网格
checkMesh      # 检查网格
simpleFoam     # 运行稳态不可压缩流求解器
paraFoam       # 打开后处理
```

## 3. 列表怎么写

- 网格：blockMesh / snappyHexMesh
- 求解：simpleFoam / pisoFoam / reactingFoam
- 后处理：ParaView

## 4. 提醒框怎么写

!!! tip "提示"
    每次修改完算例，记得先运行 `checkMesh` 再求解。

!!! warning "注意"
    OpenFOAM 的字典文件（如 `fvSolution`）缩进必须正确，少一个空格都可能报错。

## 5. 图片怎么写

```markdown
![算例截图](images/example.png)
```

以后把截图放到 `docs/course/images/` 文件夹里即可。

## 6. 写新笔记的步骤

1. 在 `docs/course/` 下新建一个 `.md` 文件
2. 文件开头写上 `title` 和 `date`
3. 保存后推送，GitHub 会自动重新部署
