
# Orange Pi Lite2 安裝和配置OpenMediaVault 

* 準備工具


系統一定要是Debian Buster

* 下載系統印像檔
  http://www.orangepi.org/downloadresources/
* 使用USB Image Tool將印像檔燒進sd卡
* ![image-20210906143902314](C:\Users\Ronald\AppData\Roaming\Typora\typora-user-images\image-20210906143902314.png)
* 更新

```sh
  sudo apt update && sudo apt -y upgrade
  sudo reboot
```

## 安裝openmediavaul

* 這個過程非常的久

```sh
wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash
```

接下來這個**很重要!!**因為openmediavaul安裝完後會將原本的網路管理工具刪掉，所以一定要先用瀏覽器連上Orange Pi Lite2 的ip去新增網路，登入帳密:
user:admin
password : openmediavault

* 進入系統裡的網路新增wifi介面卡
  ![image-20210804161431997](C:\Users\Ronald\AppData\Roaming\Typora\typora-user-images\image-20210804161431997.png)／





* 安裝插件，不然會看不到分享資料匣
  ![image-20210806100333016](C:\Users\Ronald\AppData\Roaming\Typora\typora-user-images\image-20210806100333016.png)

* 

* 設定完利用介面重開 Orange Pi Lite2

  ![image-20210804161926430](C:\Users\Ronald\AppData\Roaming\Typora\typora-user-images\image-20210804161926430.png)





