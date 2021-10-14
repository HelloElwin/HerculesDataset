# HerkulesDataset

Robot detection dataset by HKU Hercules

## Convert the original format to coco format

[raw2coco.py](https://github.com/HelloElwin/HerculesDataset/blob/main/raw2coco.py)

更完善的版本在`coco_test`分支中。

### 关于标签

将原有的中文标签转成了英文，对照如下表。

| 中文        | English     |
| ----------- | ----------- |
| 机器人      | RobotBody   |
| 装甲板      | RobotArmor  |

`RobotBody`与`RobotArmor`都被划为了`Robot`的子标签以便后期添加障碍物等标签。
