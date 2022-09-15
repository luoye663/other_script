### 宝塔升降级到 7.7（适用centos）

```bash
wget http://download.bt.cn/install/update/LinuxPanel-7.7.0.zip

unzip LinuxPanel-*

cd panel

bash update.sh

cd .. && rm -f LinuxPanel-*.zip && rm -rf panel
```

### 宝塔一键开心脚本

```bash
wget -O bt_happy.sh https://proxy.zyun.vip/https://raw.githubusercontent.com/elunez/other_script/master/bt_7.7_happy/bt_happy.sh && chmod +x bt_happy.sh && ./bt_happy.sh
```

### debian 与 ubuntu 安装宝塔 7.7

```
wget -O install.sh https://proxy.zyun.vip/https://raw.githubusercontent.com/elunez/other_script/master/bt_7.7_happy/install-ubuntu_7.7.sh && bash install.sh
```

### 卸载宝塔

```
wget http://download.bt.cn/install/bt-uninstall.sh && bash bt-uninstall.sh
```
### 效果图

<img width="1259" alt="image" src="https://user-images.githubusercontent.com/42142420/190320252-4e53840f-98c8-49e0-b6a9-d9517060dadd.png">

<img width="1255" alt="image" src="https://user-images.githubusercontent.com/42142420/190320337-3b8d3de3-479c-460e-be13-0d2ca3170a90.png">
