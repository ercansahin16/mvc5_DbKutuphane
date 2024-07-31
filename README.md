# ASP.NET MVC ile Kitap Kütüphane Yönetim Sistemi Projesi

## Proje Hakkında

Bu proje, ASP.NET MVC teknolojisi kullanılarak geliştirilmiş bir kitap kütüphane yönetim sistemidir. Proje üç farklı panelden oluşmaktadır: Admin Paneli, Vitrin Paneli ve Kullanıcı Paneli. Bu paneller sayesinde sistemde yetkilendirilmiş kullanıcılar farklı işlemler gerçekleştirebilmektedir. Proje, Entity Framework, LINQ, SQL, Bootstrap, CSS, HTML5 ve diğer modern web teknolojileri kullanılarak inşa edilmiştir. Projenin veritabanı yapısı "DB First" yaklaşımı ile oluşturulmuştur.

## Paneller ve İşlevleri

### Admin Paneli

![Admin Login](https://github.com/ercansahin16/mvc5_DbKutuphane/blob/main/img/AdminLogin.png)

- Admin kullanıcıları bu panel üzerinden sisteme giriş yapabilir, yeni kullanıcılar oluşturabilir ve yönetebilirler.
- Kitap yönetimi, ceza yönetimi, duyurular, kasa işlemleri gibi önemli yönetimsel işlemler bu panel üzerinden gerçekleştirilir.

### Vitrin Paneli

- Bu panel, kütüphanenin web sitesi gibi çalışarak, ziyaretçilere kitaplar ve kütüphane hakkında bilgi sunar.
- Duyurular ve Hakkımızda gibi sayfalar da bu panel üzerinden ziyaretçilere sunulur.

### Kullanıcı Paneli

- Kayıtlı kullanıcılar bu panel üzerinden giriş yapabilir, kitap ödünç alabilir ve iade edebilirler.
- Kullanıcılar, ceza durumlarını görebilir ve mesajlaşma sistemi aracılığıyla kütüphane personeli ile iletişime geçebilirler.

## Veritabanı Yapısı

Projede toplamda 13 ilişkili tablo bulunmaktadır:

- **ADMİN:** Admin kullanıcılarını yönetir.
- **CEZALAR:** Bir haftalık ödünç kitap süresini aşan kullanıcılar için günlük 1 TL ceza uygulanır ve bu cezalar kasa tablosunda tutulur.
- **DUYURULAR:** Kütüphane ile ilgili duyuruların yönetildiği tablo.
- **HAKKIMIZDA:** Kütüphane hakkında bilgilerin bulunduğu tablo.
- **HAREKET:** Kitap ödünç alma ve iade işlemlerinin kaydedildiği tablo.
- **İLETİŞİM:** Kütüphane ile iletişime geçmek isteyen kullanıcıların mesajlarının tutulduğu tablo.
- **KASA:** Ceza ücretlerinin toplandığı ve izlendiği tablo.
- **KATEGORİ:** Kitap kategorilerinin bulunduğu tablo.
- **KİTAP:** Kütüphanede bulunan kitapların kaydedildiği tablo.
- **MESAJLAR:** Kullanıcıların ve personelin birbirine gönderdiği mesajların kaydedildiği tablo.
- **PERSONEL:** Kütüphane personelinin bilgilerini içeren tablo.
- **ÜYELER:** Kütüphane üyelerinin kayıtlarının tutulduğu tablo.
- **YAZARLAR:** Kitap yazarlarının bilgilerini içeren tablo.

## Projenin Geliştirilmesi ve Kazanımlar

Bu proje üzerinde çalışmak, benim için büyük bir öğrenme deneyimi ve kişisel gelişim süreci olmuştur. ASP.NET MVC, Entity Framework ve LINQ gibi teknolojilerle çalışarak, bu alanlardaki bilgimi derinleştirdim ve yeteneklerimi geliştirdim. Ayrıca, SQL veritabanı tasarımı ve yönetimi konularında pratik deneyim kazandım.

Bu projenin GitHub üzerinde paylaşılması, sadece benim için değil, aynı zamanda bu projeyi inceleyecek ve benzer projeler üzerinde çalışacak diğer geliştiriciler için de değerli bir kaynak olacaktır.

## GitHub Bağlantısı

Projenin kaynak kodlarına GitHub üzerinden erişebilir ve detaylı inceleyebilirsiniz: [Kitap Kütüphane Yönetim Sistemi Projesi](https://github.com/ercansahin16/mvc5_DbKutuphane)

## Sonuç

Bu proje, kütüphane yönetim süreçlerini dijitalleştirerek daha verimli ve organize bir sistem sunmaktadır. Aynı zamanda, geliştirme sürecinde elde edilen deneyimler ve öğrenilen yeni teknolojiler, gelecekteki projeler için sağlam bir temel oluşturacaktır. Bu proje üzerinde çalışmak büyük bir emek ve çaba gerektirmiştir ve elde edilen sonuçlar oldukça tatmin edicidir.

### Admin Paneli bağlantı adresi: /AdminLogin/Login/
- **Username:** admin@admin.com
- **Şifre:** 123
