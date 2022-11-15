## DBFILTER規劃應用實作-影片
#### Xienci網站規劃
1. consultant.xienci.com：課程教材
2. runbot.xienci.com：開放課程環境

#### 執行步驟
1. 建立兩個資料庫
   + consultant
   + runbot
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/C1301.png?raw=true)
2. pchome設定增加網域。
3. 移除Cerbot跟Nginx
4. 註冊子網域網址:
   + sudo certbot --nginx -d consultant.xienci.com -d runbot.xienci.com --noninteractive --agree-tos --email harry.chang@dahsheng.com --redirect
3. sudo vi /etc/odoo-server.conf
   + 增加dbfilter = ^%d$
   + 相關說明網址參考:[網址1](https://richsoda.com/blog/odoo-1/post/hostname-14)，[網址2](https://trobz.com/blog/odoo-4/post/all-you-need-to-know-about-db-filtering-in-odoo-16)
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/C1302.png?raw=true)

#### 移除cerbot憑證(指令參考)
1. sudo certbot delete --cert-name xienci.com

#### 移除Nginx步驟(指令參考)
1. sudo apt-get --purge remove nginx
2. sudo apt-get autoremove
3. sudo apt-get --purge remove nginx
4. sudo apt-get --purge remove nginx-common

#### 使用情境
1. 顧問區規劃(consultant.xienci.com)
   + Xienci活動
   + ODOO教學文章
2. 開放區規劃(runbot.xienci.com)
   + 讓學員可以有環境使用
   + 實際操作環境
   + 及時查看設定與第三方模組

