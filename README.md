# SembadaRooms 🌟

SembadaRooms adalah aplikasi manajemen dan pemesanan hotel berbasis web yang terdiri dari backend (API), frontend admin, dan frontend customer. Project ini dirancang untuk memudahkan proses reservasi kamar hotel, pengelolaan data hotel, serta monitoring aktivitas pemesanan secara efisien.

## 🏗️ Struktur Project

- **backend/**: API berbasis Node.js, Express, dan Sequelize untuk mengelola data hotel, kamar, tipe kamar, user, customer, pemesanan, dan detail pemesanan.
- **frontend-admin/**: Frontend React untuk admin & resepsionis hotel, menyediakan fitur manajemen data dan monitoring pemesanan.
- **frontend-customer/**: Frontend React untuk customer, menyediakan fitur pencarian, pemesanan kamar, dan riwayat pemesanan.

## ✨ Fitur Utama

### Backend
- REST API untuk seluruh kebutuhan data hotel
- Autentikasi & otorisasi (JWT)
- Manajemen user (admin & resepsionis)
- Manajemen kamar, tipe kamar, customer, pemesanan, detail pemesanan
- Filter ketersediaan kamar berdasarkan tanggal

### Frontend Admin
- Login admin & resepsionis
- Dashboard monitoring data
- Manajemen data kamar, tipe kamar, user
- Monitoring & update status pemesanan

### Frontend Customer
- Registrasi & login customer
- Pencarian & filter kamar
- Pemesanan kamar online
- Riwayat & detail pemesanan

## ▶️ Cara Menjalankan

1. **Clone repository**
2. **Install dependencies** di masing-masing folder (`backend`, `frontend-admin`, `frontend-customer`)
3. **Jalankan backend**
   ```bash
   cd backend
   npm install
   npm start
   ```
4. **Jalankan frontend-admin**
   ```bash
   cd frontend-admin
   npm install
   npm run dev
   ```
5. **Jalankan frontend-customer**
   ```bash
   cd frontend-customer
   npm install
   npm run dev
   ```

## 🛠️ Teknologi
- Node.js, Express, Sequelize, MySQL
- React, Vite, Tailwind CSS

## 📝 Catatan
- Pastikan environment database sudah dikonfigurasi di `backend/config/config.json`
- Port default backend: 8081
- Frontend berjalan di port Vite (biasanya 5173/5174)

---

## 📄 Lisensi
Project ini belum memiliki lisensi open source. Jika ingin menggunakan, silakan tambahkan file LICENSE sesuai kebutuhan (misal: MIT, GPL, dsb).

---

**SembadaRooms** dikembangkan untuk kebutuhan digitalisasi hotel modern, dengan fitur lengkap dan mudah digunakan baik untuk admin maupun customer.
