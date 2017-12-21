# Kontrol Yapıları (If - Else - Elif)
Kontrol yapıları yazılımın en önemli parçalarından biridir. Programların işlemleri Neden - Sonuç bağı içinde yapmasını sağlar. Python dilinde kontrol yapıları If (Eğer), Else (Değilse), Elif (Değilse eğer) yapılarından oluşur.

## If - Eğer Yapısı
If yapısı "Eğer şu doğru ise şunu şunu şunu yap" şeklinde çalışır. Daha iyi görmek için kod üzerinden gidelim. Bir if komutu şu şekilde yazılır:


`myInt = 5`

`yourInt = 6`

`if myInt < yourInt:`
 
 
 
 
&nbsp; &nbsp; &nbsp; &nbsp;`  myInt = myInt + 1`
  
  
İlk iki satırda kullanacağımız değişkenleri tanımladık.

` if myInt < yourInt: ` satırında ise if komutunu verdik. Bu komut şunu diyor: ` Eğer myInt isimli değişken yourInt isimli değişkenden küçükse`

Yani eğer myInt yourInt'den küçük ise if'in içindeki işlemi yapacak.

Not 1: Bir kodu kontrol yapısının içine almak için "Tab" tuşuna basmalısınız. (Genellikle Q harfinin solundaki tuş) Bu şekilde kod parçasının sağa doğru hareket ettiğini göreceksiniz. Program, kontrol yapısına girdiğinde yapının bir tab içindeki kod parçacığını çalıştırmaya başlar.

## Else - Değilse Yapısı
Eğer if yapısının sonucu Doğru değilse program if yapısının içindeki kod parçacıklarını atlayarak devam eder. Ancak bazen if doğru değilse bir şey yapmasını isteyebiliriz. Bu durumda kullanacağımız yapı Else yapısıdır. Program sadece if yapısı yanlış olduğunda else'e girer.

`myBool = False`

`if myBool:`

&nbsp;&nbsp;&nbsp;&nbsp;`print("Hi!")`

`else:`

&nbsp;&nbsp;&nbsp;&nbsp;`print("Bye!")`

Bu kodda ne yaptık:
* 1. satırda False değeriyle bir Boolean oluşturduk.
* 2. satırda If yapısını 1. satırda oluşturduğumuz bool ile kullandık.
* 3. satırda If yapısının içindeki işlemleri yazdık. If'e girer ise yapacak, girmez ise yapmayacak.
* 4. satırda Else yapısını ayarladık. Else yapısını sadece `else:` yazarak yazıyoruz.
* 5. satırda Else yapısına girdiğinde yapacağımız şeyleri yazdık.
