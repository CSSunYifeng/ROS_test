# ROS_test
Add urdf (This Repository doesn't use this one while they have same content).
    主要原因在于kr5_arc.xacro中添加的robotNamespace元素拼写错误（kaka写成了kuak）导致命名空间不符合（至于哪些命名空间需要统一，还不是很清楚）。
    
    
   2019.8.26
    已经完成：1.完成ros安装 2.完成kuka_experimental的测试实现上位机ros和机器人的通信，能够进行简单的轴运动 3.初步实现kuka仿真功能（只是为了便于测试上位机程序，不进行机械臂的物理测试）
    当前目标：1.规范化文件结构 2.找到gazebo读取命令和发布状态的节点，形成闭环控制 3.创建纯净工程
    进度：1.文件结构规范：由于kuka_experimental中机器人模型的urdf文件涉及多个文件的内容，所以打算采用kuka_experimental与ros_test并行的文件结构。 2.未开始。3.未开始。





