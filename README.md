# Sui Node Kurulumu

İlk önce sudoyu kuralım
```
sudo apt install
```
Sonrasında screen'i yükleyelim

```
apt install screen
```

Şimdi de bir screen oluşturalım

```
screen -S sui

Artık full node'umuzu yükleyebiliriz

```
wget -O sui.sh https://raw.githubusercontent.com/kj89/testnet_manuals/main/sui/sui.sh && chmod +x sui.sh && ./sui.sh

Bu işlem biraz zaman alabilir


