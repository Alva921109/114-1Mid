# 第2次隨堂題目-隨堂-QZ2
>
>學號：112111133   (學號和姓名都要寫)
><br />
>姓名：林凱翎
>



請在撰寫"說明程式與內容"該塊內容，請把原該塊內上述敘述刪除，該塊上述內容只是用來指引該怎麼撰寫內容。

1. a.

Ans: 
![alt text](image-1.png)
說明:
//取得低庫存商品清單
//商品陣列，每個元素包含 { name, stock }
//name = 項目, stock = 庫存 
//宣告名為getLowStock的函式
function getLowStock(products) {
 //宣告一個新的陣列
 const lowStockItems = products
 //篩選出少於10的商品
 .filter(item => item.stock<10)
 //取出名稱name('mouse', 'monitor')
 .map(item => item.name);
 //顯示結果到終端機
 console.log("庫存少於10的商品", lowStockItems);
}
//執行結果
getLowStock(products);



1. b.

Ans:

<!-- 請撰寫時，最後一句話再寫一次 -->


1. c.

Ans:

<!--  請撰寫時，第一句話再寫一次  -->

2. a.

Ans:

<!--  請撰寫時，第一句話再寫一次  -->

2. b.

Ans:

<!--  請撰寫時，第一句話再寫一次  -->

2. c.

Ans:

<!--  請撰寫時，第一句話和最後一句再寫一次  -->

2. d.

Ans:


