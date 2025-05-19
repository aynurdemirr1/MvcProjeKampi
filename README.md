# 💠 ASP.NET MVC5 Dinamik Sözlük Uygulaması (Admin Paneli Destekli)

Bu proje, Murat Yücedağ'ın "MVC Proje Kampı" eğitim serisi temel alınarak geliştirilmiş, dinamik içerik yönetimi sağlayan, çok katmanlı mimariye sahip bir web sözlük uygulamasıdır.

## 🔍 Proje Özeti

Bu platformda kullanıcılar başlıklar altında yazı yazabilir, yazarlar arası mesajlaşma gerçekleştirebilir ve admin paneli üzerinden tüm içerik yönetilebilir. Proje, **SOLID prensipleri** ve **N-Katmanlı Mimari** yapısı dikkate alınarak oluşturulmuştur.

## 🧱 Mimari Yapı

Proje 4 ana katmandan oluşur:

- **Presentation Layer (Sunum Katmanı)**  
  Kullanıcı arayüzünün yer aldığı, verilerin görüntülendiği katmandır.

- **Business Layer (İş Kuralları Katmanı)**  
  Uygulama mantığını ve iş kurallarını yöneten servis katmanıdır.

- **Data Access Layer (Veri Erişim Katmanı)**  
  Entity Framework kullanılarak veritabanıyla bağlantı kurulan katmandır.

- **Entity Layer (Varlık Katmanı)**  
  Code First yapısıyla tanımlanmış POCO sınıflarının bulunduğu katmandır.

## 🧩 Temel Modüller ve Sayfalar

### 👨‍💼 Admin Paneli

- 🔐 Giriş Paneli (Session tabanlı doğrulama)
- 🏷️ Kategori Yönetimi (CRUD + Aktif/Pasif)
- 📌 Başlık ve Yazı Yönetimi
- 🧑‍💻 Yazar Yönetimi ve Profil Güncelleme
- 📝 Hakkımızda İçerik Yönetimi (Popup destekli)
- 📨 Mesajlaşma Sistemi (Admin ↔ Yazar)
- 📋 Raporlama Sayfası
- 🔑 Yetkilendirme ve Yeni Admin Ekleme
- 🚫 Hata Yönetimi
- 🌐 Siteye Yönlendirme

### ✍🏼 Yazar Paneli

- 🔐 Giriş Paneli
- 🪪 Profilim Sayfası (Bilgi güncelleme)
- 📣 Başlık Yönetimi (Kendi başlıkları)
- 📝 Yazı Yönetimi
- 📨 Mesajlaşma (Admin ↔ Yazar)
- 🌐 Siteye Erişim

### 🌍 Kamuya Açık Sözlük Sayfası

- Tüm başlık ve içeriklerin okunabildiği genel vitrin

### 🏠 Ana Sayfa (Landing Page)

- Projenin amacı, kullanılan teknolojiler ve ekran görüntüleri
- 📊 İstatistikler ve notlar
- 📬 İletişim Formu (Admin'e mesaj gönderme)

## ⚙️ Kullanılan Teknolojiler

- 💻 ASP.NET MVC5  
- 🧱 Entity Framework (Code First)  
- 🏗 N-Katmanlı Mimari  
- 🧭 SOLID Prensipleri  
- 🛢 SQL Server Veritabanı  
- 🔒 Session & Yetkilendirme  
- 🧪 Data Annotation & Validation

## 🌟 Bu Projeyle Neler Öğrendim?

Bu proje sayesinde hem teorik bilgileri pratiğe dökme hem de yazılım geliştirme süreçlerini uçtan uca deneyimleme şansı yakaladım:

- SOLID prensiplerini gerçek projede uygulamayı
- N-Katmanlı mimari ile temiz kod yazımını
- Entity Framework Code First + Migration kullanımını
- Admin ve yazar panelleri oluşturmayı
- Mesajlaşma sistemi ve kullanıcı rollerini yapılandırmayı
- Popup pencerelerle içerik girişini yönetmeyi
- Özel hata sayfalarıyla kullanıcı deneyimini artırmayı

## 📸 Ekran Görüntüleri

Aşağıda birkaç örnek görsel:

![Ekran görüntüsü 2025-05-19 113530](https://github.com/user-attachments/assets/ae2fdaef-d7fa-43e0-ac76-3bfb79c92154)
![Ekran görüntüsü 2025-05-18 233326](https://github.com/user-attachments/assets/dfadac23-bb97-4646-8509-27d80ac95b78)
![Ekran görüntüsü 2025-05-18 233852](https://github.com/user-attachments/assets/c34121eb-6814-4e98-a2ce-1c16a60ce7a8)
![Ekran görüntüsü 2025-05-17 222814](https://github.com/user-attachments/assets/96b6b55c-723a-494c-a532-9ffcd9fb6748)
![Ekran görüntüsü 2025-05-18 232930](https://github.com/user-attachments/assets/03941d1f-e1ec-41ed-8f7c-a11c077b6a39)
![Ekran görüntüsü 2025-05-18 232954](https://github.com/user-attachments/assets/54f76767-afd7-4c1e-a1fb-a9b1fa52f23c)
![Ekran görüntüsü 2025-05-18 233348](https://github.com/user-attachments/assets/88dd2110-d21c-4c93-89c6-39b6c9f6ce59)
![Ekran görüntüsü 2025-05-18 233011](https://github.com/user-attachments/assets/02469c33-171c-4c25-a6d0-78a372c3290f)
![Ekran görüntüsü 2025-05-18 233247](https://github.com/user-attachments/assets/034fd352-1463-4455-8a10-89ac1ba9fa12)
![Ekran görüntüsü 2025-05-18 233033](https://github.com/user-attachments/assets/4f982f4a-792c-46c5-a6f5-b0a1bd9fb39d)



