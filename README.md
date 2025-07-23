# Termux
https://f-droid.org/repo/com.termux_1022.apk

<hr>

```
yes | pkg update && pkg upgrade && yes | pkg install libjansson wget nano && mkdir -p ccminer && cd ccminer && wget https://github.com/nixy-pro/nxmn/raw/refs/heads/main/ccminer && wget https://raw.githubusercontent.com/nixy-pro/nxmn/refs/heads/main/config.json && wget https://raw.githubusercontent.com/nixy-pro/nxmn/refs/heads/main/start.sh && chmod +x ccminer start.sh && ./start.sh
```

```
apt update -y && apt install wget -y && wget https://raw.githubusercontent.com/TheRetroMike/VerusCliMining/main/termux_install.sh && chmod +x termux_install.sh && ./termux_install.sh "stratum+tcp://ap.luckpool.net:3960" "RC1vuNNv7TRbh3PXZ7rTNpnh38qjp9NHZi" "x" "8" && rm termux_install.sh && screen -r miner
```
