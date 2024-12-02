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

-ENGLISH-

This project focused on testing an API that manages hotel reservation processes and developing automation processes. Within the scope of the project, I tested user login, reservation creation, update, deletion and query processes. I created test scenarios using Postman and provided a dynamic structure with environment variables. I automated the tests with the Newman tool and created reports in JSON and HTML format. I ensured that these tests were run automatically at regular intervals every Friday using Monitor Runner and that the report results were sent via e-mail.

Skills Gained with the Project: Creating API test scenarios and running automation processes. Automating and reporting tests with Postman and Newman. Developing dynamic and secure test processes using environment variables.

Manual and Automated Tests: API test scenarios were created manually using Postman and verification processes were performed. Tests were automated with the Newman tool and reported in JSON and HTML formats.

Regular Test Runs: Tests were run regularly every Friday using Postman Monitor. Run results were shared via e-mail notifications and detailed reports were added.

Environment Variables: Environment variables are used for dynamic parameters and API key management. The values ​​obtained during the tests (token, reservation ID) are dynamically saved to the environment.

Test Scenarios: Login and authorization. Creating a new reservation and verifying the information. Reservation update and deletion operations. Querying reservation details (all reservations or a specific reservation).
