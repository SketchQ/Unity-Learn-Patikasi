# Değişkenler

## Değişkenler Nedir?

Değişkenler bizim uygulama geliştirirken kullandığımız veri tutucularımızdır. Kullandığımız verinin tipine ve büyüklüğüne bağlı olarak doğru veri tipini seçiyor olmak önemli. Örneğin sadece tek bir karakter tutmaya ihtiyacımız varsa o veri için Char veri tipinizi tanımlamak yeterli olacaktır. String tipinde bir değişken kullanmak gereksizdir. Uygulamanın performansı açısından doğru veri tiplerine karar verebilmek önemlidir.

Syntax :

```C#
(Değişken Türü)(değişken Adı) = (değeri);
int int1 = 20;
```

### Dikkat edilmesi gereken hususlar

* Değişkenler case sensitive yani büyük küçük harf duyarlıdır.
* Değişken isimleri rakamlarla başlayamaz.
* Değişken isimleri boşluk içeremez. Yalnızca "_" ifadesi kullanılabilir.
* Değişken isimlerinin arasında matematiksel ifadeler yani işlem operatörleri kullanılamaz.
* Class namespace gibi özel isimler kullanılamaz.
* Değişkenlerin her zaman bir değeri olmak zorundadır. Yoksa null tanımlanmalıdır. Ataması yapılmayan değişkenler kullanıldığında derleyici hata verir.

### Derleme ve String kütüphaneleri

Datetime ve String veri tiplerlerini yazılım geliştirirken çok kullanıyoruz. İlerleyen derslerde sadece bu kütüphaneleri kullanarak bolca örnek yapacağız. Ama öncesinde daha yakından bakmanın faydalı olacağını düşünüyorum.

[Datetime](https://docs.microsoft.com/tr-tr/dotnet/api/system.datetime?view=netcore-3.1)

[String](https://docs.microsoft.com/tr-tr/dotnet/api/system.string?view=netcore-3.1)
