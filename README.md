# surge rule-set sample
```
[Rule]
RULE-SET,https://github.com/congcong0806/surge-list/raw/master/congcong.list,Proxy
RULE-SET,https://github.com/scomper/surge-list/raw/master/apple.list,Proxy
RULE-SET,https://github.com/scomper/surge-list/raw/master/adblock.list,REJECT
RULE-SET,https://github.com/scomper/surge-list/raw/master/reject-gif.list,REJECT-TINYGIF
RULE-SET,https://github.com/scomper/surge-list/raw/master/reject.list,REJECT
RULE-SET,https://github.com/scomper/surge-list/raw/master/cn.list,nProxy
RULE-SET,https://github.com/scomper/surge-list/raw/master/blocked.list,Proxy
RULE-SET,https://github.com/scomper/surge-list/raw/master/netflix.list,Proxy
RULE-SET,LAN,DIRECT

GEOIP,CN,DIRECT
FINAL,Proxy,dns-failed
