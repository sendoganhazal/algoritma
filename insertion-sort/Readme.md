1. Insertion Sort Projesi

Dizi: [22, 27, 16, 2, 18, 6]

Insertion Sort (Ekleme Sıralaması), dizinin her elemanını kendinden önceki elemanlarla karşılaştırarak doğru konuma "yerleştirme" mantığıyla çalışır.

Aşamalar:

[22, 27, 16, 2, 18, 6]: İlk eleman (22) sıralı kabul edilir. 27'ye bakılır, 22'den büyük olduğu için yeri değişmez.

[16, 22, 27, 2, 18, 6]: 16 elemanı alınır; 27 ve 22 ile kıyaslanır. İkisinden de küçük olduğu için en başa yerleşir.

[2, 16, 22, 27, 18, 6]: 2 elemanı alınır; 27, 22 ve 16'dan küçük olduğu için en başa yerleşir.

[2, 16, 18, 22, 27, 6]: 18 elemanı alınır; 27 ve 22'den küçük, 16'dan büyük olduğu için 16 ile 22 arasına girer.

[2, 6, 16, 18, 22, 27]: 6 elemanı alınır; 2'den büyük, 16'dan küçük olduğu için uygun yere yerleştirilir ve dizi sıralanmış olur.

Big-O Gösterimi

Insertion Sort algoritmasında iç içe iki döngü yapısı olduğu için karmaşıklık şöyledir:

$O(n^2)$

Time Complexity ve 18 Sayısının Durumu

Dizi sıralandıktan sonraki hali: [2, 6, 16, 18, 22, 27]

18 sayısı, dizinin ne en başında ne de en sonundadır. Listenin orta kısmında yer aldığı için bu durum Average Case kapsamına girer.

2. Selection Sort: İlk 4 Adım

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort (Seçmeli Sıralama), her adımda dizideki en küçük elemanı bulup en baştaki elemanla yer değiştirme mantığına dayanır.

Adım: Dizideki en küçük sayı bulunur (2). 2 ile en baştaki 7 yer değiştirir.

[2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım: İkinci elemandan itibaren en küçük sayı bulunur (3). Zaten doğru yerdedir, değişiklik olmaz.

[2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım: Üçüncü elemandan itibaren en küçük sayı bulunur (4). 4 ile üçüncü sıradaki 5 yer değiştirir.

[2, 3, 4, 8, 7, 9, 5, 15, 6]

Adım: Dördüncü elemandan itibaren en küçük sayı bulunur (5). 5 ile dördüncü sıradaki 8 yer değiştirir.

[2, 3, 4, 5, 7, 9, 8, 15, 6]
