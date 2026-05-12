# poskit

多源传感器组合定位  
目标：实现 视觉SLAM、激光SLAM、INS、GNSS等常见传感器的组合定位算法  

要求：
- 传感器数据解耦！
- 算法模块化设计！
- 不追求计算效率，但要求程序可读性！

## 1、运行环境
1、ubuntu20.04  
推荐使用：WSL2  
2、ROS1：Noetic  
推荐使用：（wget http://fishros.com/install -O fishros && . fishros）需要科学上网  
3、


## 2、创建项目
```
mkdir -p ~/poskit/src
cd ~/poskit/src
git clone https://github.com/llliuqingyu/poskit.git
cd ../
catkin_make
source ~/catkin_ws/devel/setup.bash
```

## 3、运行程序
