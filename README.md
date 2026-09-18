# Rumen：深度学习学习项目

这是我的《动手学深度学习》（D2L）学习仓库。目标是使用 PyTorch 掌握深度学习基础，并通过可运行的 Notebook、实验记录和阶段项目巩固知识。

教材与代码：

- 在线教材：https://zh.d2l.ai/
- GitHub 原仓库：https://github.com/d2l-ai/d2l-zh

## 学习方法

每一节都按照下面的顺序完成：

1. 阅读教材，写下关键概念。
2. 运行示例代码，并在运行前预测输出。
3. 至少修改两个参数，记录结果变化。
4. 完成节末练习。
5. 整理 Notebook 和笔记。
6. 创建一次有明确说明的 Git commit。

## 当前阶段：预备知识

- [ ] 2.1 数据操作
- [ ] 2.2 数据预处理
- [ ] 2.3 线性代数
- [ ] 2.4 微积分
- [ ] 2.5 自动微分
- [ ] 2.6 概率
- [ ] 2.7 查阅文档

## 后续阶段

- [ ] 第3章：线性神经网络
- [ ] 第4章：多层感知机
- [ ] 第5章：深度学习计算
- [ ] 第6章：卷积神经网络
- [ ] 阶段项目：Fashion-MNIST 图像分类
- [ ] 第10章：注意力机制与 Transformer

## 项目结构

```text
rumen/
├── README.md              # 总进度和项目说明
├── .gitignore             # 不提交缓存、环境和大模型文件
├── notebooks/             # 可运行的 Jupyter Notebook
│   └── chapter02/         # 第2章预备知识
├── notes/                 # 每章学习笔记
├── projects/              # 阶段性独立项目
└── data/                  # 本地数据集（默认不提交 Git）
```

## Git 提交信息示例

```text
Complete chapter 2.1 tensor exercises
Add linear regression experiment
Document autograd observations
Fix Fashion-MNIST evaluation code
```

