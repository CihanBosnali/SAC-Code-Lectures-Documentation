# Değişkenler
Herhangi bir işlemi yapabilmek için o işlemi üzerinde uygulayacağımız, bilgisayarımızda kayıtlı, bilgiyi almamız gerekir. Örneğin toplama işlemi yapmak için toplayacağımız iki sayıyı bilgisayarın hafızasından alarak programa vermeliyiz. Bu bilgiyi bilgisayarda tutmak için ise ona bir isim atamamız gerekir. Yoksa bilgiyi tekrar kullanmak için onu nasıl bulabilrdik ki? İşte bu isimlere değişken diyoruz. Değişkenlerin amacı bilginin içinde tutulduğu bir kutu görevi görmektir.
Bir değişken şu şekilde tanımlanır:

`
DeğişkenAdı = DeğişkenDeğeri
`

İlk önce değişkene bir ad verilir. Sonra çoğu yazılım dilinde "Atama" işlevinde olan "=" işareti koyulur. Daha sonra da değişkenin değeri girilir.

## Değişken Türleri
Değişkenlerin bazı türleri vardır. Bu türler değişkeni yazı, tam sayı,ondalıklı sayı vb. şekillerde belirtmemizi sağlar. Eğer yanlış şekilde bir belirtme olursa, bilgisayar değişkeni yanlış algılayabilir. Örneğin iki sayıyı toplarken onları yazı değişkeni olarak belirttiysek iki sayıyı yan yana yazacaktır.

Peki bu değişken türleri nelerdir?
* String
* Integer
* Float
* Character
* Boolean

## String - Yazı Değişkeni
Stringler içlerinde yazıları tuttuğumuz değişkenlerdir. İçine koyduğumuz değer bir yazı olarak algılanacaktır. Örneğin bir sayı koyduğumuzda, bu sayı da bilgisayar tarafındn sayı olarak algılanmaz ve matematiksel işlem yapılamaz.

Stringler şu şekilde belirtilir:

`
myNewString = "Hello World!"
`

Not 1: Çift Tırnak ("   ") işareti içine alınan her şey bilgisayar tarafından yazı olarak algılanır. Çift tırnak işareti içine koyulmayan her yazı ise kod parçacığı olarak algılır. Örneğin string belirtirken hatayla ``` myString = Hello ``` gibi yazarsanız. Kodunuzda Hello isminde bir değişken arayacaktır. Bulamayınca da hata verecektir.

Not 2: myNewString benim tarafımdan verilmiş bir isimdir. Siz istediğiniz herhangi bir ismi kullanabilirsiniz.

## Integer - Tam Sayı Değişkeni
Integerlar tam sayı değişkenleridir. Tuttukları değerler tam sayıdır. Herhangi bir yazı tutamazlar.

Şu şekilde gösterilirler:

``` myInteger = 42 ```

## Float - Ondalıklı Sayı Değişkeni
Float isimli değişkenler ondalıklı sayıları tutarlar. Örneğin 12.35261 gibi bir sayı float ile tutulur. Eğer tutulan sayı tam sayı ise 12.0 şeklinde gösterilir.

Şu şekilde gösterilirler:

``` piNumber = 3.14159265 ```

## Character - Karakter (harf) değişkeni
Character değişkeni de String gibi yazı tutar. tek bir harf veya karakteri tutmak için kullanılır.

Şu şekide gösterilir:

` myAnswer = 'c' `

Not 1: Python dilinde bir character birden fazla karakteri tutabilir. Bu nedenle String'den önemli bir farkı yoktur. :)

## Boolean - Doğru - Yanlış (0 - 1) Değişkeni
Bir bool sadece iki değer alabilir: Doğru ve Yanlış. Genellikle kontrol komutlarında çok işe yarar.

Şu şekillerde gösterilebilir:

*Direkt olrak Doğru veren bir değişken için: ` myBool = True `
*Direkt olrak Yanlış veren bir değişken için: ` myBool = False `
*Bir kontrol işleminin cevabını veren değişken için: ` myBool = (5 * 2 < 12) `
