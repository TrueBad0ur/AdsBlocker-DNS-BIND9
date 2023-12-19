# AdsBlocker-DNS_BIND9
Create your own adsblocking service


Put into ```/etc/default/named```

```
# run resolvconf?
RESOLVCONF=no

# startup options for the server
OPTIONS="-u bind -4"
```
