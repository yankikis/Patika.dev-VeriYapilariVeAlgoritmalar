# Selection Sort

## Soru

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

## Cevap

1.adım: "22" en küçük elemanı bulana kadar bütün elemanlarla karşılaştırılır. En küçük eleman "2" ile yer değiştirir.
[2,27,16,22,18,6]

2.adım: "27" aynı şekilde karşılaştırılır, "6" ile yer değiştirir.
[2,6,16,22,18,27]

3.adım: "16" karşılaştırılır, kendinden küçük eleman olmadığı için aynı kalır.
[2,6,16,22,18,27]

4.adım: "22" karşılaştırılır, "18" ile yer değiştirir.
[2,6,16,18,22,27]

5.adım: "22" karşılaştırılır, aynı kalır.
[2,6,16,18,22,27]

6.adım: "27" son eleman olduğu için karşılaştırma olmaz, sıralama biter.
[2,6,16,18,22,27]


Big-Oh gösterimi; n eleman karşılaştırması 1 eleman kalana kadar azalarak devam eder. n + (n-1) + (n-2) + ... + 1 = [n x (n-1)] / 2 => O(n^2)


Time Complexity; 18 sayısı 4. eleman olduğu için average case'e girer
