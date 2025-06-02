本仓库测试于Ubuntu 20.04 ros-noetic
## 安装依赖
```shell
sudo apt install ros-noetic-serial
```
## Git Clone And Compile
```shell
mkdir -p catkin_ws/src
cd catkin_ws/src
git clone https://github.com/RAGI2023/External_IO.git external_io/
cd ..
catkin_make
```

## Usage
- 配置文件位于[launch](https://github.com/RAGI2023/External_IO.git/blob/main/launch/io.launch)
- 话题为 `/setIO` `/setPWM`

---
[硬件购买链接](https://item.taobao.com/item.htm?id=891054360001)
