运行在本地的DNS代理服务器，内置Pcap_DNSProxy和DNSCrypt，支持配置最多10个DNS共同或按规则解析，支持SOCKS5远程DNS、TCP协议解析、非标准端口解析，在GUI上支持订阅网络HOSTS，支持通配符的自定义HOSTS功能，支持指定IP共享DNS服务器，自带添加域名规则功能，不需要担心没有人维护，默认配置使用黑名单方式对被和谐域名使用OPENDNS的5353端口进行防污染解析，其他使用114DNS解析，不影响国内网站CDN解析准确性。

能实现的功能不少，可能称为DNS管理代理服务器更适合。

下载地址：[Releases](https://github.com/miaomiaosoft/Acrylic-DNS-Proxy-GUI/releases)



Acrylic DNS Proxy：http://mayakron.altervista.org/wikibase/show.php?id=AcrylicHome

DNSCrypt：https://dnscrypt.org

OPENDNS：https://www.opendns.com

如果只想要自动化的DNS防污染功能，推荐使用：[Pcap_DNSProxy](https://github.com/chengr28/Pcap_DNSProxy)
