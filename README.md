# PyTorch Playground 🧪

我的 PyTorch 学习与实验基地  
跟着 [Zero to Mastery: Learn PyTorch for Deep Learning](https://www.learnpytorch.io/) 课程进行中（2026版）

## 当前进度 (2026年1月)

- [x] 00 PyTorch Fundamentals  
- [ ] 01 PyTorch Workflow  
- [ ] ...  
- [ ] 05 Going Modular ← 下一个重点！

## 结构说明

- `learn_ztm/` → 课程原始 notebook + 我做的练习  
- `going_modular/` → 从课程 05 开始的模块化代码（会持续优化）  
- `experiments/` → 各种调参对比实验（未来主力）  
- `projects/foodvision_mini/` → 课程 FoodVision 项目（学完后独立完善）  
- `utils/` → 自己封装的小工具函数，越用越多

```
pytorch-playground/
├── learn_ztm/                      # 跟着课程走的原始 notebook + 练习
│   ├── 00_pytorch_fundamentals/
│   │   ├── 00_pytorch_fundamentals.ipynb
│   │   └── exercises/
│   │       └── 00_pytorch_fundamentals_exercises.ipynb   # 自己完成的版本
│   ├── 01_pytorch_workflow/
│   ├── 02_pytorch_classification/
│   ├── 03_pytorch_computer_vision/
│   ├── 04_pytorch_custom_datasets/
│   └── ...                               # 后面章节
│
├── going_modular/                  # 从 05 开始重点维护，课程官方的模块化模板
│   ├── data_setup.py
│   ├── engine.py
│   ├── model_builder.py
│   ├── utils.py
│   └── train.py                    # 课程里的示例训练脚本
│
├── experiments/                    # 调参、对比实验的主战场
│   ├── exp_00_baseline_food101/    # 示例：最简单的 baseline
│   ├── exp_01_more_epochs/
│   └── tracking/                   # 放 wandb run 链接、tensorboard log 截图等
│
├── projects/                       # 独立可展示的小项目（学完后做的）
│   └── foodvision_mini/            # 课程主线项目，最后独立出来
│
├── utils/                          # 自己慢慢积累的工具函数
│   ├── helpers.py                  # set_seed, device, plot_loss 等
│   └── viz.py                      # 自定义可视化函数
│
├── data/                           # 数据文件夹（.gitignore）
│   └── pizza_steak_sushi/          # 课程常用小数据集
│
├── models/                         # 训练好的权重（.gitignore）
│   └── efficientnet_b0_food101.pth
│
├── notebooks/                      # 临时乱七八糟的实验 notebook
│   └── scratch_20260110.ipynb
│
├── requirements.txt                # 需要的依赖
├── .gitignore                      
└── README.md                       # 学习看板
```

欢迎 star/fork，一起成长～ 🚀