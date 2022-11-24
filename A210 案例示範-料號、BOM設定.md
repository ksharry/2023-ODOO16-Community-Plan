## 案例-料號、BOM設定
#### 虛擬示範設定
1. 環境網址 - https://runbot.xienci.com/
   + 帳號密碼:admin/admin
2. 電動床架-製造業
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2101.png?raw=true)
2. 電動床架(C001)
   + 床框-自製(B001) * 1 
     + 鐵架(A001) * 4 購買價 1000
   + 貼布床板-委外(B002) * 1  委外費:100
     + 床板(A002) * 4 購買價 1000
   + 電動馬達(A003) * 2  購買價 1000
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2108.png?raw=true)
3. 產品類別設定
   + 製成品
   + 半成品-需手動新增科目
   + 原料
4. 產品明細:
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2105.png?raw=true)
5. BOM表明細:
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2106.png?raw=true)
6. 其他說明:
   + 好的編碼帶你上天堂，產品編碼-odoo16有管控不能重複
   + 設定-製造-委外功能開啟
   + 善用複製功能
   + 可設定供應商-後續採購可以示範功能
   + 路線部分設定原則
     + 原料-購買
     + 半成品與製成品-製造
7. 料號與BOM表的關聯圖
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2104.png?raw=true)
   + mrp_bom
     + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2102.png?raw=true)
   + mrp_bom_line
     + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2107.png?raw=true)
