# Jittor 热身赛

## 简介
本项目包含了第三届计图挑战赛计图 - 热身赛代码实现。本赛道将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 安装 
本项目可在 1 张 1050ti 上运行。

### 运行环境
- windows11
- python = 3.9
- jittor >= 1.3.0

## 训练并推理

单卡训练可运行以下命令：
```
python ./CGAN.py
```

## 致谢

代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)
