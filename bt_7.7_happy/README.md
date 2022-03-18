### 宝塔升降级到 7.7

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