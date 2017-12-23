# Modüller (Modules)
Her kodu elle yazmaya çalışmak, her araba yapılışında tekerleği baştan icat etmek gibidir. Dünya üzerinde binlerce yazılım gelişitirici var ve tekerleği çoktan icat eden büyük ihtimalle olmuştur. O yüzden biz de tekerleği baştan yaratmak yerine onların tekerleklerini kullanabiliriz. Arabayı yine biz yapacağız. İçine kendi icadımız olan birçok şey koyacağız ama basit işler için zaman ve enerji harcamamalıyız. Bu yüzden modüller kullanıyoruz. Modüller yazılımcılar tarafından oluşturulmuş fonksiyonlarla dolu dosyalardır. Bu dosyadan kullanacağımız fonksiyonu kendi kodumuza entegre ederek kullanabiliyoruz.

## Import
`import` komutu ile bir modülü kendi yazılım dosyamıza çağırıyoruz. Örneğin:

`import random`

komutu ile random modülünü çağırıyoruz. (Random şansa sayı üreten bir modüldür.)

## Kullanım
Her modülün kullanımı farklı olsa da içi fonksiyonlardan oluşur. Örneğin `random` modülündeki bazı fonksiyonlara göz atalım:

`myRandNum = random.randint(1,10)`

Üstteki koddaki kullanım `DeğişkenAdı = ModülAdı.Fonksiyon` şeklindeydi.

## Çok Kullanılan Bazı Modüller

### Random
Random şansa sayı üretme modülüdür. Özellikle Oyun, Çekiliş vs. programlarında çokca kullanılır. Random modülünde birçok fonksiyon var. Bunlardan basit olanlara bakalım:

`random.random()` -> 0 ile 1 arasında şans sayı üretir.

`random.randint(start, end)` -> start ve end intiger'ları arasında tam sayı üretir.

`random.randrange(start, end, aralık)` -> start ve end intiger'ları arasında şansa aralık ile sayı üretir. Örneğin, aralık 2 ise çift sayı üretir.

`item = [1,2,3,4,5,6]`

`random.shuffle(item)` -> item isimli dizinin elemanlarının sırasını karıştırır.

Not 1: Modüller bazı kaynaklarda kütüphane (library) olarak geçer.
