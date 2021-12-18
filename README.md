# mcreqt2q

## Güncellemeler & Screen
```sh
apt update -y
apt upgrade -y
apt -y dist-upgrade
apt install screen
```
## Nodejs kurulum
```sh
curl -o- https://raw.githubusercontent.com/oguzhantanitmis/mcreqt2q/main/MCReqt2q.tar.gz | bash
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
