# 410随身WIFI升级CAN支持

1. 检查系统是否支持CAN
```
sudo modprobe can && echo "您的内核支持CAN" || echo "您的内核不支持CAN"
```

2. git clone
```
git clone https://github.com/duxlong/410wifi-can.git
```

3. 进入项目目录，安装CAN支持
```
dpkg -i linux-headers-5.18.0-msm8916mainline+_5.18.0-msm8916mainline+-10.00.Custom_arm64.deb
dpkg -i linux-image-5.18.0-msm8916mainline+_5.18.0-msm8916mainline+-10.00.Custom_arm64.deb
```
