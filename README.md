# ml-learning - 机器学习技术学习项目

个人机器学习与深度学习技术学习记录和实践项目。

## 项目目标

- 系统学习机器学习基础理论与算法
- 掌握深度学习框架（PyTorch/TensorFlow）
- 实践计算机视觉、自然语言处理等应用
- 探索强化学习、大模型等前沿技术

## 环境配置

### 基础环境要求

| 工具 | 版本 | 说明 |
|------|------|------|
| Python | 3.8+ | 推荐使用 3.10 |
| Jupyter | latest | Notebook 运行环境 |
| Git | latest | 版本控制 |

### 安装依赖

```bash
# 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 或: venv\Scripts\activate  # Windows

# 安装基础包
pip install numpy pandas matplotlib seaborn scikit-learn scipy

# 安装 Jupyter
pip install jupyter notebook ipykernel

# 注册环境到 Jupyter
python -m ipykernel install --user --name=ml-learning
```

### 分阶段环境需求

#### Phase 1: 机器学习基础
```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```
**核心库**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

#### Phase 2: 深度学习入门
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
# 或 GPU 版本: pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
**核心库**: PyTorch, TorchVision

#### Phase 3: 进阶应用
```bash
pip install transformers datasets accelerate
pip install opencv-python pillow
```
**核心库**: Transformers, OpenCV, Pillow

#### Phase 4: 前沿探索
```bash
pip install gymnasium stable-baselines3
pip install onnx onnxruntime
```
**核心库**: Gymnasium, Stable-Baselines3, ONNX

### 验证安装

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import sklearn

print(f"NumPy: {np.__version__}")
print(f"Pandas: {pd.__version__}")
print(f"Scikit-learn: {sklearn.__version__}")
```

---

## 目录结构

```
ml-learning/
├── README.md           # 本文件
├── docs/               # 学习笔记和文档
│   ├── fundamentals/   # 基础理论
│   ├── algorithms/     # 算法详解
│   └── papers/         # 论文阅读笔记
├── notebooks/          # Jupyter Notebook 实验
│   ├── basics/         # 基础练习 (Phase 1)
│   ├── cv/             # 计算机视觉 (Phase 2-3)
│   ├── nlp/            # 自然语言处理 (Phase 3-4)
│   └── rl/             # 强化学习 (Phase 4)
├── projects/           # 完整项目实践
│   └── README.md       # 项目列表
├── resources/          # 资源收集
│   ├── datasets/       # 数据集
│   ├── models/         # 预训练模型
│   └── references/     # 参考资料
└── requirements.txt    # 依赖文件
```

## 学习路线

### Phase 1: 机器学习基础 (4-6周)
**详细设计**: `docs/phase1_curriculum.md`

- [ ] **模块 1**: Python 数据科学基础 (2项目, 3-4天)
- [ ] **模块 2**: 监督学习 - 回归 (3项目, 5-7天)
- [ ] **模块 3**: 监督学习 - 分类 (4项目, 7-10天)
- [ ] **模块 4**: 模型评估与选择 (2项目, 4-5天)
- [ ] **模块 5**: 无监督学习 (2项目, 4-5天)
- [ ] **模块 6**: 综合项目 (1项目, 5-7天)

**总计**: 14个项目, 约4-6周

### Phase 2: 深度学习入门
- [ ] 神经网络基础
- [ ] 反向传播与优化
- [ ] PyTorch 框架学习
- [ ] CNN 与计算机视觉

### Phase 3: 进阶应用
- [ ] RNN/Transformer
- [ ] 目标检测（YOLO/Faster R-CNN）
- [ ] 图像分割
- [ ] 生成模型（GAN/VAE）

### Phase 4: 前沿探索
- [ ] 强化学习基础
- [ ] 大语言模型（LLM）
- [ ] 多模态学习
- [ ] 模型部署与优化

## 学习记录

| 日期 | 内容 | 笔记链接 | 状态 |
|------|------|----------|------|
| 2026-04-22 | 项目初始化 | - | ✅ |

## 参考资料

- [Scikit-learn 官方文档](https://scikit-learn.org/)
- [PyTorch 官方教程](https://pytorch.org/tutorials/)
- [Fast.ai 课程](https://www.fast.ai/)
- [吴恩达机器学习课程](https://www.coursera.org/learn/machine-learning)

---

**创建日期**: 2026-04-22  
**最后更新**: 2026-04-23
