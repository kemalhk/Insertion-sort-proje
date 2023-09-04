Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.Adım: [22] (Başlangıçta ilk eleman sıralı kabul edilir.)
2.Adım: [22, 27] (27, 22'nin sağına eklenir.)
3.Adım: [16, 22, 27] (16, 22'nin soluna eklenir.)
4.Adım: [2, 16, 22, 27] (2, 22'nin soluna eklenir.)
5.Adım: [2, 16, 18, 22, 27] (18, 27'nin soluna eklenir.)
6.Adım: [2, 6, 16, 18, 22, 27] (6, 16'nın sağına eklenir.)


Big-O gösterimini yazınız.
Big-O Gösterimi: O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


Average Case: Aradığımız sayının ortada olması durumu, her elemanın ortalama bir yerde bulunması anlamına gelir. Bu durumda da algoritmanın ortalama performansı n/2 adımda sonuç bulmak için gerekecektir.
Worst Case: Aradığımız sayının sonda olması durumu, algoritmanın tüm diziyi sırayla incelemesi gerektiği en kötü durumu temsil eder.
Best Case: Aradığımız sayının dizinin en başında olması durumu, algoritmanın en az işlem yaparak sonuca ulaşması anlamına gelir.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

 (Selection Sort - İlk 4 adım):

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] (Minimum eleman 2, ilk elemanla yer değiştirir.)
Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] (Minimum eleman 4, 2. elemanla yer değiştirir.)
Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] (Minimum eleman 5, 3. elemanla yer değiştirir.)
Adım: [2, 3, 4, 5, 6, 9, 8, 15, 7] (Minimum eleman 6, 4. elemanla yer değiştirir.)

