# 《智能机器人导论》配套资源

本仓库存放书中实验用到的配套文件与代码。技术路线:Ubuntu 24.04 + ROS 2 Jazzy + Gazebo Harmonic。

## resources/gazebo-models

Gazebo 启动仿真场景时需要的两个通用模型(来自 Open Robotics 的 Fuel 模型库,原地址 https://fuel.gazebosim.org/1.0/OpenRobotics/models/ ),国内直连亚马逊服务器常失败,这里放一份副本:

- `ground_plane.zip` — Ground Plane(地面)
- `sun.zip` — Sun(光源)

使用方法见书第 1 章 1.5.3 节:解压到 `~/.gz/fuel/fuel.gazebosim.org/openrobotics/models/"ground plane"/1` 与 `.../sun/1`。
