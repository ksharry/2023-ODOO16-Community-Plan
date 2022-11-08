## odoo16安裝-[影片](https://www.youtube.com/watch?v=Uskr6rm0P9Y&t=2s)
#### Xienci網站規劃
1. consultant.xienci.com：顧問課程規劃與經驗分享
2. technical.xienci.com：技術課程規劃與經驗分享
3. runbut1.xienci.com：開放課程環境1
4. runbot2.xienci.com：開放課程環境2

#### 執行步驟
1. 建立四個資料庫
   + consultant
   + technical
   + runbut1
   + runbot2
2. 移除niginx重新安裝
   + 
3. sudo vi /etc/odoo-server.conf
   + 增加dbfilter = ^%d$
   + 相關說明網址參考:[網址1](https://richsoda.com/blog/odoo-1/post/hostname-14)，[網址2](https://trobz.com/blog/odoo-4/post/all-you-need-to-know-about-db-filtering-in-odoo-16)



