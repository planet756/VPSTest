Misaka HK S3P2-1C1G 21刀/月

S3P2-1C1G | HK: **[链接](https://app.misaka.io/iaas/vm/create/hkg12/s3p2-1c1g "Misaka S3P2")**

官网配置:
>1 vCPU
>1 GB RAM
>16 GB SSD
>716 GB Transfer 单向流量计算

### 1. 融合怪测评

```bash
--------------------- A Bench Script By spiritlhl ----------------------
                   测评频道: https://t.me/vps_reviews                    
版本：2024.04.21
更新日志：VPS融合怪测试(集百家之长)                       
---------------------基础信息查询--感谢所有开源项目---------------------
 CPU 型号          : AMD EPYC-Milan Processor
 CPU 核心数        : 1
 CPU 频率          : 2645.028 MHz
 CPU 缓存          : L1: 32.00 KB / L2: 512.00 KB / L3: 32.00 MB
 硬盘空间          : 1.78 GiB / 14.94 GiB
 启动盘路径        : /dev/vda1
 内存              : 196.25 MiB / 943.39 MiB
 Swap              : [ no swap partition or swap file detected ]
 系统在线时间      : 4 days, 6 hour 9 min
 负载              : 0.15, 0.04, 0.01
 系统              : Debian GNU/Linux 12 (bookworm) (x86_64)
 AES-NI指令集      : ✔ Enabled
 VM-x/AMD-V支持    : ❌ Disabled
 架构              : x86_64 (64 Bit)
 内核              : 6.1.0-18-amd64
 TCP加速方式       : bbr
 虚拟化架构        : KVM
 NAT类型           : Full Cone
 IPV4 ASN          : AS23961 Misaka Network, Inc.
 IPV4 位置         : Hong Kong / Hong Kong / HK
 IPV6 ASN          : AS23961 Misaka Network
 IPV6 位置         : Hong Kong
 IPV6 子网掩码     : 64
----------------------CPU测试--通过sysbench测试-------------------------
 -> CPU 测试中 (Fast Mode, 1-Pass @ 5sec)
 1 线程测试(单核)得分:          3824 Scores
---------------------内存测试--感谢lemonbench开源-----------------------
 -> 内存测试 Test (Fast Mode, 1-Pass @ 5sec)
 单线程读测试:          43627.01 MB/s
 单线程写测试:          23488.52 MB/s
------------------磁盘dd读写测试--感谢lemonbench开源--------------------
 -> 磁盘IO测试中 (4K Block/1M Block, Direct Mode)
 测试操作               写速度                                  读速度
 100MB-4K Block         88.2 MB/s (21.53 IOPS, 1.19s))          132 MB/s (32173 IOPS, 0.80s)
 1GB-1M Block           1.4 GB/s (1359 IOPS, 0.74s)             1.5 GB/s (1448 IOPS, 0.69s)
---------------------磁盘fio读写测试--感谢yabs开源----------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 269.79 MB/s  (67.4k) | 2.41 GB/s    (37.6k)
Write      | 270.50 MB/s  (67.6k) | 2.42 GB/s    (37.8k)
Total      | 540.29 MB/s (135.0k) | 4.83 GB/s    (75.5k)
           |                      |                     
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ---- 
Read       | 2.98 GB/s     (5.8k) | 2.87 GB/s     (2.8k)
Write      | 3.14 GB/s     (6.1k) | 3.07 GB/s     (2.9k)
Total      | 6.13 GB/s    (11.9k) | 5.94 GB/s     (5.8k)
---------------------流媒体解锁--感谢sjlleo开源-------------------------
以下测试的解锁地区是准确的，但是不是完整解锁的判断可能有误，这方面仅作参考使用
----------------Youtube----------------
[IPv4]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG12S20)
Youtube识别地域: 香港(HK)
[IPv6]
连接方式: Youtube Video Server
视频缓存节点地域: 中国香港(HKG07S42)
Youtube识别地域: 香港(HK)
----------------Netflix----------------
[IPv4]
您的出口IP可以使用Netflix，但仅可看Netflix自制剧
NF所识别的IP地域信息：香港
[IPv6]
您的出口IP完整解锁Netflix，支持非自制剧的观看
NF所识别的IP地域信息：香港
---------------DisneyPlus---------------
[IPv4]
当前IPv4出口解锁DisneyPlus
区域：香港区
[IPv6]
当前IPv6出口解锁DisneyPlus
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
============[ Multination ]============
 Dazn:                                  Failed (Network Connection)
 HotStar:                               No
 Disney+:                               Yes (Region: HK)
 Netflix:                               Yes (Region: HK)
 YouTube Premium:                       Yes (Region: HK)
 Amazon Prime Video:                    Unsupported
 TVBAnywhere+:                          Failed (Network Connection)
 iQyi Oversea Region:                   Failed
 Viu.com:                               Failed
 YouTube CDN:                           Hong Kong 
 Netflix Preferred CDN:                 Hong Kong  
 Spotify Registration:                  Yes (Region: HK)
 Steam Currency:                        Failed (Network Connection)
 ChatGPT:                               Failed
 Bing Region:                           HK
 Instagram Licensed Audio:              No
=======================================
---------------TikTok解锁--感谢lmc999的源脚本及fscarmen PR--------------
 Tiktok Region:         Failed
-------------------欺诈分数以及IP质量检测--本脚本原创-------------------
数据仅作参考，不代表100%准确，如果和实际情况不一致请手动查询多个数据库比对
以下为各数据库编号，输出结果后将自带数据库来源对应的编号
ipinfo数据库  ① | scamalytics数据库 ②  | virustotal数据库  ③ | abuseipdb数据库 ④  | ip2location数据库   ⑤
ip-api数据库  ⑥ | ipwhois数据库     ⑦  | ipregistry数据库  ⑧ | ipdata数据库    ⑨  | ipgeolocation数据库 ⑩
ipapiis数据库 ⑪ | ipapicom数据库    ⑫  | abstractapi数据库 ⑬ | ipqualityscore数据库 ⑭ 
欺诈分数(越低越好): 0⑤  abuse得分(越低越好): 0⑤  0 (Very Low)⑪  威胁等级: low②  
IP类型: 
  使用类型(usage_type):hosting①  Data Center/Web Hosting/Transit⑤  hosting⑧  business⑨  isp⑪  
  公司类型(company_type):hosting①  business⑧  isp⑪  
  云服务提供商(cloud_provider):  Yes⑧ 
  数据中心(datacenter):  No⑥ ⑨   Yes⑪ 
  移动网络(mobile):  No⑥ ⑪ 
  代理(proxy):  No① ②   Yes⑥ ⑦ ⑧ ⑨ ⑪ ⑫ 
  VPN(vpn):  No① ②   Yes⑦ ⑧ ⑪ 
  TOR(tor):  No① ② ⑦ ⑧ ⑨ ⑪ ⑫ 
  TOR出口(tor_exit):  No⑧ 
  搜索引擎机器人(search_engine_robot):② 
  匿名代理(anonymous):  Yes⑦ ⑧   No⑨ 
  攻击方(attacker):  No⑧ ⑨ 
  滥用者(abuser):  No⑧ ⑨ ⑪ 
  威胁(threat):  No⑧ ⑨ 
  iCloud中继(icloud_relay):  No① ⑧ ⑨ 
  未分配IP(bogon):  No⑧ ⑨ ⑪ 
Google搜索可行性：YES
------以下为IPV6检测------
欺诈分数(越低越好): 0②  abuse得分(越低越好): 0⑤  0 (Very Low)⑪  威胁等级: low②  
IP类型: Data Center/Web Hosting/Transit⑤  isp⑪
----------------三网回程--感谢zhanghanyun/backtrace开源-----------------
国家: HK 城市: Hong Kong 服务商: AS23961 Misaka Network, Inc.
北京电信 219.141.136.12  移动CMI [普通线路]           
北京联通 202.106.50.1    移动CMI [普通线路]           
北京移动 221.179.155.161 移动CMI [普通线路]           
上海电信 202.96.209.133  移动CMI [普通线路]           
上海联通 210.22.97.1     移动CMI [普通线路]           
上海移动 211.136.112.200 移动CMI [普通线路]           
广州电信 58.60.188.222   移动CMI [普通线路]           
广州联通 210.21.196.6    移动CMI [普通线路]           
广州移动 120.196.165.24  移动CMI [普通线路]           
成都电信 61.139.2.69     移动CMI [普通线路]           
成都联通 119.6.6.6       移动CMI [普通线路]           
成都移动 211.137.96.205  移动CMI [普通线路]           
---------------------回程路由--感谢fscarmen开源及PR---------------------
依次测试电信/联通/移动经过的地区及线路，核心程序来自ipip.net或nexttrace，请知悉!
广州电信 58.60.188.222
0.42 ms  AS57695  中国, 香港, misaka.io
8.68 ms  AS969  中国, 香港, misaka.io
1.45 ms  AS58453  中国, 香港, chinamobile.com, 移动
28.45 ms  AS58453  中国, 上海, chinamobile.com, 移动
29.91 ms  AS9808  中国, 上海, chinamobile.com, 移动
29.96 ms  AS9808  中国, 上海, chinamobile.com, 移动
47.35 ms  AS4134  中国, 广东, 深圳, chinatelecom.com.cn, 电信
39.12 ms  AS4134  中国, 广东, 深圳, chinatelecom.com.cn, 电信
广州联通 210.21.196.6
0.16 ms  AS57695  中国, 香港, misaka.io
0.73 ms  AS969  中国, 香港, misaka.io
3.83 ms  AS58453  中国, 香港, chinamobile.com, 移动
26.75 ms  AS58453  中国, 上海, chinamobile.com, 移动
28.79 ms  AS9808  中国, 上海, chinamobile.com, 移动
34.66 ms  AS9808  中国, 上海, chinamobile.com, 移动
40.78 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
33.65 ms  AS4837  中国, 广东, 广州, chinaunicom.com, 联通
38.83 ms  AS17816  中国, 广东, 深圳, chinaunicom.com, 联通
39.61 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
37.13 ms  AS17623  中国, 广东, 深圳, chinaunicom.com, 联通
广州移动 120.196.165.24
0.13 ms  AS57695  中国, 香港, misaka.io
0.61 ms  AS969  中国, 香港, misaka.io
6.88 ms  AS58453  中国, 广东, 广州, chinamobile.com, 移动
6.31 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
6.45 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
9.33 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
12.06 ms  AS9808  中国, 广东, 广州, chinamobile.com, 移动
11.14 ms  AS56040  中国, 广东, 深圳, chinamobile.com, 移动
--------------------自动更新测速节点列表--本脚本原创--------------------
位置             上传速度        下载速度        延迟     丢包率
Speedtest.net    9829.06 Mbps    10130.46 Mbps   0.23     0.0%
中国香港         9557.54 Mbps    5281.96 Mbps    0.40     0.0%
新加坡           4.74 Mbps       3500.67 Mbps    31.72    0.0%
联通上海5G       64.58 Mbps      63.78 Mbps      35.83    0.0%
联通WuXi         963.34 Mbps     902.67 Mbps     42.01    0.0%
电信浙江         963.50 Mbps     2326.05 Mbps    42.33    NULL
电信浙江         957.50 Mbps     2864.81 Mbps    40.63    NULL
移动Beijing      78.03 Mbps      703.02 Mbps     47.49    14.0%
------------------------------------------------------------------------
 总共花费      : 6 分 8 秒
 时间          : Tue Apr 30 10:50:00 UTC 2024
------------------------------------------------------------------------
```

### 2. Youtube测试

![ytb-misaka-hk-S3P2-1C1G](https://github.com/tossnotes/VPSTest/assets/96852061/151c4750-eee0-427a-9862-154a20886c68)


### 3. Speedtest

* 多线程

![speedtest-misaka-hk-S3P2-1C1G-多线程](https://github.com/tossnotes/VPSTest/assets/96852061/cbadec02-7587-40ae-9951-dfc33df735e5)

* 单线程

![speedtest-misaka-hk-S3P2-1C1G-单线程](https://github.com/tossnotes/VPSTest/assets/96852061/f4b733aa-5edd-482b-9a3a-3811bf841121)

### 4. 哪吒监控

![nezha-misaka-hk-S3P2-1C1G](https://github.com/tossnotes/VPSTest/assets/96852061/057da7f8-05a7-4d2b-b3bf-bf60df2e65c2)


