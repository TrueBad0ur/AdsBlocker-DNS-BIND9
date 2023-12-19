# AdsBlocker-DNS_BIND9
Create your own adsblocking service


Put into ```/etc/default/named```

```
# run resolvconf?
RESOLVCONF=no

# startup options for the server
OPTIONS="-u bind -4"
```

And comment in ```/etc/bind/named.conf.options```
```
listen-on-v6 { any; };
```
