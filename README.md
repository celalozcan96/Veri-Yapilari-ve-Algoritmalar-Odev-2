[https://app.patika.dev/leathrans](https://app.patika.dev/leathrans)

# Veri-Yapilari-ve-Algoritmalar-Odev-2

   [16,21,11,8,12,22] -> Merge Sort

# 1.Soru // Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- 1. Aşama Parçalara Ayırma.
  * [16,21,11] -- [8,12,22]

- 2. Aşama Daha Küçük Parçalara Ayırma.
  * [16],[21,11] -- [8],[12,22]
  * [16],[11],[21] -- [8],[12],[22]

- 3. Aşama Parçaları Birleştirme.
  * [16,11,21] -- [8,12,22]
  * [8,11,12,16,21,22]

# 2.Soru // Big-O gösterimini yazınız.
  * 2^x=n
  * x=logn
  * O(nlogn)     
