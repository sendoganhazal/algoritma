# Binary Search Tree Projesi

Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]


## Aşamalar:
1. Root 7'dir.

2. 5 değeri 7'den küçüktür, bu yüzden 7'nin soluna eklenir.

3. 1 değeri 7'den küçüktür (sola git), 5'ten de küçüktür. 5'in soluna eklenir.

4. 8 değeri 7'den büyüktür, bu yüzden 7'nin sağına eklenir.

5. 3 değeri 7'den küçüktür (sola git), 5'ten küçüktür (sola git), 1'den büyüktür. 1'in sağına eklenir.

6. 6 değeri 7'den küçüktür (sola git), 5'ten büyüktür. 5'in sağına eklenir.

7. 0 değeri 7'den küçüktür (sola git), 5'ten küçüktür (sola git), 1'den küçüktür. 1'in soluna eklenir.

8. 9 değeri 7'den büyüktür (sağa git), 8'den büyüktür. 8'in sağına eklenir.

9. 4 değeri 7'den küçüktür (sola git), 5'ten küçüktür (sola git), 1'den büyüktür (sağa git), 3'ten büyüktür. 3'ün sağına eklenir.

10. 2 değeri 7'den küçüktür (sola git), 5'ten küçüktür (sola git), 1'den büyüktür (sağa git), 3'ten küçüktür. 3'ün soluna eklenir.


## Ağaç Yapısının Görünümü

- Root: 7

- 7'nin solu: 5, sağı: 8

- 5'in solu: 1, sağı: 6

- 1'in solu: 0, sağı: 3

- 8'in solu: boş, sağı: 9

- 3'ün solu: 2, sağı: 4