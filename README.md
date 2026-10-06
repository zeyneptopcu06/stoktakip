# 📦 Stok Takip Sistemi

Bu proje, ürün, depo ve stok hareketlerinin yönetilebildiği full-stack bir stok takip uygulamasıdır. Uygulama **Next.js**, **React**, **Java Spring Boot** ve **PostgreSQL** kullanılarak geliştirilmiştir.

## 📌 Proje Hakkında

Stok Takip Sistemi; işletmelerin ürünlerini, depolarını ve stok giriş/çıkış hareketlerini daha düzenli şekilde takip edebilmesi amacıyla geliştirilmiştir.

Uygulamada ürün yönetimi, depo yönetimi, stok hareketleri, mevcut stok durumu ve kullanıcı giriş/kayıt işlemleri bulunmaktadır.

Bu proje ile frontend ve backend yapısının birlikte çalışması, REST API entegrasyonu, veritabanı yönetimi ve kullanıcı odaklı arayüz geliştirme konularında pratik yapılmıştır.

## ✨ Özellikler

- Kullanıcı kayıt ve giriş işlemleri
- Ürün ekleme, listeleme, güncelleme ve silme
- Depo ekleme, listeleme, güncelleme ve silme
- Stok giriş ve stok çıkış işlemleri
- Mevcut stok durumunu görüntüleme
- Minimum ve maksimum stok limitleri ile kontrol
- Backend ve frontend arasında REST API entegrasyonu
- PostgreSQL veritabanı kullanımı
- Modern ve kullanımı kolay web arayüzü

## 🛠️ Kullanılan Teknolojiler

**Frontend:** Next.js, React, JavaScript  
**Backend:** Java, Spring Boot  
**Veritabanı:** PostgreSQL  
**API Test:** Postman  
**Araçlar:** Git, GitHub, IntelliJ IDEA, VS Code

## 📁 Proje Yapısı

- `aa/`: Frontend tarafı
- `backend/stockTracking/`: Backend tarafı
- `app/`: Next.js sayfa ve bileşen yapısı
- `components/`: React bileşenleri
- `src/main/java/`: Java backend kaynak kodları
- `application.properties`: Backend yapılandırma dosyası
- `pom.xml`: Spring Boot bağımlılıkları
- `package.json`: Frontend bağımlılıkları ve komutları

## 🚀 Kurulum ve Çalıştırma

PostgreSQL üzerinde veritabanı oluşturun:

`CREATE DATABASE stock_tracking;`

Backend için `application.properties` dosyasındaki veritabanı bilgilerini kendi bilgisayarınıza göre düzenleyin:

`spring.datasource.url=jdbc:postgresql://localhost:5432/stock_tracking`

`spring.datasource.username=postgres`

`spring.datasource.password=POSTGRESQL_SIFRENIZ`

Backend projesini IntelliJ IDEA ile açıp Spring Boot uygulamasını çalıştırın.

Frontend klasörüne girin:

`cd aa`

Bağımlılıkları yükleyin:

`npm install`

Frontend uygulamasını başlatın:

`npm run dev`

Frontend çalıştıktan sonra tarayıcıdan şu adrese gidin:

`http://localhost:3000`

Backend varsayılan olarak şu adreste çalışır:

`http://localhost:8080`

## 💻 Kullanım

1. Uygulamaya kayıt olun veya giriş yapın.
2. Ürün bilgilerini ekleyin ve yönetin.
3. Depo bilgilerini ekleyin ve yönetin.
4. Stok giriş ve stok çıkış hareketlerini kaydedin.
5. Mevcut stok durumunu takip edin.

## 📚 Bu Projede Kazanılan Deneyimler

Bu proje ile şu konularda pratik yapılmıştır:

- Next.js ve React ile frontend geliştirme
- Java Spring Boot ile backend geliştirme
- REST API yapısı oluşturma
- Frontend ve backend entegrasyonu
- PostgreSQL ile ilişkisel veritabanı kullanımı
- CRUD işlemleri geliştirme
- Kullanıcı giriş/kayıt süreçleri
- Postman ile API test etme
- GitHub üzerinde proje paylaşma

---

Bu proje, full-stack web geliştirme becerilerini göstermek amacıyla hazırlanmış stok takip uygulamasıdır.












