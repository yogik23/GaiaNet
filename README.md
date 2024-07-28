# GaiaNet BetaLaunch
Claim your GAIA Profile Verified Role \
https://www.gaianet.ai \
-Connect Metamask wallet \
-Go to profil \
-Bind email,twitter,discord & telegram \
-Claim Role galxe \
https://app.galxe.com/quest/Gaianet/GCML9tgKrT



## RUN NODE



* Install default node software
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
* Buat CLI gaianet tersedia di shell
```
source /root/.bashrc atau source /administrator/.bashrc
```
* Inisialisasi node
```
gaianet init
```
* Start Node
```
gaianet start
```
* Buka Link yg muncul terminal anda, contoh \
```... ... https://0xf63939431ee11267f4855a166e11cc44d24960c0.us.gaianet.network``` 

* Cek Node id
```
gaianet info
```
* Cek addres,keystore,pasparse ( simpan )
```
nano gaianet/nodeid.json
```
* Perintah stop Node
```
gaianet stop
```



# Verif Node
https://www.gaianet.ai/node \
-Click Add Node \
-Submit Node ID \
-Device ID \
-Check node status \
-Join The Network Of GaiaNet \
-interaction with bot \
-Claim your Early Node Verified Role \
https://app.galxe.com/quest/Gaianet/GCMz9tgKnG 



## Bot Auto Chat gunakan vps yg berbeda

* Install Tmux 
```
apt install tmux
```
* Buat Sesi baru gaianet
```
tmux new-session -s gaianet
```
* Install Npm
```
apt install npm
```
* Clone Repo
```
git clone https://github.com/gilkur23/gaia
```
* Masuk ke Folder Gaian
```
cd gaia
```
* Buka File nano & edit NodeIdGaiaMu ke Node ID kalian
```
nano gaian.js
```
* Save File
```
ctrl x y
```
* Install
```
npm i
```
* Jalankan bot
```
node gaian.js
```

* Keluar dari sesi tmux ```ctrl-b + d``` 
* Masuk sesi tmux
```
tmux attach-session -t gaianet
```
Done
