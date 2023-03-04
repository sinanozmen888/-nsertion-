Insertion Selection
22<27, 22 yerinde kaldı.
[22,27,16,2,18,6]
22>16, 16 22'nin soluna gelir.

[22,16,27,2,18,6]
[16,22,27,2,18,6]
16>2, 2 16' nın soluna gelir.
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]

2<18, 16<18, 22>18, 18 22' nin soluna gelir.
[2,16,22,18,27,6]
[2,16,18,22,27,6]
2<6, 16>6, 6 16' nın soluna gelir.
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]

Dizimizi küçükten büyüğe doğru sıralamış olduk.
Dizi sıralandıktan sonra 18 sayısı ortada olduğu için 1. duruma girer yani avarage case.

Selection Sort
[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
