fork自phuslu/ddns 
修改内容:
1. 修改获取外部地址的接口url为中国,防止获取的ip为vpn服务器ip的问题
2. 增加异常条件判断.防止未获取到外部ip时退出.


# ddns
```
Usage: ddns <provider> [arguments]

Examples:
        ddns aliyun --key KEY --secret SECRET --domain DOMAIN
        ddns cloudflare --email EMAIL --key KEY --domain DOMAIN
        ddns cloudxns --key KEY --secret SECRET --domain DOMAIN
        ddns digitalocean --key KEY --domain DOMAIN
        ddns dnsimple --account-id ACCOUNT_ID --key KEY --domain DOMAIN
        ddns dnspod --email EMAIL --password PASSWORD --domain DOMAIN
        ddns gandi --key KEY --domain DOMAIN
        ddns godaddy --key KEY --secret SECRET --domain DOMAIN
        ddns he --key KEY --domain DOMAIN
        ddns linode --key KEY --domain DOMAIN
        ddns namecheap --password PASSWORD --domain DOMAIN
        ddns namesilo --key KEY --domain DOMAIN
        ddns ns1 --key KEY --domain DOMAIN
        ddns qcloud --secret-id SECRET_ID --secret-key SECRET_KEY --domain DOMAIN
```
### Roadmap
- [ ] add [more...](https://github.com/Neilpang/acme.sh/tree/master/dnsapi) providers
- [ ] add post hooks
