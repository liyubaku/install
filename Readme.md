使用root用户登录，运行以下命令：

yum install -y wget && wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/raw/master/shadowsocks-all.sh && chmod +x shadowsocks-all.sh && ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

卸载方法
若已安装多个版本，则卸载时也需多次运行（每次卸载一种）
使用root用户登录，运行以下命令：

./shadowsocks-all.sh uninstall

如提示没有wget，则先安装wget

yum -y install wget


