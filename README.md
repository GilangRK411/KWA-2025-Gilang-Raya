# OWASP Juice Shop – Exploitation Walkthrough

## Persiapan
1. Buka aplikasi:  
   [https://juice-shop.herokuapp.com/#/login](https://juice-shop.herokuapp.com/#/login)

2. Login:  
   - **Email**: bebas  
   - **Password**: bebas  

---

## Langkah Eksploitasi

### 1. Login
Masuk ke halaman login dengan kredensial acak.

### 2. Cari Produk
Gunakan fitur pencarian → ketik **Apple Juice** → buka produk tersebut.

### 3. Buka Review
Masuk ke tab **Reviews** pada produk Apple Juice.  
Di sini muncul **kredensial admin**.

### 4. Catat Kredensial
Salin email dan password admin yang muncul di review, lalu gunakan untuk login sebagai admin.

---
## Hasil
- Berhasil mendapatkan **kredensial admin** melalui fitur review produk.  
- Kerentanan ini menunjukkan adanya **information disclosure**.
---

## Referensi
- [OWASP Juice Shop Project](https://owasp.org/www-project-juice-shop/)  
- [Juice Shop GitHub](https://github.com/juice-shop/juice-shop)  
