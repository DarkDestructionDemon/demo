# demo
ML架构
--normal/  
----data/：数据
----checkpoints/：保存训练好的模型
----logs/：日志
----model_hub/：预训练模型权重
--------chinese-bert-wwm-ext/：  
----utils/：辅助模块，可以是日志、评价指标计算等等
--------utils.py
--------metrics.py
----models/：模型
--------model.py
----configs/：配置文件
--------config.py
----datasets/：加载数据
--------data_loader.py  
----main.py：主程序，包含训练、验证、测试和预测

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
