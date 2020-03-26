# KoolProxy
#安装命令
opkg install https://github.com/iPhone-5/KoolProxy/raw/master/luci-app-koolproxy_3.8.4-x86_64.ipk
#更新规则地址
wget https://raw.githubusercontent.com/iPhone-5/KoolProxy/master/data/source.list -O /mnt/loop0/upper/usr/share/koolproxy/data/source.list
#每日规则
wget https://shaoxia1991.coding.net/p/kp_dat/d/kp_dat/git/tree/master/daily.txt -O /overlay/upper/usr/share/koolproxy/data/rules/daily.txt
#静态规则
wget https://shaoxia1991.coding.net/p/kp_dat/d/kp_dat/git/tree/master/koolproxy.txt -O /overlay/upper/usr/share/koolproxy/data/rules/koolproxy.txt
#视频规则
wget https://shaoxia1991.coding.net/p/kp_dat/d/kp_dat/git/tree/master/kp.dat -O /overlay/upper/usr/share/koolproxy/data/rules/kp.dat
