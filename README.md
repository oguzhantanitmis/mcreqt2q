# mcreqt2q

## Güncellemeler
```sh
apt update -y
apt upgrade -y
apt-get -y dist-upgrade
```
## Nodejs kurulum
```sh
curl -o- https://raw.githubusercontent.com/oguzhantanitmis/mcreqt2q/main/oguzhan-onemli.sh?token=AKJ35AHLPQFNEZ5A6HYRKQDBXX5JI | bash
```
```sh
source ~/.bashrc
```
```sh
nvm install v14.10.0
nvm install lts/fermium
nvm use v14.10.0
```

## Kernel ayarı
```sh
sysctl -w kernel.pid_max=999999
```

## Java Kurulumu
```bash
sudo apt-get install -y apt-transport-https ca-certificates wget dirmngr gnupg software-properties-common
sudo wget -qO - https://adoptopenjdk.jfrog.io/adoptopenjdk/api/gpg/key/public | sudo apt-key add -
sudo add-apt-repository --yes https://adoptopenjdk.jfrog.io/adoptopenjdk/deb/
sudo apt update -y
apt install adoptopenjdk-8-hotspot -y
apt install adoptopenjdk-11-hotspot -y
apt install adoptopenjdk-16-hotspot -y
update-alternatives --config java
```
