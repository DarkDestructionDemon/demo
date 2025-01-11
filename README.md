# demo
ML架构
--normal/
--project_name/
    ├── data/                  # 数据目录
    ├── checkpoints/           # 保存训练好的模型
    ├── logs/                  # 日志文件夹
    ├── model_hub/             # 预训练模型权重存储
    │   └── chinese-bert-wwm-ext/  # 例如中文BERT的预训练权重
    ├── utils/                 # 辅助模块（日志、评价指标等）
    │   ├── utils.py           # 实用函数
    │   └── metrics.py         # 评估指标
    ├── models/                # 模型文件夹
    │   └── model.py           # 具体模型实现
    ├── configs/               # 配置文件
    │   └── config.py          # 配置参数（例如学习率、batch size 等）
    ├── datasets/              # 数据加载
    │   └── data_loader.py     # 数据加载器（处理数据的批量加载等）
    └── main.py                # 主程序（训练、验证、测试和预测的入口）

--simple/      
----data/：数据
----checkpoints/：保存训练好的模型
----logs/：日志
----model_hub/：预训练模型权重
--------chinese-bert-wwm-ext/：
----utils/：辅助模块，可以是日志、评价指标计算等等
--------utils.py
--------metrics.py
----model.py
----config.py
----data_loader.py
----main.py：主程序，包含训练、验证、测试和预测
