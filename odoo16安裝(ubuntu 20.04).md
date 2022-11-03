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
3. 設定MasterPassword
4. 重新啟動
5. 註冊網址

## STEP3: 結論
1. 建議使用ubuntu進行正式機的設置
2. 要學習看一下腳本內容

## 後續影片
1. 後續影片為odoo16的各模組教學，會區分顧問與開發進行
   + 顧問-ERP相關教學與建議使用第三方模組
     + 如何安裝台灣模組與第三方模組
     + 銷售
     + 採購
     + 庫存
     + 製造
     + 財務
   + 開發-第二階段
     + 如何使用win11安裝odoo16環境
     + 如何使用pycharm環境進行開發
     + 如何使用git進行共同開發

## 錯誤排除訊息
1. sudo apt-get install postgresql postgresql-server-dev-all -y
2. systemctl status postgresql.service
3. sudo su - postgres -c "createuser -s  odoo" 2> /dev/null || true
4. sudo -u postgres psql
5. SELECT rolname FROM pg_roles;
