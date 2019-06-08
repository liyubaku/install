使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/raw/master/shadowsocks-all.sh && chmod +x shadowsocks-all.sh && ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

如提示没有wget，则先安装wget

yum -y install wget


