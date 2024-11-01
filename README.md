# Hastane Randevu Sistemi
Bu C# Windows Forms uygulaması, bir hastanenin randevu ve hasta yönetimi için geliştirilmiştir. Sekreter, doktor ve hasta için farklı ihtiyaçlara uygun arayüzler sunan bu sistem, her kullanıcının kendi işlevlerini kolayca gerçekleştirebilmesi amacıyla hazırlanmıştır. Aşağıda sistemin özellikleri detaylandırılmıştır.

## Modüller ve Özellikler
1. Giriş Paneli
Hasta, Doktor ve Sekreter için ayrı giriş panelleri bulunmaktadır.
Kullanıcılar, TC Kimlik Numarası ve şifreleri ile sisteme giriş yaparlar.
Kayıtlı olmayan hastalar, kayıt formunu doldurarak sisteme üye olabilir.

![1](https://github.com/user-attachments/assets/e12169cb-c53a-4b73-82f8-4abd7f749ed4)
![2](https://github.com/user-attachments/assets/320b59bb-14f7-456c-8444-b4e53dad51ac)

# 2. Hasta Kayıt Paneli
Yeni hastalar, ad, soyad, TC kimlik numarası, telefon numarası, şifre ve cinsiyet gibi bilgileri girerek kayıt olabilir.
Kayıt işlemi tamamlanan hastalar, sisteme giriş yaparak randevularını görüntüleyip yönetebilirler.

![3](https://github.com/user-attachments/assets/88a3f9ae-2ea8-4990-bda8-8c39fc067f77)

# 3. Hasta Paneli
Hasta Bilgileri: Hastanın TC kimlik numarası ve adı görüntülenir.
Randevu Alma: Hastalar, branş ve doktor seçerek yeni randevu oluşturabilir ve şikayetlerini belirtebilir.
Aktif ve Geçmiş Randevular: Hastalar, aktif ve geçmiş randevularını tarih, saat, branş, doktor ve şikayet bilgileriyle görebilir.

![4](https://github.com/user-attachments/assets/4b09bd35-4ee2-4dbd-9779-c8215184870c)
![5](https://github.com/user-attachments/assets/a7db94cf-b247-4eeb-91aa-e6cc4c3b15bf)

# 4. Sekreter Paneli
Sekreter Bilgisi: Sekreterin TC kimlik numarası ve adı görüntülenir.
Duyuru Oluşturma: Sekreter, hastane personeli için duyuru oluşturabilir.
Randevu Yönetimi: Sekreter, randevu oluşturma, düzenleme ve silme işlemlerini gerçekleştirebilir.
Doktor ve Branş Yönetimi: Sekreter, doktorları farklı branşlara atayabilir ve branşları görüntüleyebilir.
Hızlı Erişim: Doktor ve branş panellerine, randevu listesine ve duyurulara hızlı erişim butonları bulunur.

![10](https://github.com/user-attachments/assets/6b3be3b4-d7a6-4738-97b2-64ca898b8abd)
![11](https://github.com/user-attachments/assets/4c28592c-1910-4890-91a4-35650acafd6c)
![14](https://github.com/user-attachments/assets/246bfd93-de82-4a2e-98b2-2aee9b929f9c)

# 5. Doktor Paneli
Doktor Bilgileri: Doktorun TC kimlik numarası ve adı görüntülenir.
Randevu Listesi: Doktor, kendisine atanmış tüm randevuları tarih, saat, hasta ve şikayet bilgileriyle görebilir.
Randevu Detayları: Doktorlar, her randevunun detayında hastanın şikayetini inceleyebilir.
Hızlı Erişim: Kişisel bilgileri düzenleme ve hastane duyurularını görme butonları mevcuttur.

![6](https://github.com/user-attachments/assets/46988c1a-0f18-4732-9190-14547d0250be)
![7](https://github.com/user-attachments/assets/1fa721b9-0417-4fbd-b2e3-e78897ac62cf)

# 6. Duyurular
Hastane duyuruları, tüm personelin görüntüleyebilmesi için sistemde yer almaktadır.
Sekreterler, duyuru ekleyebilir, güncelleyebilir veya silebilir.
![9](https://github.com/user-attachments/assets/4854cf42-3fd2-414b-ad53-5d51f6ad70ad)

# 7. Veri Tabanı Yönetimi
Bu uygulamada veri tabanı olarak Microsoft SQL Server Management Studio kullanılmaktadır.
Kullanıcılar tarafından girilen tüm veriler, bu veri tabanına kaydedilmekte ve yönetilmektedir.
Randevu, hasta, doktor ve duyuru gibi bilgiler SQL Server üzerinde saklanarak verilerin güvenli ve hızlı erişimine olanak tanınmaktadır.
