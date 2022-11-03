## STEP0：ubuntu環境架設(20.04)，安裝SSH並設定連線。
## STEP1：Odoo16環境架設(使用Yenthe666的Script簡化安裝)
1. sudo wget https://raw.githubusercontent.com/Yenthe666/InstallScript/16.0/odoo_install.sh
2. sudo chmod +x odoo_install.sh
3. 調整使用nginx與註冊憑證。
   + 設定ngin，拿掉網址註冊
   + 手動使用網址註冊:sudo certbot --nginx -d www.xxx.com --noninteractive --agree-tos --email xxx@gamil.com --redirect
4. sudo ./odoo_install.sh

## STEP2: 測試環境
1. http://192.168.xxx.xxx:8069
2. 設定workers
3. 
