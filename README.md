## RUN NODE

Install default node software
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
copy perintah
```
source...../.bashrc
```
Inisialisasi node
```
gaianet init
```
Start Node
```
gaianet start
```
Buka Link yg muncul terminal anda, contoh 
```
... ... https://0xf63939431ee11267f4855a166e11cc44d24960c0.us.gaianet.network
```
Cek Node id
```
gaianet info
```
Cek addres,keystore,pasparse ( simpan )
```
nano gaianet/nodeid.json
```

## Bot Auto Chat

Install Scren
```
sudo apt install screen
```
Masuk ke Screnn
```
screen -Rd gaia
```
Install Npm
```
apt install npm
```
Clone Repo
```
https://github.com/yogik23/GaiaNet-bot
```
Masuk ke Folder Gaian
```
cd gaian
```
Buat File nano & edit UbahNodeID ke Node ID kalian
```
nano gaian.js
```
Install
```
npm i
```
Jalankan bot
```
node gaian.js
```

Keluar dari screen
```
ctrl + a + d
```
Masuk Screen
```
screen -S gaia
```

Done
