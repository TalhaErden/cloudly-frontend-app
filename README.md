# Cloudly Software Case Study - Talha Erden

Bu repository, Cloudly Software teknik değerlendirmesi kapsamında hazırlanan Backend ve Frontend projelerini içerir.

## Proje Yapısı

Bu repo iki ana bölümden oluşmaktadır:

1.  **cloudly-backend:** NestJS ile geliştirilmiş, Clean Architecture prensiplerine sahip Multi-Tenant Proje Yönetim API'si.
2.  **cloudly-frontend:** Next.js ile geliştirilmiş, DummyJSON API kullanan, sürükle-bırak destekli Analitik Dashboard.

---

## 🚀 1. Backend (NestJS) Kurulum ve Çalıştırma

Backend projesi, "Task Move Challenge" ve Swagger dökümantasyonunu içerir.

1.  Terminalde backend klasörüne gidin:
    ```bash
    cd cloudly-backend
    ```

2.  Bağımlılıkları yükleyin ve projeyi başlatın:
    ```bash
    npm install
    npm run start:dev
    ```

* **API URL:** `http://localhost:3000`
* **Swagger UI:** `http://localhost:3000/api` (Tüm endpoint'leri buradan test edebilirsiniz)

---

## 🎨 2. Frontend (Next.js) Kurulum ve Çalıştırma

Frontend projesi, Zustand state yönetimi ve Drag & Drop widget yapısını içerir.

1.  Yeni bir terminalde frontend klasörüne gidin:
    ```bash
    cd cloudly-frontend
    ```

2.  Bağımlılıkları yükleyin ve projeyi başlatın:
    ```bash
    npm install
    npm run dev
    ```

* **Uygulama URL:** `http://localhost:3001` (veya 3000 portu doluysa terminalde belirtilen port)

---

## 🛠 Kullanılan Teknolojiler

* **Backend:** NestJS, TypeScript, TypeORM, SQLite, Swagger, Class-Validator
* **Frontend:** Next.js (App Router), Tailwind CSS, Zustand, dnd-kit (Drag & Drop), Recharts

---

## ✅ Tamamlanan Challenge'lar

* [x] **Backend:** Farklı organizasyonlar arası görev taşıma engeli (Security Logic).
* [x] **Backend:** Adım adım Git commit geçmişi.
* [x] **Frontend:** Polymorphic Widget yapısı (Chart, Table, Stat).
* [x] **Frontend:** Global Filtreleme (Kategori bazlı).
* [x] **Frontend:** Sayfa yenilendiğinde widget sıralamasının korunması (LocalStorage).
