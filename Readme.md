使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/blob/master/shadowsocks-all.sh 
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

安装bbr

wget --no-check-certificate https://github.com/liyubaku/install/blob/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh
