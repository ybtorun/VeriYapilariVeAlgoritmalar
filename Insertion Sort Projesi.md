# [22,27,16,2,18,6] -> Insertion Sort
------------------------------------------------------------------------------------------------

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* 1. aşama:[22,27,16,2,18,6] -->n işlem
* 2. aşama:[16,22,27,2,18,6] -->n-1 işlem
* 3. aşama:[2,16,22,27,18,6] -->n-2 işlem
* 4. aşama:[2,16,18,22,27,6] -->n-3 işlem
* 5. aşama:[2,6,16,18,22,27] -->1 işlem

## 2. Big-O gösterimini yazınız.

* n + (n-1) + (n-2) + (n-3) +...+ 1 = n (n+1)/2 => O(n²)

## 3. Time Complexity: 

* Average Case: Ortadaki eleman olduğu için eleman sayısının yarısı kadar işlem olacak yani 2^x=n => x=logn => O(logn)
* Worst Case: En son da olması tüm eleman sayıları yani n kadar işlem demek => O(n)
* Best Case: iLk sayı olacağı için 0(1) olurdu.

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

[2,6,16,18,22,26] şeklinde sıralanacağı için 18 dizinin ortasında kalıyor.Dolayısyla average case e girer.

## 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı nedir?
* 1. aşama:[3,7,5,8,2,9,4,15,6]
* 2. aşama:[3,5,7,8,2,9,4,15,6]
* 3. aşama:[3,5,7,8,2,9,4,15,6]
* 4. aşama:[2,3,5,7,8,9,4,15,6]


