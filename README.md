# 📦 Stok Takip Sistemi

İşletmelerin ürün stoklarını, depolarını ve stok hareketlerini takip etmesini sağlayan fullstack web uygulaması.

## 🎯 Proje Amacı

Bu proje, stok yönetimini kolaylaştırmak için geliştirilmiştir:
- ✅ Ürün ve depo stok CRUD işlemleri
- ✅ Stok giriş/çıkış kayıtları
- ✅ Anlık stok durum takibi
- ✅ Kullanıcı kimlik doğrulama

---

## 🛠️ Teknolojiler

**Frontend:** Next.js 14, React, Tailwind CSS  
**Backend:** Spring Boot, PostgreSQL  
**IDE:** IntelliJ IDEA (Backend), VSCode (Frontend)

---

## 🚀 Kurulum ve Çalıştırma

### 1️⃣ PostgreSQL Veritabanı Kurulumu

```sql
-- PostgreSQL'e bağlanın (psql -U postgres)
CREATE DATABASE stock_tracking;
```

### 2️⃣ Backend (IntelliJ IDEA)

1. **IntelliJ IDEA'yı açın**
2. **File → Open → `backend/stockTracking`** klasörünü seçin
3. **`src/main/resources/application.properties`** dosyasını düzenleyin:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/stock_tracking
spring.datasource.username=postgres
spring.datasource.password=POSTGRESQL_SIFRENIZ
spring.jpa.hibernate.ddl-auto=update
server.port=8080
```

4. **`StockTrackingApplication.java`** dosyasına sağ tıklayın → **Run**
5. ✅ Backend çalıştı: **http://localhost:8080**

### 3️⃣ Frontend (VSCode)

```bash
# Frontend klasörüne gidin
cd aa

# Bağımlılıkları yükleyin
npm install

# Uygulamayı başlatın
npm run dev
```

✅ Frontend çalıştı: **http://localhost:3000**

---

## 💻 Kullanım

1. Tarayıcıda **http://localhost:3000** adresine gidin
2. Kayıt olun ve giriş yapın
3. Sol menüden **Depo**, **Ürün**, **Stok Hareketi** ve **Stok Durum** sayfalarını kullanın

---

## 📝 Proje Yapısı

```
stock/
├── aa/                      # Frontend (Next.js)
│   ├── app/components/      # React bileşenleri
│   └── package.json
│
└── backend/stockTracking/   # Backend (Spring Boot)
    ├── src/main/java/
    ├── pom.xml
    └── application.properties
```

---


**Zeynep Topçu** - [@zeyneptopcu06](https://github.com/zeyneptopcu06)

⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!
