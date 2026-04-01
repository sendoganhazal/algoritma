# Merge Sort Projesi

Dizi: [16, 21, 11, 8, 12, 22]


## Aşamalar:

### 1. Bölme (Divide) Aşaması:

Dizi ikiye bölünür: [16, 21, 11] ve [8, 12, 22]

Sol taraf tekrar bölünür: [16] ve [21, 11]

[21, 11] parçası bölünür: [21] ve [11]

Sağ taraf ([8, 12, 22]) bölünür: [8] ve [12, 22]

[12, 22] parçası bölünür: [12] ve [22]

### 2. Birleştirme (Merge) Aşaması (Sıralayarak):

[21] ve [11] karşılaştırılır, küçük olan başa gelir: [11, 21]

[16] ile [11, 21] karşılaştırılarak birleştirilir: [11, 16, 21]

Diğer tarafta [12] ve [22] karşılaştırılır: [12, 22]

[8] ile [12, 22] karşılaştırılarak birleştirilir: [8, 12, 22]

### 3. Son Birleştirme:

Elimizdeki iki sıralı grup ([11, 16, 21] ve [8, 12, 22]) eleman eleman karşılaştırılarak tek bir dizi haline getirilir:

8 ile 11 kıyaslanır -> 8

11 ile 12 kıyaslanır -> 11

12 ile 16 kıyaslanır -> 12

16 ile 22 kıyaslanır -> 16

21 ile 22 kıyaslanır -> 21

Kalan eleman eklenir -> 22

*Sonuç*: **[8, 11, 12, 16, 21, 22]**

## Big-O Gösterimi

Merge Sort, diziyi her seferinde ikiye böldüğü için derinlik $\log n$ kadar olur. 
Her seviyede tüm elemanlar ($n$) birleştirme işlemine tabi tutulduğu için karmaşıklığı her durumda aynıdır:$O(n \log n)$
Bu performans, özellikle büyük veri setlerinde Insertion Sort veya Selection Sort'un $O(n^2)$ olan performansına göre çok daha hızlı sonuç verir.

