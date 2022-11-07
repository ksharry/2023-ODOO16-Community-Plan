## ODOO介面與設定介紹-影片
#### ODOO介面介紹 
1. tree view
2. form view
3. 智慧面板
4. 其他-動作(報表、複製、歸檔)
5. 匯入
6. 欄位的搜尋、分組
7. 檔案的轉出
8. 報表的調整

#### ODOO小猴子
1. chrome apps -[網址](https://chrome.google.com/webstore/category/extensions?hl=zh-TW)
2. 搜尋odoo debug
3. 安裝使用，或在網址上加上(web?debug=1)
4. 

#### odoo第三方模組安裝
1. 範例模組:odoomate推出的會計模組-[網址](https://apps.odoo.com/apps/modules/16.0/om_account_accountant/)
2. 透過winscp上傳到使用者目錄/git
   + sudo cp -a /home/dsc/git/* /odoo/custom/addons/.
   + sudo chown -R odoo: /odoo/custom/addons
   + sudo chmod 755 -R /odoo/custom/addons
   + sudo service odoo-server stop/start
   + 如果上面有問題看一下ps aux | grep 'odoo'

#### ODOO設定介紹
1. 感謝社群貢獻，已預設台灣設定模組。
   + 台灣會計模組-[網址](https://apps.odoo.com/apps/modules/14.0/l10n_tw_standard_ifrss/)
   + WINSCP安裝(暫不需要)
2. 各模組設定檢查
   + 公司:資訊維護
   + 庫存:開啟倉庫路線的設定
   + 會計:群組/搜尋"會計"，加入使用者
   + 
3. 


