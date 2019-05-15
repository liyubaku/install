使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/raw/master/shadowsocks-all.sh && chmod +x shadowsocks-all.sh && ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log


安装bbr

wget --no-check-certificate https://github.com/liyubaku/install/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh

测速（中文）
wget -N —no-check-certificate https://github.com/liyubaku/install/raw/master/ZBench-CN.sh && bash ZBench-CN.sh

测速（英文）
wget -N —no-check-certificate https://github.com/liyubaku/install/raw/master/ZBench.sh && bash ZBench.sh
