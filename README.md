> 本仓库通过 [ad-filters-subscriber](https://github.com/fordes123/ad-filters-subscriber/) 构建
## 使用说明
| 文件              | 说明                          |        github        |         ghproxy          |         jsdelivr          |
|-----------------|:----------------------------|:--------------------:|:------------------------:|:-------------------------:|
| `easylist.txt`  | 完整主规则                       | [link][easylist-raw] | [link][easylist-ghproxy] | [link][easylist-jsdelivr] |
| `modify.txt`    | 不含 DNS 过滤规则的 `easylist.txt` |  [link][modify-raw]  |  [link][modify-ghproxy]  |  [link][modify-jsdelivr]  |
| `dns.txt`       | 仅含 DNS 过滤规则的 `easylist.txt` |   [link][dns-raw]    |   [link][dns-ghproxy]    |   [link][dns-jsdelivr]    |
| `dnsmasq.conf`  | dnsmasq 及其衍生版本              | [link][dnsmasq-raw]  | [link][dnsmasq-ghproxy]  | [link][dnsmasq-jsdelivr]  |
| `clash.yaml`    | clash 及其衍生版本                |  [link][clash-raw]   |  [link][clash-ghproxy]   |  [link][clash-jsdelivr]   |
| `smartdns.conf` | smartdns                    | [link][smartdns-raw] | [link][smartdns-ghproxy] | [link][smartdns-jsdelivr] |
| `hosts`         | 几乎所有操作系统原生支持                |  [link][hosts-raw]   |  [link][hosts-ghproxy]   |  [link][hosts-jsdelivr]   |
| `private.txt`   | 本仓库维护的私有规则，以 easylist 形式提供  | [link][private-raw]  | [link][private-ghproxy]  | [link][private-jsdelivr]  |

[easylist-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/easylist.txt

[easylist-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/easylist.txt

[easylist-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/easylist.txt

[modify-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/modify.txt

[modify-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/modify.txt

[modify-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/modify.txt

[dns-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/dns.txt

[dns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/dns.txt

[dns-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/dns.txt

[dnsmasq-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/dnsmasq.conf

[dnsmasq-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/dnsmasq.conf

[dnsmasq-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/dnsmasq.conf

[clash-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/clash.yaml

[clash-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/clash.yaml

[clash-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/clash.yaml

[smartdns-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/smartdns.conf

[smartdns-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/smartdns.conf

[smartdns-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/smartdns.conf

[hosts-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/hosts

[hosts-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/hosts

[hosts-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/hosts

[private-raw]: https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/private.txt

[private-ghproxy]: https://ghproxy.net/https://raw.githubusercontent.com/Seameee/adblock_list/refs/heads/release/private.txt

[private-jsdelivr]: https://gcore.jsdelivr.net/gh/Seameee/adblock_list@refs/heads/release/private.txt
## 上游规则列表
| **序号** | **规则名称**                                  | **类型**    | **规则地址**                                                                                          |
|----------|----------------------------------------------|-------------|-----------------------------------------------------------------------------------------------------|
| 1        | AdGuard 防跟踪保护过滤器                     | easylist    | [link](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt) |
| 2        | AdGuard URL跟踪过滤器                        | easylist    | [link](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt) |
| 3        | AdGuard 恼人广告过滤器                       | easylist    | [link](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt) |
| 4        | AdGuard 解除搜索广告和自我推销过滤器         | easylist    | [link](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt) |
| 5        | xndeye web-ad-rule                           | easylist    | [link](https://raw.githubusercontent.com/Seameee/web-ad-rule/master/easylist.txt) |
| 6        | 217heidai rule                              | -           | [link](https://raw.githubusercontent.com/217heidai/adblockfilters/main/rules/adblockdns.txt) |
| 7        | d3Host List by d3ward                        | hosts       | [link](https://raw.githubusercontent.com/d3ward/toolz/master/src/d3host.txt) |
| 8        | crazy-max/WindowsSpyBlocker                                | hosts       | [link](https://cdn.jsdelivr.net/gh/crazy-max/WindowsSpyBlocker@master/data/hosts/spy.txt) |
| 9       | 大圣净化                                     | hosts       | [link](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts) |
| 10       | 8680/GOODBYEADS 补充规则                     | -           | [link](https://raw.githubusercontent.com/8680/GOODBYEADS/refs/heads/master/data/mod/adblock.txt) |
