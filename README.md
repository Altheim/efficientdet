# 如何添加到mmdetection中
## 1-把backbones里的内容添加到mmdet/models/backbones里，再在__init__文件里添加对应内容
## 2-把necks里的内容添加到mmdet/models/necks里，再在__init__文件里添加对应内容
## 3-把configs里的内容添加到configs里
## 4-按照mmdetection的说明操作即可
## ps：如果与训练模型无法自动下载，可以使用下载工具，如迅雷等先下载好后放入/root/.cache/torch/checkpoints/
