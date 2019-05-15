使用root用户登录，运行以下命令：

wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/blob/master/all.sh
chmod +x all.sh
./all.sh 2>&1 | tee all.log

卸载方法
若已安装多个版本，则卸载时也需多次运行（每次卸载一种）

使用root用户登录，运行以下命令：

./all.sh uninstall



安装bbr

wget --no-check-certificate https://github.com/liyubaku/install/blob/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh
