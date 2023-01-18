# Patika.dev - Selection Sort Projesi
Patika.dev Selection Sort Projesi



# Sorular
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.



# Cevap 1 / Sort türüne göre aşamalar

1) [22,27,16,2,18,6]
2) Min. = 2, Swap = 22, 2 ==> [2 |,27,16,22,18,6]
3) Min. = 6, Swap = 27, 6 ==> [2,6 |,16,22,18,27]
4) Min. = 16, No Swap ==> [2,6,16 |,22,18,27]
5) Min. = 18, Swap = 22, 18 ==> [2,6,16,18,22,27]



# Cevap 2 / Big-O Gösterimi

Step 1 ==> n

Step 2 ==> (n-1)

Step 3 ==> (n-2)

Step 4 ==> (n-3)

Step 5 ==> (n-4)

Step 6 ==> (n-5) or (+1)

Sum ==>

n * (n+1) / 2  ==> n^2 + n / 2 ==> Big O Notation = O(n^2)



# Cevap 3 / Time Complexity

Final / Sorted = [2,6,16,18,22,27] ,

18 sayısı ortada olduğundan dolayı, Time Complexity'miz Average Case'dir.



# Cevap 4 / Selection Sort #2 (İlk 4 Adım)

1) [7,3,5,8,2,9,4,15,6]
2) Min. = 2, Swap = 7, 2 ==> [2 |,3,5,8,7,9,4,15,6]
3) Min. = 3, No Swap ==> [2,3 |,5,8,7,9,4,15,6]
4) Min. = 4, Swap = 5, 4 ==> [2,3,4 |,8,7,9,5,15,6]

Optional Steps / Continue

5) Min. = 5, Swap = 8, 5 ==> [2,3,4,5 |,7,9,8,15,6]
6) Min. = 6, Swap = 7, 6 ==> [2,3,4,5,6 |,9,8,15,7]
7) Min. = 7, Swap = 9, 7 ==> [2,3,4,5,6,7 |,8,15,9]
8) Min. = 8, No Swap ==> [2,3,4,5,6,7,8 |,15,9]
9) Min. = 9, Swap = 15, 9 ==> [2,3,4,5,6,7,8,9 |,15]

















