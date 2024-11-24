Film (Movie): Filmlerin adı, süresi ve türü gibi bilgileri içerir.
Salon (Theater): Salonun adı ve içerisinde gösterilen filmlerle birlikte kaydedilen müşteri bilgilerini tutar.
Müşteri (Customer): Müşterilerin adı, soyadı ve müşteri numarası gibi bilgileri içerir. Ayrıca, film kaydı yapılabilir.
Interface (IKayit): Müşterinin kayıt olabilmesi için gerekli metodları tanımlar.
Polymorphism: Temel sınıfta bulunan bilgiGoster() metodunun türetilmiş sınıflarda özelleştirilmesiyle kullanılmıştır.

Kullanıcı İşlevselliği
Filmler
Matrix: Bilim kurgu türünde, 136 dakika süren bir film.
Ben Efsaneyim: Komedi türünde, 118 dakika süren bir film.
Salonlar
Salon 1: "Matrix" filmi gösteriliyor.
Salon 2: Hem "Matrix" hem de "Ben Efsaneyim" filmi gösteriliyor.
Müşteriler
Pelin Şahinbey: "Matrix" ve "Ben Efsaneyim" filmlerine kaydolmuştur.
Mina Özgül: "Matrix" filmine kaydolmuştur.
Sınıflar ve Metodlar

BaseEntity
Ortak özellikler: ad, soyad
Ortak metod: bilgiGoster()
Film
Özellikler: ad, sure, tur
Metodlar:
filmBilgisi(): Film bilgilerini gösterir.
Salon
Özellikler: salonAd, filmler, musteriListesi
Metodlar:
filmEkle(): Filmleri salonlara ekler.
musteriKayitOl(): Müşteriyi belirli bir filme kaydeder.
salonBilgisi(): Salon bilgilerini ve gösterilen filmleri gösterir.
musteriListele(): Salonun kaydedilen müşterilerini listeler.
Musteri
Özellikler: ad, soyad, musteriNo
Metodlar:
kayitOl(): Müşterinin kaydını yapar.
bilgiGoster(): Müşterinin bilgilerini gösterir.
