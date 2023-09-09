# Binary-Search-Tree

## Soru

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## Cevap

Dizinin ilk elemanı "7" root olarak seçilir. Daha sonra insert edilecek elemanlar root düğümünden küçükse sağa, büyükse sol tarafa yazılır.

Burada ikinci eleman "5" sağ tarafa yazılır.
```
7
 \
  5
``` 
Sıradaki eleman "1" sırayla küçük, küçük olacağı için en sağa yazılır.
```
7
  \
   5
     \
      1
```
"8" elemanı "7" nin soluna yazılır.
```
  7
 /  \
8    5
       \
        1
```
sırayla her eleman kontrol edilir.
```
    7
   /  \
  8    5
 /    /  \
9   6     1
         /  \
        3    0
       /  \
      4    2
```
