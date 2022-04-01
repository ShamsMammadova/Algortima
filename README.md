# INSERTION-SORT PROJECT

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1.First Step

[2,27,16,22,18,6](n),[2,6,16,22,27,18](n-1),[2,6,16,18,22,27](n-3)

2.Big-O Ilk once elemanlar bir bir gezilir,her eleman siralandiginda siralanacaklar bir bir azalir ve sonuc asagidaki gibi olur:
n + n-1 +n-2 + ....+1 = n*(n-1)/2
O(n) = n^2

Big-O gösterimini yazınız.

3.Best case’de aradığımız sayı = 2 ve Big-O notation O(n)
Average case'de aradigimiz sayi=16 ve  Big-O  notation O(n^2)
Worst Case'de aradigimiz sayi=27 ve Big-O notation O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6],[2,3,4,6,7,9,5,15,8], [2,3,5,6,7,5,9,15,8],[2,3,4,5,6,7,8,9,15]


# MERGE SORT-PROJECT
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

        [16,21,11,8,12,22]
        /                 \
  [16,21,11]          [8,12,22]
    /  \                /    \
 [16,21] [11]         [8,12] [22]
  /        |           /      |
[16],[21],[11]        [8][12]  [22] 
 /          |          /      |
[16,21]    [11]       [8,12]  [22]
/                       /       
[11,16,21]            [8,12,22]
\                       /
        [8,11,12,16,21,22]
Big-O: O(nlogn)

# BINARY SEARCH TREE PROJECT
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Root:6
       6
      / \
     5   8
     /    \
     1   7 9
     /\
     0 3
      /\
      2 4
      
