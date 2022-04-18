# China DNS Forwarding Rules for dnscrypt-proxy

> 数据来源：https://gitee.com/felixonmars/dnsmasq-china-list

用于 [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy/) ，具体使用方法详见 [dnscrypt-proxy > Wiki > Forwarding](https://github.com/DNSCrypt/dnscrypt-proxy/wiki/Forwarding)

DNS为 `阿里DNS` 及 `腾讯DNS` 

数据说明：

```
 data
 ├── ipv4                                        IPv4 DNS
 │   ├── accelerated-domains.china.txt          一般域名
 │   ├── google.china.txt                       Google 在中国可以解析的域名
 │   ├── apple.china.txt                        Apple 在中国可以解析的域名
 │   └── all.txt                                以上所有数据
 │
 ├── ipv6                                        IPv6 DNS
 │   └── ...
 │
 ├── ipv4_ipv6                                   IPv4 + IPv6 混合DNS
 │   └── ... 
 │
 └── raw                                         只有域名数据
      └── ...
```
