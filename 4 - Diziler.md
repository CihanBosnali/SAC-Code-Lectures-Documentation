# Diziler (Arrays)
Bazı durumlarda her değişkene teker teker isim atamak imkansızdır. Örneğin prograam yeni değerler üretip saklayacağı zaman. Diziler tek bir değişken gibi saklanan ama içine sırayla istediğimiz kadar değişkeni koyabildiğimiz bir değişken türüdür.

Şu şekilde ifade edilirler:

`fruits = ["apple", "pear", "banana"]`

üstteki kodda ismi fruits olan içinde elma, armut ve muz olan bir liste - dizi (Array) oluşturduk. Array oluştururken değişken oluşturur gibi bir isim yazıyoruz. Sonrasında atama işaretimizi (`=`) koyuyoruz. Sonrasında ise köşeli parantez'in (`[]` (Alt - 8, Alt - 9 tuşları)) içine değişkenlerimizi virgül (`,`) ile ayırarak yazıyoruz.

## Dizilerin içinden değişkeni alma
Bir dizi'nin (array'in) içinde bir çok değişken koyabiliriz. Peki bu değişkenlerden birini nasıl geri çağıracağız?

Dizilerde dizinin her elemanı (üstteki örnekte apple, pear ve banana; fruits dizisinin elemanlarıdır.) hangi sırada olduğu ile ifade edilebilir:

`print(fruits[1])`

Üstteki kodda fruits isimli dizinin 1 nolu elemanını yazdır dedik. Bunun yerine tabiki aynı elemanı ayrı bir değişkene de atayabiliriz:

`myFavouriteFruit = fruits[1]`

Bu koddan da anlaşıldığı üzere bir dizinin bir elemanını çağırırken `DizininAdı[ElemanınSırası]` şeklini kullanıyoruz. Yani dizinin adını yazıyoruz. Birleşik şekilde köşeli parantez koyuyoruz ve köşeli parantezin içine kaç numaralı elemanı istediğimizi yazıyoruz.

Not 1: Bir dizinin içinden değişken alırken köşeli parantezin içine değeri integer olan bir değişken koyarsanız. O değişkenin değeri nolu elemanı alır. Örneğin:

`myInt = 3`

`myArray = ["Rabbit", "Dog", "Cat", "Bird", "Fish"]`

`print(myArray[myInt])`

Program `myArray[myInt]` satırına geldiğinde myInt yerine değeri olan 3 sayısını koyar ve `myArray[3]` komutunu uygular.

## Programcılar Saymaya Sıfırdan Başlar!
Normal hayatta sayma sayıları 1'den başlar. Ancak programlamada sayma sayılarımız 0'dan başlar deriz. Yani dizinin ilk elemanı 0. elemanıdır.

Bu durumda ilk örnekteki `print(fruits[1])` kodunun yazdıracağı değer `pear` değeridir.

## Dizilerde Kullanılan Birkaç Fonksiyon
Fonksiyonlar konusunu fonksiyonlar isimli sayfada göreceksiniz. Bir fonksiyon kısaca tek bir satırla başka bir yerde yazılmış kodu çalıştıran kod parçasıdır.

Bu bölüm dizilerde kullanılan, Python ile gelen bazı fonksiyonlar ile ilgilidir.

### Append Fonksiyonu
Append fonksiyonu bir dizinin içine kod ile yeni bir değişken koymamızı sağlar:

`myArray.append("Lion")`

Üstteki kodda myArray isimli dizinin en sonuna Lion isimli bir değişken ekliyoruz. Array şu şekile geliyor:

`myArray = ["Rabbit", "Dog", "Cat", "Bird", "Fish", "Lion"]`
