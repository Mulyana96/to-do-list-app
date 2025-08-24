# 📋 Aplikasi To-Do List

Aplikasi sederhana berbasis web untuk mencatat dan mengelola kegiatan sehari-hari.  
Dibuat dengan teknologi **HTML, Bootstrap, dan JavaScript** sehingga **responsif** dan bisa dibuka di device manapun.

---

## 📂 Struktur Aplikasi
todo-list-app/
│
├── index.html # Halaman utama aplikasi (UI + script utama)
├── style.css # (Opsional) File CSS tambahan untuk styling custom
├── script.js # (Opsional) File JavaScript terpisah untuk logika aplikasi
├── todo.json # File hasil backup (export/import JSON)
└── package.json # Konfigurasi project (identitas, script npm, dll)

---

## 🛠 Teknologi yang Digunakan

1. **HTML5**  
   - Membuat struktur dasar halaman web (form input, list, tombol, dll).

2. **Bootstrap 5 (via CDN)**  
   - Framework CSS untuk desain responsif.  
   - Digunakan untuk grid system, tombol, list-group, dan layout yang mobile-friendly.

3. **JavaScript (Vanilla/Native)**  
   - Logika utama aplikasi (tambah task, hapus task, animasi, backup & import JSON).  
   - Tidak menggunakan framework tambahan agar tetap ringan.

4. **JSON (JavaScript Object Notation)**  
   - Format untuk **backup & import** daftar kegiatan (`todo.json`).  
   - Memudahkan menyimpan dan memuat ulang data.

5. **(Opsional) Node.js + npm**  
   - Untuk manajemen project dengan `package.json`.  
   - Bisa digunakan jika ingin menambahkan **server lokal** (misalnya dengan `live-server` atau `serve`).

---

## 🚀 Fitur Utama

- Tambah kegiatan baru.  
- Hapus kegiatan dengan tombol merah.  
- Animasi timbul saat hover.  
- Backup daftar kegiatan ke file **todo.json**.  
- Import kembali data dari file **todo.json**.  
- Footer informasi pembuat.  
- Desain **responsif** di semua device.

---
## 👨‍💻 Pembuat

**Mulyana**


