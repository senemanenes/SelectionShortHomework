# SelectionShortHomework
1.Soru-----------

[22,27,16,2,18,6] -->  Selection Sort'a göre sıralama

Temel prensip en küçük sayıyı, bul baştaki sayıyla yer değiştir.

Yukarıdaki dizide en küçük sayı 2. 2 ile dizinin ilk elemanı 22 yer değiştirildi. Dizi [2,27,16,22,18,6] oldu.

Daha sonra dizinin en küçük elemanı 6, 27 ile yer değiçtirdi. [2,6,16,22,18,27]

16 sayısı hali hazırda listenin en küçük elemanı olduğu için dizide değişiklik yapılmadı.

18, 22 ile yer değiştirdi. Dizi [2,6,16,18,22,27] oldu.

22 sayısı en küçük olduğu için dizide yer değiştirme yapılmadı ve dizi sıralanmış oldu.

Dizinin son ve sıralanmış hali=  [2,6,16,18,22,27] 

2.Soru --------------Big-O Gösterimi

n elemanımız var. Her sıralama işlemi sonrası dzideki işlem bir önceki işlemden 1 az olacak şekilde gerçekleşir. 1 işlem olana kadar yapılır. Formülizde edersek : n,n-1,n-2.... 1 olur.

Bu işlemleri toplarsak n*(n+1)/2 işlemmiz olur. Bu da (n^2 + n)/2 'ye eşittir. Bu sebeple dizinin Big-O gösterimi O[n^2]'dir.

Dizi sıralandıktan sonra yani [2,6,16,18,22,27] 18 sayısı ortada olduğu için averga case kapsamına girer.





Diğer Soru [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1.Adım 
--> Dizideki en küçük sayı 2 sayısı listenin başındaki 7 sayısı ile yer değiştirilir. [2,3,5,8,7,9,4,15,6]
 
2.Adım
--> Dizideki bir sonraki küçük sayı 3, zaten dizinin 2'den sonraki en sağında olduğu için yer değiştirme yapılmaz. [2,3,5,8,7,9,4,15,6]

3.Adım
--> Dizideki bir sonraki küçük sayı 4 listenin 3'ten sonraki en baştaki sayı olan 5 ile yer değiştirir. [2,3,4,8,7,9,5,15,6] 

4.Adım
-->Dizideki bir sonraki küçük sayı 5 listenin 4'ten sonraki en baştaki sayı olan 8 ile yer değiştirir. [2,3,4,5,7,9,8,15,6] 


#patika.dev ödevidir.



