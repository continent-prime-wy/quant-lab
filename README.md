# quant-lab

量化研究的练习仓库，记录我从零开始学习量化分析与策略研究的过程。

## 目录结构

| 目录 | 用途 |
|---|---|
| `src/` | 可复用的 Python 模块（函数、类） |
| `notebooks/` | Jupyter notebook，做数据探索和可视化 |
| `data/` | 本地数据文件（不进版本库） |
| `tests/` | 单元测试 |

## 环境

本项目使用 conda 管理环境，Python 3.12：

```
conda create -n quant python=3.12
conda activate quant
pip install -r requirements.txt
```

## 进度记录

- 2026-10-12：环境搭建，跑通第一个脚本
- 2026-10-13：掌握 Git 工作流（status → add → commit → push）
- 2026-10-14：建立项目目录结构