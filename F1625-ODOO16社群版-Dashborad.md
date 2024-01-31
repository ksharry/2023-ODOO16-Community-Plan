ODOO15以前的儀表板功能都是透過報表的加入儀表板，才會有相關的報表資料，在ODOO16版本大幅度更新，已有固定的模板外，原新增的功能仍可保留，今天就來說明16版的銷售的模板進行介紹，並且加入第三方模組，製作屬於個案公司的CRM儀表板~

## Dashborad

不同模組的模板內容強調的數字不同，銷售模組的模板內容如下參考:

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788SVp9plNjPs.png)

### 新的儀表板可以篩選與連動

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788XlfQ4fTCLp.png)

- 點選admin進行篩選

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788cQypk7XO7Z.png)

- 系統僅呈現admin這個客戶的相關資料

此連動方式可以很方便的查看關於這個客戶的相關資料。

### 社群版是否可以自己進行儀表板製作。

答案是可以的，透過第三方模組的安裝，就可以跟企業版類似的功能可以進行設定:

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788CvzWPo2SOp.png)

資料來源:

[OCA/spreadsheet](https://github.com/OCA/spreadsheet)

透過安裝這兩個模組，我們就可以透過樞紐分析表製作相關報表。

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788BaKaaNoYmC.png)

資料來源:

[Introduction to the new Odoo 16 dashboards](https://www.youtube.com/watch?v=KOSlYfhC9Rk)

我們同樣透過社群版來製作看看:

### 1. 透過CRM報表新增柱狀圖

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788ydHwG3kZRV.png)

### 2. 透過CRM報表新增樞紐表

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788SAYKkVvzvI.png)

### 3. 整理KPI數據

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788fWEevLgaeu.png)

### 4. 調整版面

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788z39e6XZ6UI.png)

### 5. 查看結果

![Alt text](https://ithelp.ithome.com.tw/upload/images/20230919/20161788Ryeg4QCBEM.png)

## 小結

當ODOO16推出儀表版功能時，就非常吸引人想要使用，因此當OCA推出可以自行設定，透過幾個KPI的設定，就可以製作個案公司專屬的管理儀表板，而且只要USER會使用GOOGLE SHEET，也可以自行製作想要的報表格式，製作完成就同步發佈出去，有樞紐也有視覺化，此功能讓系統報表的彈性大幅提升，真的是非常感謝社群的貢獻。
