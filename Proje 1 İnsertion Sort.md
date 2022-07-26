# Proje 1
### (22,27,16,2,18,6)->İnsertion Sort
### Yukarıdaki verilen dizinin sort türüne göre aşamalarını yazınız.
Verilen örüntüye ait en küçük elemanı bulunuyor ve en baştaki sayı ile yer değiştiriyor.

İlk sayımızdan bahsettiğimiz için (22) kendi başına sıralıdır.Hiçbir işlem yapmadan devam eder.
|1.adım|22|27|16|2|18|6|
|------|-|-|-|-|-|-|

22 ile 27 kıyaslanır. 22 küçük olduğu için hiçbir değişiklik yapılmaz.
|2.adım|22|27|16|2|18|6|
|------|-|-|-|-|-|-|

16 ile 27 kıyaslanır. 16 küçük olduğu için 16 ile 27 yer değiştirir.Sonra 16 ile 22 kıyaslanır. 16 küçük olduğu için 16 ile 22 yer değiştirir.

|3.adım|22|16|27|2|18|6|-->|16|22|27|2|18|6|
|------|-|-|-|-|-|-|----|-|-|-|-|-|-|

2 ile 27 kıyaslanır. 2 küçük olduğu için 2 ile 27 yer değiştirir.Sonra 2 ile 22 kıyaslanır. 2 küçük olduğu için 2 ile 22 yer değiştirir.Daha sonra tekrar 2 ile 16 kıyaslanır. 2 küçük olduğu için 2 ile 16 yer değiştirir.

|4.adım|16|22|27|2|18|6|-->|16|2|22|27|18|6|
|------|-|-|-|-|-|-|----|-|-|-|-|-|-|

|-->|2|16|22|27|18|6|
|----|-|-|-|-|-|-|

18 ile 27 kıyaslanır. 18 küçük olduğu için 18 ile 27 yer değiştirir.Sonra 18 ile 22 kıyaslnaır. 18 küçük olduğu için 18 ile 22 yer değiştirir.Daha sonra tekrar 18 ile 16 kıayslanır. 18 16'dan büyük olduğu in hiçbir değişiklik yapılmaz.
|5.adım|2|16|22|18|27|6|-->|2|16|18|22|27|6|
|------|-|-|-|-|-|-|----|-|-|-|-|-|-|


6 ile 27 kıyaslanır. 6 ile 27 yer değiştirir.Sonra 6 ile 22 kıyaslanır. 6 küçük olduğu için 6 ile 22 yer değiştirir.Daha sonra tekrar 6 ile 16 kıyaslanır.6 16'dan da küçük olduğu için 6 ile 16 yer değiştirir.
|6.adım|2|16|18|22|6|27|-->|2|16|18|22|27|6|
|------|-|-|-|-|-|-|----|-|-|-|-|-|-|

|6.adım|2|16|6|18|22|27|-->|2|6|16|18|22|27|
|------|-|-|-|-|-|-|----|-|-|-|-|-|-|


##### 2.Big-O gösterimini yazınız.
O(n²)

##### 3.Time Complexity:
######  Worst case: Aradığımız sayının sonda olması.
Yani (n-1) + n + (n+1) +.....+ 2 + 1 + 0
[n.(n-1)] / 2 : n²

###### Average case: Aradığımız sayının ortada olması.
n² olarak buluruz.

###### Best case: Aradığımız sayının dizinin en başında olması.
n'dir.

##### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizinin ortasında olduğu için average case kapsamına girer.

#### 2. [7,3,5,8,2,9,4,15,6] dizisinin İnsertion Sort'a göre ilk 4 adımını yazınız.
|1.adım|7|3|5|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|

|2.adım|3|7|5|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|

|3.adım|3|5|7|8|2|9|4|5|6|
|------|-|-|-|-|-|-|-|-|-|

|4.adım|3|5|7|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|




