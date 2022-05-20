# [16,21,11,8,12,22] -> Merge Sort

## 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* 1. aşama: [16,21,11] - [8,12,22]          
* 2. aşama: [16,21] - [11] - [8,12] - [22] 
* 3. aşama: [16] - [21] - [11] - [8] - [12] - [22] 
* 4. aşama: [16,21] - [11] - [8,12] - [22] 
* 5. aşama: [11,21,16] - [8,12,22]    
* 6. aşama: [8,11,12,16,21,22]       


## 2. Big-O gösterimini yazınız.

* Dizi her seferinde 2 ye bölünürken "O(logn)" her adımda (n-1) kere işlem yaparak O(n-1) sıralama yapıyor.Bunun sonucunda O(nlogn)  

