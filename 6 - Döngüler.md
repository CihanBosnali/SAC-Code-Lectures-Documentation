# Döngüler (Loops)
Bir program bazen aynı kod veya kod parçacığını onlarca kez kullanır. Peki bu kod parçacığını o kadar çok kez yazacak mıyız? Tabi ki hayır. Bir program aynı işi bir çok kez sırayla yapacaksa, aynı şeyi yazıp durmak yerine bir döngü kullanarak programı döngünün başına geri alıp tekrar okutturuyoruz. 

Örneğin bir programın 10 kez "Hello World!" yazdığını düşünelim. Algoritması şu şekilde olacaktır:
* 1) i'yi 1 olarak ayarla
* 2) i 10'dan küçükse devam et. Değilse 6. bölüm'e git.
* 3) "Hello world" yaz.
* 4) i'yi 1 arttır.
* 5) 2 nolu adıma dön
* 6) Bitir.

Peki bunu Python ile nasıl yazabiliriz? İki yönten var: While Döngüsü ve For döngüsü.
## While (sürece) Döngüsü
While döngüleri şu şekilde yazılırlar:

`i = 0`

`while i < 10:`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`print("Hello World!")`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`i += 1`

İlk satırda i isimli bir değişken oluşturup 0'a eşitledik. 

İkinci satırda while döngümüzü yazdık. Yazdığımız kodun anlamı şu: i değişkeninin değeri 10'dan küçük olduğu sirce döngüye gir.

Üçüncü satırda içerde istediğim işlemi yaptık.

Dördüncü adımda ise i'yi arttırdık. Bu sayede i aynı kalmadı ve i 10 olana kadar ilerledi.
