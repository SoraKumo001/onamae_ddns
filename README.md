# onamae_ddns

## usage

```bash
curl -O https://raw.githubusercontent.com/SoraKumo001/onamae_ddns/master/onamae_ddns
chmod +x onamae_ddns
./onamae_ddns -u userid -p password -d domain -h hostname [-i ip_addr]
```

## example

If ip is not specified, the global IP of the query source is specified.

```
./onamae_ddns -u 0000000 -p password -d example.com -h host
./onamae_ddns -u 0000000 -p password -d example.com -h host -i 172.16.1.1
```
