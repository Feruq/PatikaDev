# Insertion Sort Projesi
    
#### Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
> [22,27,16,2,18,6] -> Insertion Sort
### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

O ana kadarki sıralı kısma ‘ | ‘ koyalım.

>①   22 | 27 16 2 18 6
>②   22 27 | 16 2 18 6
>③   22 **16** 27 | 2 18 6 → **16** 22 27 | 2 18 6
>④   16 22 **2** 27 | 18 6 → 16 **2** 22 27 | 18 6 → **2** 16 22 27 | 18 6
>⑤   2 16 22 **18** 27 | 6 → 2 16 **18** 22 27 | 6
>⑥   2 16 18 22 **6** 27 | → 2 16 18 **6** 22 27 | → 2 16 **6** 18 22 27 | → 2 **6** 16 18 22 27 |
Bu şekilde sırasız bir dizi sıralı hale gelir.

### 2. Big-O gösterimini yazınız.
        O(n^2)

### 3. Time Complexity:

   > Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
     
### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
>   Average Case

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

O ana kadarki sıralı kısma ‘ | ‘ koyalım.

>Başlangıç:   7 | 3 5 8 2 9 4 15 6

# Merge Sort Projesi
    
#### Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

    (16,21,11) - (8,12,22)
    (16,21) - (11) - (8,12) - (22)
    (11,16,21) - (8,12,22)
    (8,11,16,21,22)
    
Big O Notation = O(nlogn)

# Binary Search Tree Projesi

#### Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

              7
            5   8
          1  6    9
        0  3       
         2  4
>1-Adım:      **3** 7 | 5 8 2 9 4 15 6
>2-Adım:      3 **5** 7 | 8 2 9 4 15 6
>3-Adım:      3 5 7 8 | 2 9 4 15 6
>4-Adım:      3 5 7 **2** 8 | 9 4 15 6 → 3 5 **2** 7 8 | 9 4 15 6 → 3 **2** 5 7 8 | 9 4 15 6 → **2** 3 5 7 8 | 9 4 15 6
