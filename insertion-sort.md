# Insertion Sort Proje 1

[22,27,16,2,18,6] -> Insertion Sort

## Yukarı verilen dizinin sort türüne göre aşamalarını yazınız ?

 * 1 - ilk aşama [22,27,16,2,18,6] -> (n)
 * 2- [2,27,16,22,18,6] -> (n - 1) -> 22 ile 2 yer değiştiriyor.
 * 3- [2,6,16,22,18,27] -> (n - 2) -> 27 ile 6 yer değiştiriyor.
 * 4- [2,6,16,18,22,27] -> (1) -> 22 ile 18 yer değiştiriyor.

## Big-0 gösterimini yazınız ?

* Sayı öbeği => 6 dır.
* n*(n-1) / 2 ile toplamını bulurız.
* Toplamı = 21
* Big-0 bulmak içinde n^2 olarak bakıcaz 6^2 = 36'dır.

## Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

* **Time Complexity :** Average Case:Arağımız sayının ortada olması, Wort Case:Arağımız sayımız sayının sonda olması, Best Case:Arağımız sayının dizinin en başta olması.
*  İstenilen case 18 sayısı -> Ortada olduğu için **Average Case'dir**



# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı yazınız ?

* 1-) [7,3,5,8,2,9,4,15,6] -> 1 adım
* 2-) [2,3,5,8,7,9,4,15,6] -> 7 ile 2 yer değiştirdi.
* 3-) [2,3,4,8,7,9,5,15,6] -> 4 ile 5 yer değiştirdi.
* 4-) [2,3,4,5,7,9,8,15,6] -> 8 ile 6 yer değiştirdi.


