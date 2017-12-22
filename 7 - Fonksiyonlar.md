# Fonksiyonlar (Functions)
50 satırlık bir kod parçamız olduğunu düşünelim. Bu parçayı kodumuzda 6 kez kullanıyoruz. Sırf bu kod parçasının yaptığı iş için 300 satır kod mu yazacağız? Tabi ki hayır. Fonksiyonları kullanarak bu işi 300 satıdan 57 satıra düşürebiliriz. Bir fonksiyonu yazmak iki aşamadan oluşur: fonksiyonu oluşturma ve fonksiyonu çalıştırma.

## Fonksiyon oluşturmak
`def myFunc(parameter1, parameter2):`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`toplam = parameter1 + parameter2`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`print(toplam)`

Üstteki kodda ilk satır fonksiyonun tanımlanması. `def` yazarak bir fonksiyon yarattığımızı belirtiyoruz. Daha sonra bir boşluk bırakıp fonksiyonun ismini yazıyoruz. Örnekte `myFunc`. Daha sonra parantez içinde parametreleri yazıyoruz ve iki nokta (:) koyuyoruz.

İkinci ve üçüncü satırlar fonksiyonun içi. Fonksiyon her çağrılıp çalıştırıldığında bu işlemler yapılacak.

### Parametre ne demek?
fonksiyonlar bazen fonksiyon dışından değer alarak çalışır. Fonksiyon çağırırken parametreleri yazıyoruz ve o parametreleri değişken gibi içeri alıyor.

## Fonksiyon Çağırma
`myFunc(5, 10)`

Bir fonksiyonu çağırırken sadece bunu yazmamız gerekiyor. FonksiyonunAdı(parametreler) şeklinde yazılıyor. 

Not 1:Bizim fonksiyonumuz iki parametre alıyor ama istediğiniz kadar alabilir (0 da dahil).

## Return işlemi
Bazı durumlarda fonksiyonun son bir değer vermesini ve bunu dışardaki bir değişkene atamak isteyebiliriz. Bu işleme `return` diyoruz. Örnek bir topla fonksiyonu yazalım:

`def topla(sayi1, sayi2):`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`toplam = sayi1 + sayi2`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`return toplam`

`sonuc = topla(7, 10)`

`print(sonuc)`
