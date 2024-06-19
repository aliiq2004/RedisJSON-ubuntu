# RedisJSON to ubuntu 24.04




## Install & Build

```bash
sudo apt update
sudo apt install wget
sudo apt install unzip
wget https://huggingface.co/alikwiq/test/resolve/main/RedisJSON%20ubuntu.zip
unzip "RedisJSON ubuntu.zip" -d "RedisJSON-ubuntu"
cd "RedisJSON-ubuntu"
chmod -R 777 .
sudo ./sbin/setup
```

after done run this command
```bash
sudo ./deps/readies/bin/getredis
```

## Run
```bash
make run
```
## note
# this mode edit by alikwiq

telegram username is:- https://alikwiq.t.me
