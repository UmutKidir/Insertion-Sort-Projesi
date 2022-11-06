# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması,  Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

# Çözüm

1. Problem

1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]

2. Problem

* İlk sorguda n adet işlem yapılır. 
* Sonrasında bir sayının yeri bulunduğundan n-1 adet işlem yapılır ve bu her adımda bir azalır. 

* Bunun sonucunda ise toplam işlem sayısı şu şekilde hesaplanır: n + (n-1) + (n-2) + (n-3) +..... 1. 
* Bu gösterim ise ardışık sayıların toplamıdır ve şu şekilde gösterilir: (n * (n+1))/2 yani (n^2+n)/2  
* Burada baskın olan n^2 olduğundan da Big-O Notation n^2 olur ve şöyle gösterilir: O(n^2)

3. Problem
 
* Average case: en küçük sayıyı ararken değiştirdiğimiz sayıların doğru yerlere denk gelmesi
* Best case: dizinin sıralı gelmesi
* Worst case: dizinin karmaşık olup n^2 işlemde düzenlenmesi.

4. Problem

* 18 Avarage case'e girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# Çözüm

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
