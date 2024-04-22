# Usercloud

## 1. HK用愛發電vps ｜ HK 朋友版VPS

HK用愛發電vps-年付12u，老板没有做好准备，抢了40分钟才付款成功，网站直接干崩，顺便要说一句，**老板是台妹**！

HK用愛發電vps: **[链接](https://billing.usercloud.host/aff.php?aff=80&pid=68 "usercloud") (带aff)**

HK 朋友版VPS(年付20u): **[链接](https://billing.usercloud.host/aff.php?aff=80&pid=73 "usercloud") (带aff)**

测试机为**HK用愛發電vps**

官网配置如下:(标注为HK 朋友版VPS)

>接入 Lumen + PCCWG + Cogent + HKIX + EIEHK + RETN + NTT + TELSTRA
>【附註】當遭到DDoS攻擊時將自動切換至清洗線路
>可自定義 VPS 規格
>1 Cores vCPU
>512MB RAM
>8G SSD
>750G 流量 (Lite Route)
>10Gbps 端口速率
>**可申請 BGP Session**
>**可額外加購 IP 地址**

### 1.1 融合怪测试

```bash
--------------------- A Bench Script By spiritlhl ----------------------
                   测评频道: https://t.me/vps_reviews                    
版本：2024.03.26
更新日志：VPS融合怪测试(集百家之长)                       
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel(R) Xeon(R) CPU E5-2660 v4 @ 2.00GHz
 CPU 核心数        : 1
 CPU 频率          : 1995.372 MHz
 CPU 缓存          : L1: 64.00 KB / L2: 256.00 KB / L3: 35.00 MB
 硬盘空间          : 1.58 GiB / 7.87 GiB
 启动盘路径        : /dev/vda3
 内存              : 157.17 MiB / 437.50 MiB
 Swap              : [ no swap partition or swap file detected ]
 系统在线时间      : 0 days, 0 hour 47 min
 负载              : 0.36, 0.26, 0.10
 系统              : Debian GNU/Linux 11 (bullseye) (x86_64)
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 架构              : x86_64 (64 Bit)
 内核              : 5.10.0-20-amd64
 TCP加速方式       : cubic
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS215310 Pfcloud UG
 IPV4 位置         : Hong Kong / Hong Kong / HK
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分:          595 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:          13326.44 MB/s
 单线程写测试:          8677.64 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作               写速度                                  读速度
 100MB-4K Block         13.2 MB/s (3215 IOPS, 7.96s)            24.6 MB/s (6016 IOPS, 4.26s)
 1GB-1M Block           240 MB/s (229 IOPS, 4.36s)              711 MB/s (678 IOPS, 1.47s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 128.13 MB/s  (32.0k) | 145.57 MB/s   (2.2k)
Write      | 128.47 MB/s  (32.1k) | 146.34 MB/s   (2.2k)
Total      | 256.61 MB/s  (64.1k) | 291.91 MB/s   (4.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 116.48 MB/s    (227) | 121.31 MB/s    (118)
Write      | 122.67 MB/s    (239) | 129.39 MB/s    (126)
Total      | 239.15 MB/s    (466) | 250.70 MB/s    (244)
---------------------流媒体解锁--感谢sjlleo开源-------------------------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Youtube----------------
[IPv4]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG33S01)
Youtube识别地域: 香港(HK)
----------------Netflix----------------
[IPv4]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：台湾
[IPv6]
您的网络可能没有正常配置IPv6，或者没有IPv6网络接入
---------------DisneyPlus---------------
[IPv4]
当前IPv4出口解锁DisneyPlus
区域：香港区
解锁Youtube，Netflix，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:                                  Yes (Region: HK)
 HotStar:                               No
 Disney+:                               Yes (Region: TW)
 Netflix:                               Yes (Region: TW)
 YouTube Premium:                       Yes (Region: HK)
 Amazon Prime Video:                    Yes (Region: HK)
 TVBAnywhere+:                          No
 iQyi Oversea Region:                   TW
 Viu.com:                               Yes (Region: HK)
 YouTube CDN:                           Hong Kong 
 Netflix Preferred CDN:                 Hong Kong  
 Spotify Registration:                  No
 Steam Currency:                        HKD
 ChatGPT:                               Only Available with Mobile APP
 Bing Region:                           HK
 Instagram Licensed Audio:              No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:         【TW】
-------------------欺诈分数以及IP质量检测--本脚本原创-------------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  ① | scamalytics数据库 ②  | virustotal数据库  ③ | abuseipdb数据库 ④  | ip2location数据库   ⑤
ip-api数据库  ⑥ | ipwhois数据库     ⑦  | ipregistry数据库  ⑧ | ipdata数据库    ⑨  | ipgeolocation数据库 ⑩
ipapiis数据库 ⑪ | ipapicom数据库    ⑫  | abstractapi数据库 ⑬ | ipqualityscore数据库 ⑭ 
欺诈分数(越低越好): 0⑤  abuse得分(越低越好): 0⑤  0.0078 (Low)⑪  威胁等级: low②  
IP类型: 
  使用类型(usage_type):business①  Data Center/Web Hosting/Transit⑤  business⑧  business⑨  hosting⑪  
  公司类型(company_type):isp①  hosting⑧  business⑪  
  云服务提供商(cloud_provider):  Yes⑧ 
  数据中心(datacenter):  No⑥ ⑨ ⑪ 
  移动网络(mobile):  No⑥ ⑪ 
  代理(proxy):  No① ② ⑥ ⑦ ⑧ ⑨ ⑩ ⑪ ⑫ 
  VPN(vpn):  No① ② ⑦ ⑧ ⑪ 
  TOR(tor):  No① ② ⑦ ⑧ ⑨ ⑪ ⑫ 
  TOR出口(tor_exit):  No⑧ 
  搜索引擎机器人(search_engine_robot):② 
  匿名代理(anonymous):  No⑦ ⑧ ⑨ 
  攻击方(attacker):  No⑧ ⑨ 
  滥用者(abuser):  No⑧ ⑨ ⑪ 
  威胁(threat):  No⑧ ⑨ 
  iCloud中继(icloud_relay):  No① ⑧ ⑨ 
  未分配IP(bogon):  No⑧ ⑨ ⑪ 
Google搜索可行性：YES
端口25检测:
  本地: No
  163邮箱: Yes
  gmail邮箱: Yes
  outlook邮箱: Yes
  yandex邮箱: Yes
  qq邮箱: Yes
----------------三网回程--感谢zhanghanyun/backtrace开源-----------------
国家: HK 城市: Hong Kong 服务商: AS215310 Pfcloud UG
北京电信 219.141.136.12  测试超时
北京联通 202.106.50.1    联通4837[普通线路]           
北京移动 221.179.155.161 移动CMI [普通线路]           
上海电信 202.96.209.133  电信163 [普通线路]           
上海联通 210.22.97.1     联通4837[普通线路]           
上海移动 211.136.112.200 移动CMI [普通线路]           
广州电信 58.60.188.222   测试超时
广州联通 210.21.196.6    联通4837[普通线路]           
广州移动 120.196.165.24  移动CMI [普通线路]           
成都电信 61.139.2.69     测试超时
成都联通 119.6.6.6       联通4837[普通线路]           
成都移动 211.137.96.205  移动CMI [普通线路]           
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
3.88 ms  AS205329,AS215310  中国, 香港, allpasstravel.com
0.82 ms  *  局域网
0.56 ms  *  局域网
9.72 ms  AS174  中国, 香港, cogentco.com
8.25 ms  AS174  中国, 香港, cogentco.com
10.48 ms  AS174  中国, 香港, cogentco.com
74.09 ms  AS174  日本, 东京都, 东京, cogentco.com
187.75 ms  AS174  关岛, cogentco.com
187.96 ms  AS174  美国, 加利福尼亚州, 洛杉矶, cogentco.com
188.62 ms  AS174  美国, 加利福尼亚州, 圣何塞, cogentco.com
187.77 ms  AS174  美国, 加利福尼亚州, 圣何塞, cogentco.com
343.76 ms  AS4134  中国, 广东, 广州, chinatelecom.com.cn, 电信
343.67 ms  AS4134  中国, 广东, 深圳, chinatelecom.com.cn, 电信
357.33 ms  AS4134  中国, 广东, 深圳, chinatelecom.com.cn, 电信
广州联通 210.21.196.6
0.42 ms  AS205329,AS215310  中国, 香港, allpasstravel.com
0.88 ms  *  局域网
0.56 ms  *  局域网
157.92 ms  AS3356  美国, 加利福尼亚州, 洛杉矶, level3.com
228.71 ms  AS3356  美国, 加利福尼亚州, 洛杉矶, level3.com
261.95 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
236.30 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
242.91 ms  AS17816  中国, 广东, 广州, chinaunicom.com, 联通
273.75 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
246.75 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
广州移动 120.196.165.24
0.36 ms  AS205329,AS215310  中国, 香港, allpasstravel.com
0.61 ms  *  局域网
0.75 ms  *  局域网
2.73 ms  AS3356  中国, 香港, level3.com
3.35 ms  AS58453  中国, 香港, chinamobile.com, 移动
8.86 ms  AS58453  中国, 广东, 广州, chinamobile.com, 移动
11.23 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
11.14 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
12.71 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
13.80 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
11.98 ms  AS56040  中国, 广东, 深圳, chinamobile.com, 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置             上传速度        下载速度        延迟     丢包率
Speedtest.net    2182.35 Mbps    4038.77 Mbps    0.68     0.0%
中国香港         466.72 Mbps     271.03 Mbps     2.81     NULL
新加坡           2082.68 Mbps    983.77 Mbps     32.05    0.0%
联通海南         499.06 Mbps     284.02 Mbps     113.68   NULL
电信湖南5G       0.70 Mbps       48.97 Mbps      440.52   9.9%
移动Beijing      955.12 Mbps     425.85 Mbps     48.49    NULL
------------------------------------------------------------------------
 总共花费      : 9 分 38 秒
 时间          : Thu Apr 18 22:56:16 HKT 2024
------------------------------------------------------------------------
```

### 1.2 Youtube测试

![Youtube-HK用愛發電vps](https://github.com/tossnotes/VPSTest/assets/96852061/a5f4688a-d7e2-4e98-b87c-c5d964409328)

### 1.3 SpeedTest

* 多线程

![speedtest-HK用愛發電vps](https://github.com/tossnotes/VPSTest/assets/96852061/980ce322-3076-4ff3-9a07-b79c80d54c4a)

* 单线程

![speedtest-HK用愛發電vps-单线程](https://github.com/tossnotes/VPSTest/assets/96852061/6c981e08-1d5c-41ca-8ec9-d6ea9690e9e7)

### 1.4 哪吒探针

![nezha-HK用愛發電vps](https://github.com/tossnotes/VPSTest/assets/96852061/0f42bc1d-6112-4723-8d0a-a40caf00ad26)



## 2. China Direct 復活局

**前提条件：5.1之前卖不到50会清退**

目前使用的是上游是**100Mbps**，但5.1后会使用新的上游，升级为**500Mbps**

China Direct 復活局(年付288.92u): **[链接](https://billing.usercloud.host/aff.php?aff=80&pid=70 "usercloud") (带aff)**

* **5折折扣码**：`U8Q0YPXBR2` （最终为：年付144.5u）

China Direct 復活局(月付19.97u): **[链接](https://billing.usercloud.host/aff.php?aff=80&pid=71 "usercloud") (带aff)**



测试机为 **100Mbps** China Direct 復活局



官网配置如下:

> 使用HK Lite國際出口線路
> 經由CTGNET + CU 10099 + CMI接入中國核心網路
> VPS 規格
>
> > 1 Core vCPU
> > 1GB RAM
> > 20G SSD
> > 1TB 流量 (China Direct Route)*
> 500Mbps 端口速率
> 可額外加購 IP 地址
>
> 
>
> ** 此 500Mbps 須基於公平使用原則來使用，詳情請參閱【知識庫 > Fair Use Resources】
>  加購額外 IP 地址需另外開單
>
> 
>
> 【註】如有特殊規格需求，請另外開單
> 當訂單成立後，即代表您已詳閱 【知識庫 > 服務條款】 與 【知識庫 > 退款條款】
> 1/5前賣不到50台全退

### 1. 融合怪测试

```bash
--------------------- A Bench Script By spiritlhl ----------------------
                   测评频道: https://t.me/vps_reviews                    
版本：2024.04.21
更新日志：VPS融合怪测试(集百家之长)                       
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : Intel(R) Xeon(R) CPU E5-2660 v4 @ 2.00GHz
 CPU 核心数        : 1
 CPU 频率          : 1995.372 MHz
 CPU 缓存          : L1: 32.00 KB / L2: 256.00 KB / L3: 35.00 MB
 硬盘空间          : 3.66 GiB / 15.82 GiB
 启动盘路径        : /dev/vda3
 内存              : 305.36 MiB / 925.86 MiB
 Swap              : [ no swap partition or swap file detected ]
 系统在线时间      : 16 days, 0 hour 49 min
 负载              : 0.18, 0.07, 0.02
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ✔ Enabled
 架构              : x86_64 (64 Bit)
 内核              : 6.1.0-18-amd64
 TCP加速方式       : bbr
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS215310 Pfcloud UG
 IPV4 位置         : Hong Kong / Hong Kong / HK
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分:          570 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:          12520.56 MB/s
 单线程写测试:          9361.55 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作               写速度                                  读速度
 100MB-4K Block         7.4 MB/s (1814 IOPS, 14.11s)            15.2 MB/s (3709 IOPS, 6.90s)
 1GB-1M Block           302 MB/s (288 IOPS, 3.47s)              691 MB/s (659 IOPS, 1.52s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 68.14 MB/s   (17.0k) | 185.34 MB/s   (2.8k)
Write      | 68.33 MB/s   (17.0k) | 186.32 MB/s   (2.9k)
Total      | 136.48 MB/s  (34.1k) | 371.67 MB/s   (5.8k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 149.08 MB/s    (291) | 225.85 MB/s    (220)
Write      | 157.00 MB/s    (306) | 240.90 MB/s    (235)
Total      | 306.08 MB/s    (597) | 466.75 MB/s    (455)
---------------------流媒体解锁--感谢sjlleo开源-------------------------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Youtube----------------
[IPv4]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG12S20)
Youtube识别地域: 香港(HK)
----------------Netflix----------------
[IPv4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：香港
[IPv6]
您的网络可能没有正常配置IPv6，或者没有IPv6网络接入
---------------DisneyPlus---------------
[IPv4]
当前IPv4出口解锁DisneyPlus
区域：香港区
解锁Youtube，Netflix，DisneyPlus上面和下面进行比较，不同之处自行判断
----------------流媒体解锁--感谢RegionRestrictionCheck开源--------------
 以下为IPV4网络测试，若无IPV4网络则无输出
============[ Multination ]============
 Dazn:                                  Yes (Region: HK)
 HotStar:                               No
 Disney+:                               No
 Netflix:                               Originals Only
 YouTube Premium:                       Yes (Region: HK)
 Amazon Prime Video:                    Yes (Region: HK)
 TVBAnywhere+:                          No
 iQyi Oversea Region:                   HK
 Viu.com:                               Yes (Region: HK)
 YouTube CDN:                           Hong Kong 
 Netflix Preferred CDN:                 Hong Kong  
 Spotify Registration:                  Yes (Region: HK)
 Steam Currency:                        HKD
 ChatGPT:                               Only Available with Mobile APP
 Bing Region:                           HK
 Instagram Licensed Audio:              No
=======================================
 以下为IPV6网络测试，若无IPV6网络则无输出
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:         【TW】
-------------------欺诈分数以及IP质量检测--本脚本原创-------------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  ① | scamalytics数据库 ②  | virustotal数据库  ③ | abuseipdb数据库 ④  | ip2location数据库   ⑤
ip-api数据库  ⑥ | ipwhois数据库     ⑦  | ipregistry数据库  ⑧ | ipdata数据库    ⑨  | ipgeolocation数据库 ⑩
ipapiis数据库 ⑪ | ipapicom数据库    ⑫  | abstractapi数据库 ⑬ | ipqualityscore数据库 ⑭ 
欺诈分数(越低越好): 0⑤  abuse得分(越低越好): 0⑤  0 (Very Low)⑪  威胁等级: low②  
IP类型: 
  使用类型(usage_type):business①  Data Center/Web Hosting/Transit⑤  business⑧  business⑨  hosting⑪  
  公司类型(company_type):hosting①  hosting⑧  business⑪  
  云服务提供商(cloud_provider):  Yes⑧ 
  数据中心(datacenter):  No⑥ ⑨   Yes⑪ 
  移动网络(mobile):  No⑥ ⑪ 
  代理(proxy):  No① ② ⑥ ⑦ ⑧ ⑨ ⑩ ⑪ ⑫ 
  VPN(vpn):  No① ② ⑦ ⑧ ⑪ 
  TOR(tor):  No① ② ⑦ ⑧ ⑨ ⑪ ⑫ 
  TOR出口(tor_exit):  No⑧ 
  搜索引擎机器人(search_engine_robot):② 
  匿名代理(anonymous):  No⑦ ⑧ ⑨ 
  攻击方(attacker):  No⑧ ⑨ 
  滥用者(abuser):  No⑧ ⑨ ⑪ 
  威胁(threat):  No⑧ ⑨ 
  iCloud中继(icloud_relay):  No① ⑧ ⑨ 
  未分配IP(bogon):  No⑧ ⑨ ⑪ 
Google搜索可行性：YES
----------------三网回程--感谢zhanghanyun/backtrace开源-----------------
国家: HK 城市: Hong Kong 服务商: AS215310 Pfcloud UG
北京电信 219.141.136.12  电信CN2 [优质线路]           
北京联通 202.106.50.1    联通4837[普通线路]           
北京移动 221.179.155.161 移动CMI [普通线路]           
上海电信 202.96.209.133  电信CN2 [优质线路]           
上海联通 210.22.97.1     联通4837[普通线路]           
上海移动 211.136.112.200 移动CMI [普通线路]           
广州电信 58.60.188.222   电信CN2 [优质线路]           
广州联通 210.21.196.6    联通4837[普通线路]           
广州移动 120.196.165.24  移动CMI [普通线路]           
成都电信 61.139.2.69     电信CN2 [优质线路]           
成都联通 119.6.6.6       联通4837[普通线路]           
成都移动 211.137.96.205  移动CMI [普通线路]           
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
1.01 ms  AS151188,AS215310  中国, 香港, simple.taipei
0.61 ms  *  局域网
1.00 ms  *  局域网
0.87 ms  *  美国, ibm.com
2.14 ms  AS24429  中国, 香港, aliyun.com, 阿里云
0.78 ms  *  中国, 香港, chinatelecom.com.cn, 电信
8.23 ms  *  中国, 广东, 广州, chinatelecom.com.cn, 电信
12.39 ms  *  中国, 广东, 广州, chinatelecom.com.cn, 电信
13.09 ms  *  中国, 广东, 深圳, chinatelecom.com.cn, 电信
11.76 ms  AS4134  中国, 广东, 深圳, chinatelecom.com.cn, 电信
广州联通 210.21.196.6
0.38 ms  AS151188,AS215310  中国, 香港, simple.taipei
0.43 ms  *  局域网
0.59 ms  *  局域网
0.71 ms  *  美国, ibm.com
1.62 ms  AS24429  中国, 香港, aliyun.com, 阿里云
1.55 ms  AS10099  中国, 香港, chinaunicom.com, 联通
4.50 ms  AS10099  中国, 香港, chinaunicom.com, 联通
2.31 ms  AS10099  中国, 香港, chinaunicom.com, 联通
10.66 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
8.04 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
13.47 ms  AS17816  中国, 广东, 深圳, chinaunicom.com, 联通
18.15 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
11.21 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
广州移动 120.196.165.24
0.39 ms  AS151188,AS215310  中国, 香港, simple.taipei
17.17 ms  *  局域网
18.75 ms  *  局域网
5.11 ms  *  美国, ibm.com
9.07 ms  AS58453  中国, 香港, chinamobile.com, 移动
1.98 ms  AS58453  中国, 香港, chinamobile.com, 移动
7.61 ms  AS58453  中国, 广东, 广州, chinamobile.com, 移动
7.47 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
7.40 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
9.16 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
11.33 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
11.13 ms  AS56040  中国, 广东, 深圳, chinamobile.com, 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置             上传速度        下载速度        延迟     丢包率
Speedtest.net    498.31 Mbps     399.59 Mbps     0.76     0.0%
新加坡           506.08 Mbps     434.97 Mbps     30.93    0.0%
联通海南         83.35 Mbps      78.36 Mbps      22.61    NULL
联通上海5G       33.27 Mbps      47.95 Mbps      30.54    0.0%
电信浙江         83.67 Mbps      84.83 Mbps      31.49    NULL
电信合肥5G       42.79 Mbps      40.05 Mbps      48.69    0.0%
移动杭州5G       87.36 Mbps      85.85 Mbps      35.75    14.6%
移动Beijing      78.57 Mbps      88.41 Mbps      49.41    NULL
------------------------------------------------------------------------
 总共花费      : 7 分 24 秒
 时间          : Mon Apr 22 20:11:38 HKT 2024
------------------------------------------------------------------------
```

### 2. Youtube测试

![Youtube-China_Direct_復活局](https://github.com/tossnotes/VPSTest/assets/96852061/e029587f-b8fa-44d8-843a-7d379feef5cc)

### 3. SpeedTest

* 多线程

![speedtest-China_Direct_復活局](https://github.com/tossnotes/VPSTest/assets/96852061/037605c8-2fac-4b01-a674-88e380916e56)

* 单线程

![speedtest-China_Direct_復活局](https://github.com/tossnotes/VPSTest/assets/96852061/10f7e690-e489-4f89-b973-28e1f881e182)

### 4. 哪吒探针

![nezha-China_Direct_復活局](https://github.com/tossnotes/VPSTest/assets/96852061/8f04e60d-ff24-4d8e-bd62-bb71da889ea1)

**更新时间**：2024-04-22 20:30
