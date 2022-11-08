## DBFILTER規劃應用實作-影片
#### Xienci網站規劃
1. consultant.xienci.com：顧問與技術課程規劃與經驗分享(主要)
2. runbot.xienci.com：開放課程環境1(主要)

#### 執行步驟
1. 建立兩個資料庫
   + consultant
   + runbot
2. pchome設定增加網域。
3. 註冊子網域網址:
   + sudo certbot --nginx -d consultant.xienci.com --noninteractive --agree-tos --email harry.chang@dahsheng.com --redirect
   + sudo certbot --nginx -d runbot.xienci.com --noninteractive --agree-tos --email harry.chang@dahsheng.com --redirect
3. sudo vi /etc/odoo-server.conf
   + 增加dbfilter = ^%d$
   + 相關說明網址參考:[網址1](https://richsoda.com/blog/odoo-1/post/hostname-14)，[網址2](https://trobz.com/blog/odoo-4/post/all-you-need-to-know-about-db-filtering-in-odoo-16)

#### 使用情境
1. 顧問區網站規劃(consultant.xienci.com)
   + Xienci活動
   + ODOO文章
2. 開放區域規劃(透明化)
   + 讓學員可以有環境使用
   + 看得到顧問的設定

