使用root用户登录，运行以下命令：

yum install -y wget && wget --no-check-certificate -O shadowsocks-all.sh https://github.com/liyubaku/install/raw/master/shadowsocks-all.sh && chmod +x shadowsocks-all.sh && ./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

安装 simple-obfs , 选择 http 模式

一键安装原版BBR

wget --no-check-certificate https://github.com/liyubaku/install/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh

卸载方法
若已安装多个版本，则卸载时也需多次运行（每次卸载一种）
使用root用户登录，运行以下命令：

./shadowsocks-all.sh uninstall


如提示没有wget，则先安装wget

yum -y install wget

- [Win SS客户端下载地址](https://github.com/shadowsocks/shadowsocks-windows/releases)
- [SS obfs-local插件下载地址](https://github.com/shadowsocks/simple-obfs/releases)

#### 本地配置

服务器端已将安装了 obfs, 本地端直接下载obfs-local插件, 解压后**将插件 obfs-local 与Shdowsocks.exe 同一路径下**即可.


obfs可以直接在SS的服务器编辑页面修改参数

插件选项为 **obfs=http;obfs-host=www.bing.com**, 实际上可以将 www.bing.com 更换为任意的一个网址, 只要不是被GFW封杀的就可以, 推荐像腾讯视频, 优酷, bing这种流量较大的网站

### iOS

iOS上推荐的客户端为 Shadowrocket 
支持 http 与 tls 两种模式

#### Shadowrocket

shadowrocket在服务器的编辑页面中即可设置混淆

### Android

#### Shadowsocks

推荐在Google Play上下载Shadowsocks app, 同时下载obfs插件, 开发者均为 Max Lv. 

也可以前往 [Shadowsocks-Android](https://github.com/shadowsocks/shadowsocks-android/releases) 的 GitHub 仓库下载。




