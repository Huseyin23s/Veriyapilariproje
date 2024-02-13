# Veriyapilariproje
Java eğitimi içerisindeki veri yapıları projeleri(Selection sort,merge sort,binary search tree)
# Selection/İnsertion Sort
-Soru a
```[22,27,16,2,18,6]```
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

  Adım 1: 22,27,16,2,18,6 //22 27 den küçük olduğu için değişiklik yapılmadı.
  Adım 2: 22,16,27,2,18,6 // 27 ile 16 yer değiştirildi.
  Adım 3: 16,22,27,2,18,6 // 22 ile 16 yer değiştirildi.
  Adım 4: 16,22,2,27,18,6 // 27 ile 2 yer değiştirildi.
  Adım 5: 16,2,22,27,18,6 // 22 ile 2 yer değiştirildi.
  Adım 6: 2,16,22,27,18,6 // 16 ile 2 yer değiştirildi.
  Adım 7: 2,16,22,18,27,6 // 27 ile 18 yer değiştirildi.
  Adım 8: 2,16,18,22,27,6 // 22 ile 18 yer değiştirildi.
  Adım 9: 2,16,18,22,6,27 // 27 ile 6 yer değiştirildi.
  Adım 10: 2,16,18,6,22,27 // 22 ile 6 yer değiştirildi.
  Adım 11: 2,16,6,18,22,27  // 18 ile 6 yer değiştirildi.
  Adım 12: 2,6,16,18,22,27  // 16 ile 6 yer değiştirildi.

  -Soru b
  Big o gösterimi:O(n^2)

  -Soru c
  Average case

  -Soru d
  ```[7,3,5,8,2,9,4,15,6]``` 
  Yukarıdaki dizinin Selection Sort'a göre ilk 4 adımını yazınız.

Adım1: ```[2,3,5,8,7,9,4,15,6]``` // 7 ile 2 yer değiştirdi
Adım2: ```[2,3,4,8,7,9,5,15,6]``` // 3'den daha küçük olmadığı için aynı şekilde bırakıldı. 4 ile 5 yer değiştirildi
Adım3: ```[2,3,4,5,7,9,8,15,6]``` // 5 ile 8 yer değiştirildi
Adım4: ```[2,3,4,5,6,9,8,15,7]``` // 6 ile 7 yer değiştirildi

# Merge Sort

```[16,21,11,8,12,22]```
-Soru a
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```[16,21,11,8,12,22]```
```[16,21,11][8,12,22]```
```[16][21,11][8][12,22]```
```[16][21][11][8][12][22]```
```[16][11,21][8][12,22]```
```[11,16,21][8,12,22]```
```[8,11,12,16,21,22]```
-Soru c
Big-O gösterimini:O(n logn)

# Binary Search Tree
```[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]``` 
Yukaridaki dizinin Binary-Search-Tree aşamalarını yazınız. 
           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4

Root 7 dir
