# Doa Sahur & Buka Puasa

Website sederhana berbasis HTML dan Tailwind CSS yang menampilkan:

- Doa Sahur
- Doa Buka Puasa
- Dalil tentang puasa
- Tanggal otomatis (Masehi dan Hijriah)

Project ini dibuat sebagai latihan penggunaan struktur semantic HTML dan styling menggunakan Tailwind CDN.

---

## Fitur

- Struktur semantic: `header`, `main`, `section`, `article`, `footer`
- Responsive layout
- Animasi sederhana (fade-up)
- Font khusus untuk teks Arab (Amiri)
- Tanggal otomatis:
  - Format Indonesia (Masehi)
  - Kalender Islam (Hijriah)
- Tanpa backend
- Tanpa database
- Menggunakan Tailwind via CDN

---

## Teknologi yang Digunakan

- HTML5
- Tailwind CSS (CDN)
- Google Fonts
- JavaScript (untuk tanggal otomatis)

---

## Cara Menjalankan

1. Download atau clone project ini.
2. Pastikan file HTML berada dalam satu folder.
3. Buka file HTML langsung di browser (double click atau klik kanan → Open with browser).

Tidak perlu install apa pun karena menggunakan CDN.

---

## Struktur Utama

- Header → Judul dan tanggal otomatis
- Section Sahur → Niat puasa dan doa sebelum makan
- Section Buka → Doa berbuka dan doa setelah berbuka
- Section Dalil → QS. Al-Baqarah ayat 183
- Footer → Informasi pembuat

---

## Catatan

Tanggal Hijriah menggunakan `Intl.DateTimeFormat` dengan kalender Islam dari browser.  
Hasil bisa sedikit berbeda tergantung sistem dan lokasi pengguna.

---

Dibuat oleh: **Satria Farel**  
Tahun: 2026
