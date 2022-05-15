# Proje-2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

dizi ikiye bölünür
[16,21,11] and [8,12,22]

sol ve sağdakiler tekrar ikiye bölünür
[16] [21,11] and [8] [12,22]

tek eleman kalacak şekilde bölünür
[16] [21] [11] and [8] [12] [22]

ikili ve sıralı şekilde birleştirilir
[16,21] [11] and [8] [12,22]

sıralı şekilde ikili grup yapılır
[11,16,21] and [8,12,22]

sonuç yazılır
[8,11,12,16,21,22]

Big-O gösterimini yazınız.
O(nlogn)
