# Python'da Matematiksel İşlemler
Tüm yazılım dilleri, matematiksel işlemler yapmakta ustadırlar. Bunun nedeni de bilgisayarlarımızın matematik üzerine kurulu sistemlerden oluşmasıdır. Her programda matematik kullanırız. Bu yüzden matematik işlemerini nasıl yaptığımızı görmek de önemlidir.

Peki, bu işlemler nasıl yapılır?

## Toplama
Toplama işleminde özel bir durum yok. Sadece + (artı) işareti kullanıyoruz:

`print(5 + 7)`

## Çıkarma
Çıkarma işleminde de özel bir durum yok. Sadece - (eksi, kısa çizgi) işareti kullanıyoruz:

`print(10 - 7)`

## Çarpma
Çarpma işleminde `*` (yıldız) işaretini kullanıyoruz:

`print(5 * 6)`

## Bölme

Bölme işleminde `/` (slash ( klavyede üst 7)) işaretini kullanıyoruz:

`print(15 / 3)`

## Üstünü alma

Eğer iki kez yıldız (`**`) kullanırsak bu üstünü alma işlemidir.

`print(2 ** 3)`

Yukarıdaki kodun çıktısı "2 üstü 3" yani 2 x 2 x 2 = 8'dir.

# Büyüktür, Küçüktür, Eşittir...
Matematikte kullandığımız <, >, = gibi işaretler programlamada da karşımıza çıkar. Peki bu işaretleri python'da nasıl kullanıyoruz.

## Eşittir
Programlamada = işareti "atama" amacıyla kullanılır. (atama işlemine değişkenler bölümünden okuyabilirsiniz.) O yüzden eşittir demek için `==` (iki tane = işareti) kullanılıyor.

`print(5 == 5)`

Not: Bu işlemler `True` (Doğru) veya `False` (Yanlış) olarak iki sonuç dönmektedir.

## Eşit Değildir
Matematikte "eşit değildir" işareti eşittir işaretinin üzerine bir çizgi atarak kullanılır. Ancak klavyede böyle bir şey yapamayız. O yüzden yazılım dillerinde eşit değildir demek için `!=` (ünlem işareti ve eşittir işareti) yazıyoruz. Sanki çizgiyi üzerine koyamayınca yanına koymuşuz gibi görünüyor değil mi?

`print(7 != 4)`

## Büyüktür ve Küçüktür
Büyüktür ve küçüktür işaretleri matematikte kullanıldığı ile aynı şekilde kullanılır:

`print(4 < 8)`

ve

`print(7 > 6)`

## Büyük eşittir ve küçük eşittir

Büyük eşit ve küçük eşit işaretlerinde yine matematiksel gösterimi kullanamadğımızdan dolayı `<=` ve ` >=` işaretleri kullanılır:

`print(3 >= 3)`

ve

`print(8 <= 8)`
