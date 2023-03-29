# patikadevMergeSort

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Merge Sort
büyük inputlar için elimdeki sayı dizisini daha küçük parçalara ayırıp sıralamak olur.
tek bir eleman kalana kadar böleceğiz sonra birleştirme aşamasına geçilir.
sıralayarak hepsini birleştiririz.
yapacağım sorgu sayısı n-1 olur.
nlogn

[16, 21, 11, 8, 12, 22]

[16, 21, 11] [8, 12, 22] -> Diziyi iki eşit boyutta alt dizilere böl

[16] [21, 11] [8] [12, 22] -> Dizileri sırala

[16] [11, 21] [8] [12, 22] -> İki alt diziyi birleştir

[11, 16, 21] [8, 12, 22] -> Tüm diziyi sırala

[8, 11, 12, 16, 21, 22] -> Sonuç

