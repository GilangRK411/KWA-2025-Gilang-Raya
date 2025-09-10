# OWASP Juice Shop – Exploitation Walkthrough

## Persiapan
1. Buka aplikasi:  
   [https://juice-shop.herokuapp.com/#/login](https://juice-shop.herokuapp.com/#/login)

2. Login:
<img width="1920" height="1080" alt="Screenshot (688)" src="https://github.com/user-attachments/assets/599a6dfc-b4b0-4336-a798-61be7b68abbd" />
  
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
<img width="1919" height="1079" alt="Screenshot 2025-09-10 212220" src="https://github.com/user-attachments/assets/e51fa927-6855-460d-b2d2-85c293b127f2" />


### 4. Catat Kredensial
Salin email dan password admin yang muncul di review, lalu gunakan untuk login sebagai admin.

---
## Hasil
- Berhasil mendapatkan **kredensial admin** melalui fitur review produk.  
- Kerentanan ini menunjukkan adanya **information disclosure**.

---
