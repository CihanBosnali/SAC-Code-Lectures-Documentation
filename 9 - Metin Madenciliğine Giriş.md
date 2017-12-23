# Metin Madenciliğine Giriş
Metin Madenciliği Nedir? Metin Madenciliği verilen bir metinden özellik çıkarımı yapmak ve çıkartılan bu özelliklerden bazı sonuçlar elde etmektir.

Metin Madenciliği uygulamalarına örnek olarak "En çok kullanılan kelimeyi bulma", "Metinden Duygu Çıkarma", "Metinden Yazar Tahmini" gösterilebilir. SAC Code Lectures'da biz "en çok kullanılan kelimeyi bulma" yapmaktayız. 

Öncelikle Madencilik yapmak için metini bulup, metin'in üzerinde bazı düzenlemeler yapmalıyız.

## Metini Kodumuza Almak
Metin üzerinde işlem yapmak için öncelikle metini bilgisayarımızdan koda göndermemiz gerekiyor. Bunun için şu kod parçasını kullanıyoruz:

`with open("DOSYA İSMİ","r") as Dosya:`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`data = Dosya.read()`

open fonksiyonunun içine dosyamızın bilgisayardaki yerini yazıyoruz. Örnek olarak ben masaüstümdeki test adlı dosya için şunu yazmalıyım: `/users/cihan/Desktop/test.txt`. `"r"`'nin açılımı ise `read`'dir. Dosyayı okumak için aldığımızı belirtiyoruz.

İkinci satırda data isimli değişkeni, Dosya'ya yazdığımız read fonksiyonun return'üne atıyoruz. Yani verdiğimiz text'i bir string olarak data değişkenine atıyoruz.

Not 1: Ben MacOS işletim sistemi kullanıyorum. Sizin işletim sisteminize göre değişebilir.

Not 2: Dosyalarınızın uzantısı `.txt` olmalıdır.

Not 3: `as` komutundan sonra yazdığımız `Dosya` ismini biz verdik. İstediğinizi kullanabilirsiniz.

## Küçük Harf - Büyük Harf
Merhaba ve merhaba aynı kelime midir? Bir bilgisayar için değildir. Ama biz bir metin ile uğraşırken ikisinin aynı kelime olarak görülmesini istiyoruz, çünkü metin madenciliğinde herhangi bir anlam değişikliği yapmadığı için kelimenin büyük harf - küçük harf'ine bakmamamız gerekiyor. Peki nasıl kod ile bu işi değiştereceğiz? İki seçenek var: Hepsini küçük harf yapmak veya hepsini küçük harf yapmak.

Hepsini büyük harf yapmak için: `textName.upper()`

Hepsini büyük harf yapmak için: `textName.lower()`

komutlarını kullanıyoruz.

Not: `textName` kullandığımız değişkenin adı.

## Kelimeleri, Cümleleri ayırmak

Kelimeleri veya cümleleri birbirinden ayırıp, bir diziye atamak için split fonksiyonunu kullanıyoruz:

`textName.split(" ")`

Üstteki kodda textName isimli string'i boşluklardan ayırıyoruz. Split fonksiyonunun içine nokta (".") koysaydık bu sefer cümlelerden ayırmış olurduk.

Örnek olarak:

`textName = "merhaba güzel dünya"`

`textArray = textName.split(" ")`

`print(textArray)`

print'in çıktısı --> `["merhaba", "güzel", "dünya"]`

Artık textArray üzerinde istediğimiz tüm dizi işlemlerini yapabiliriz.
