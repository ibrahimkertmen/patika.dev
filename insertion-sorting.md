Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
insertion sort'a göre en küçük eleman bulunur ve en başa getirilir. en baştaki eleman en küçük elamanın yerine geçer. sıralama bu şekilde devam eder.
1. adım
[2,27,16,22,18,6] (n-1)
en küçük eleman 2. 2 en başa getirilir, en baştaki eleman 2'nin yerine yazılır.
2. adım
[2,6,16,22,18,27] (n-2)
2'den sonra en küçük eleman 2. sıraya yazılır(6). 2. sıradaki eleman 6'nın yerşne yazılır.
3.adım
[2,6,16,18,22,27] (n-3)
sıralama kontrol edilir. ilk 3 eleman sıralı fakat sonra sıralama bozuluyor. 16'dan sonra en küçük eleman bulunur(18), 4.sıraya yazılır. 4.sıradaki eleman 18'in yerine geçer.
Dizi bu haliyle sıralı olduğundan 3.adımda sıralama tamamlanmış olur.
son durum: [2,6,16,18,22,27]


2.Big-O gösterimini yazınız.
n + (n-1) + (n-2) + ... + 1 = n*(n+1)/2 = n^2 + n/2
bu durumda Big-O göserimi O(n^2) olur.


3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Wors case: [27,22,18,16,6,2] - O(n^2)
Best case: [2,6,16,18,22,27] - O(n)
Average case: [2,6,16,18,22,27] - O(n^2)


4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı avegage case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1.adım: [2,3,5,8,7,9,4,15,6] 
2.adım: [2,3,4,8,7,9,5,15,6]
3.adım: [2,3,4,5,7,9,8,15,6]
4.adım: [2,3,4,5,6,9,8,15,7]

*****

www.patika.dev