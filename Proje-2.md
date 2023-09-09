# Merge Sort

## Soru

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

## Cevap

1.adım: Tek eleman kalıncaya dek ortadan eşit olarak iki alt listeye ayrılır.

[16,21,11] - [8,12,22]

[16] - [21,11] - [8] - [12,22]

[16] - [21] - [11] - [8] - [12] - [22]

2.adım: Alt listeler kendi içinde sıralanarak birleştirilir.

[16] - [11,21] - [8] - [12,22]

[11,16,21] - [8,12,22]

[8,11,12,21,22]

Big-Oh gösterimi; her bölünmede dizi boyutu yarıya indiğinden (log n) ve her adımda n tane işlem yapıldığından O(n log n) olur.
