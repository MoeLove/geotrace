geotrace是根据mtr（my trace route）的报告内容结合whois来直观显示traceroute过程中经过的路由跳数、ip、平均延迟、运营商、地理位置信息等内容，在做机房选址的时候会给带来极大的帮助，报告内容一目了然。

### 运行系统：Linux/Mac OS

### 依赖程序：mtr, Python

### 使用方法:

首先确保依赖程序正常;

```
wget https://raw.githubusercontent.com/MoeLove/geotrace/master/geotrace.sh
wget https://raw.githubusercontent.com/MoeLove/geotrace/master/query_ip_geo.py

chmod +x geotrace.sh

./geotrace.sh ip/domain
```
