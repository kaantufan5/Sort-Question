# Sorting (Sıralama) Algoritmaları

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


# Çözüm: 

## 1. Insertion Sort:

1. Aşama: 22,27,16,2,18,6 
2. Aşama: 16,22,27,2,18,6
3. Aşama: 2,16,22,27,18,6
4. Aşama: 2,16,18,22,27,6
5. Aşama: 2,6,16,18,22,27

- Big-O: O(n^2)

18 sayısı = Avarage Case

## 2. Selection Sort:


1. Aşama: 2,7,3,5,8,9,4,15,6
2. Aşama: 2,3,7,5,8,9,4,15,6
3. Aşama: 2,3,4,7,5,8,9,15,6
4. Aşama: 2,3,4,5,7,8,9,15,6
