# InsertionSortProjesi

Insertion Sort Projesi
Proje 1

İSTENENLER

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

1.	Average case: Aradığımız sayının ortada olması
2.	Worst case: Aradığımız sayının sonda olması
3.	Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

YANITLAR

[22,27,16,2,18,6] ….. Insertion Sort

1. [22, 27, 16, 2, 18, 6] ------ 27 doğru yerde, 22’den büyük.
2. [16, 22, 27, 2, 18, 6] ------ 16, 27 ve 22'nin önüne yerleşir.
3. [2, 16, 22, 27, 18, 6] ------- 2, en başa gelir.
4. [2, 16, 18, 22, 27, 6] ------- 18, 22 ve 27’nin önüne yerleşir.
5. [2, 6, 16, 18, 22, 27] ------- 6, 2’nin arkasına yerleşir.
Son Hali: [2, 6, 16, 18, 22, 27]

Insertion Sort Big-O Gösterimi:

-Best Case: O(n) → Dizi zaten sıralıysa

-Average Case: O(n²)

-Worst Case: O(n²) → Dizi tamamen ters sıradaysa

*Dizi sıralandıktan sonra 18 sayısı, ortada olduğu için “average case” kapsamına girer.

[7, 3, 5, 8, 2, 9, 4, 15, 6] …… Selection Sort ilk 4 adım
1. Min. eleman 2 → [2, 3, 5, 8, 7, 9, 4, 15, 6] --------- 2 ile 7 yer değiştirdi.
2. Min. eleman 3 (zaten yerinde) → [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. Min. eleman 4 → [2, 3, 4, 8, 7, 9, 5, 15, 6] --------- 4 ile 5 yer değiştirdi.
4. Min. eleman 5 → [2, 3, 4, 5, 7, 9, 8, 15, 6] --------- 5 ile 8 yer değiştirdi.
