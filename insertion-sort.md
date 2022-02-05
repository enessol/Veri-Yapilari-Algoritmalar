[22,27,16,2,18,6] -> Insertion Sort

-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6]   n
[2,27,16,22,18,6]   n-1
[2,6,16,22,18,27]   n-2
[2,6,16,18,22,27]   1


-Big-O gösterimini yazınız.
n + n(n-1) + (n-2) + 1
n.(n+1)/2 <!-- 1'den n'e kadar olan sayıların toplamı kadardır -->
n^2 + n/2
big-O = n^2

Average Case = 16, 18
Worst Case = 27
Best Case = 2

[2,6,16,18,22,27]
18 ortada yer aldığı için "Average Case" olarak değerlendirilir.


-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
