# trivialproxy
A simple proxy server in nodejs

Usage:

``` sh
npm i -g trivialproxy

# for http proxy server
tp -p 8080 -h localhost

# for https proxy server
tp -p 443 -h somehost.in -prot https --key-path key.pem --cert-path cert.pem

# for https proxy server and http request
tp -p 443 -h somehost.in -prot https --key-path key.pem --cert-path cert.pem --https-req
```
