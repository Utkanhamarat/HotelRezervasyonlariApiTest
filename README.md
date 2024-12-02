# HotelRezervasyonlariApiTest
Bu proje, otel rezervasyon süreçlerini yöneten bir API’nin test edilmesi ve otomasyon süreçlerinin geliştirilmesi üzerine odaklandım. Proje kapsamında kullanıcı oturum açma, rezervasyon oluşturma, güncelleme, silme ve sorgulama işlemlerini test ettim. Postman kullanarak test senaryoları oluştuşturdum ve environment değişkenleriyle dinamik bir yapı sağladım. Newman aracı ile testler otomatikleştirdim ve JSON ile HTML formatında raporlar oluşturdum. Monitor Runner kullanılarak bu testlerin düzenli aralıklarla Her cuma günü otomatik çalıştırılması ve rapor sonuçlarının e-posta ile iletilmesini sağladım. 

Proje ile Kazanılan Beceriler:
API test senaryoları oluşturma ve otomasyon süreçlerini yürütme.
Postman ve Newman ile testlerin otomatikleştirilmesi ve raporlanması.
Environment değişkenleri kullanarak dinamik ve güvenli test süreçleri geliştirme.

Manuel ve Otomatik Testler:
Postman kullanılarak API test senaryoları manuel olarak oluşturulmuş ve doğrulama işlemleri yapılmıştır.
Newman aracı ile testler otomatikleştirilmiş, JSON ve HTML formatlarında raporlanmıştır.

Düzenli Test Çalıştırmaları:
Postman Monitor kullanılarak testler her hafta cuma günü düzenli olarak çalıştırılmıştır.
Çalıştırma sonuçları e-posta bildirimleriyle paylaşılmış, detaylı raporlar eklenmiştir.

Environment Değişkenleri:
Dinamik parametreler ve API anahtarı yönetimi için environment değişkenleri kullanılmıştır.
Testler sırasında alınan değerler (token, rezervasyon ID) dinamik olarak environment’a kaydedilmiştir.

Test Senaryoları:
Oturum açma ve yetkilendirme.
Yeni rezervasyon oluşturma ve bilgilerin doğrulanması.
Rezervasyon güncelleme ve silme işlemleri.
Rezervasyon detaylarını sorgulama (tüm rezervasyonlar veya belirli bir rezervasyon).
