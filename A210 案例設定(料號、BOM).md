## 案例設定(料號、BOM)
#### 虛擬案例設定
1. 電動床架-製造業
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2101.png?raw=true)
2. 電動床架(C001)- 查看成本
   + 床框-自製(B001) * 1 
     + 鐵架(A001) * 4 購買價 1000
   + 貼布床板-委外(B002) * 1  委外費:100
     + 床板(A002) * 4 購買價 1000
   + 電動馬達(A003) * 2  購買價 1000
3. 產品類別設定
   + 製成品
   + 半成品-需手動新增科目
   + 原料
4. 料號與BOM表的關聯圖
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2104.png?raw=true)
   + mrp_bom
     + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2102.png?raw=true)
   + mrp_bom_line
     + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2103.png?raw=true)
5. 產品編碼-odoo16有管控不能重複
6. 路線部分設定原則
   + 原料-購買
   + 半成品與製成品-製造
7. 善用複製功能
8. 可設定供應商-後續採購可以示範功能
9. 產品明細:
   + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2105.png?raw=true)
10. BOM表明細:
    + ![Alt text](https://github.com/ksharry/odoo-repository/blob/main/pic/A2106.png?raw=true)
