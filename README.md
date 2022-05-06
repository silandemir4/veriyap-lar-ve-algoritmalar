# veriyap-lar-ve-algoritmalar

## **Proje 1**

**[22,27,16,2,18,6]** >>İnsert Sort

**1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

**1.Cevap:**
Algoritma her defasında en baştan başlayarak dizideki en küçük elemanı bulur ve her bir adımda başa getirir.

- 1. ADIM: | 2 | 27 | 16 | 22 | 18 | 6 |
- 2. ADIM: | 2 | 6 | 16 | 22 | 18 | 27 |
- 3. ADIM: | 2 | 6 | 16 | 18 | 22 | 27 |

**2. Big-O gösterimini yazınız.**

**2.CEVAP:**

- O(n^2)

**3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**

**3.Cevap:**

- Worst case: Aradığımız sayının sonda olması,
  Tam ters verilmiş dizi, bu durumda dizinin her bir elemanı bir gerisindekinden küçük olacaktır. Dolayısıyla 1inci eleman için iç döngü 0 2 eleman için geriye doğru 1, 3. eleman için iki daha sonra 3 4 5 6… n kadar geriye hareket yapacaktır. Yani 0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2

- Average case: Aranan sayının ortada olması durumu
  Worst case ve best casein ortalaması alındığında n^2 olarak bulunur.

- Best case: Aranan sayının dizinin en başında olması. n

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   **4.CEVAP:**

- ortada bir say olduğundan avarage case.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- 1. ADIM: | 7 | 3 | 5 | 8 | 2 | 9 | 4 |
- 2. ADIM: | 2 | 3 | 5 | 8 | 7 | 9 | 4 |
- 3. ADIM: | 2 | 3 | 4 | 8 | 7 | 9 | 5 |
- 4. ADIM: | 2 | 3 | 4 | 5 | 7 | 9 | 8 |
