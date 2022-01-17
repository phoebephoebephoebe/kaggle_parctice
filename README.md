# Shopee Code League - Logistics
Task: 偵測包裹是否延誤

第一次送貨不成功，會進行第二次送貨

第二次送貨不能超過3天

時間格式：UTC + 8

工作日：Monday ~ Saturday

Day 0 = Day of Pickup ;   Day 1 = Next Day after Pickup

公定假日：    
      2020-03-08  /  2020-03-25  /  2020-03-30  / 2020-03-31
    
SLA:
|                |  Metro Manila  |      Luzon     |     Visayas    |    Mindanao    |
| -------------- | -------------- | -------------- | -------------- | -------------- |
|  Metro Manila  | 3 working days | 5 working days | 7 working days | 7 working days |
|      Luzon     | 5 working days | 5 working days | 7 working days | 7 working days |
|     Visayas    | 7 working days | 7 working days | 7 working days | 7 working days |
|    Mindanao    | 7 working days | 7 working days | 7 working days | 7 working days |

Steps:
1. 算出第一次及第二次運貨時間
2. 算出每個地點的標準送貨時間
3. 比較出是否有延誤


https://www.kaggle.com/c/open-shopee-code-league-logistic
