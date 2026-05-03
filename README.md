# laporanstudynotes
## Richie Pranata 
## 312410451

# 🚀 Progress Pengembangan Aplikasi Study Notes

## 📌 Overview

Aplikasi **Study Notes** adalah aplikasi Android yang dikembangkan untuk membantu pengguna dalam mencatat dan mengelola materi pembelajaran secara lebih terstruktur. Dalam proses pengembangannya, berbagai fitur telah berhasil dibuat dan ditingkatkan secara bertahap.

---

## 🛠️ Fitur yang Telah Dikerjakan

### 📝 1. Sistem Manajemen Catatan

Fitur utama aplikasi adalah pengelolaan catatan, meliputi:

* Menambahkan catatan baru
* Menampilkan daftar catatan
* Mengedit catatan
* Menghapus catatan

📍 Implementasi:

* Menggunakan **SQLite Database**
* Data disimpan secara lokal di perangkat
* Menggunakan **RecyclerView** untuk menampilkan daftar catatan

---

### 💾 2. Database SQLite

Database digunakan untuk menyimpan seluruh data catatan.

Struktur tabel:

* `id` → Primary Key
* `title` → Judul catatan
* `category` → Kategori
* `content` → Isi catatan
* `date` → Tanggal

📍 Fitur database:

* Insert data
* Read data
* Update data
* Delete data (CRUD)

---

### 📱 3. Tampilan Home (RecyclerView)

Halaman utama menampilkan daftar catatan yang sudah dibuat.

📍 Fitur:

* Data ditampilkan secara dinamis
* Otomatis refresh saat kembali ke halaman
* Menggunakan Adapter (NoteAdapter)

---

### ✏️ 4. Detail Catatan (Edit & Auto Save)

Pengguna dapat melihat dan mengedit isi catatan.

📍 Fitur:

* Edit judul dan isi catatan
* Auto save saat mengetik (tanpa tombol)
* Keyboard otomatis muncul saat membuka catatan

---

### 🤖 5. AI Study Assistant (Fitur Utama Tambahan)

Aplikasi telah dikembangkan dengan fitur AI sederhana untuk membantu proses belajar.

#### 📌 a. Rekomendasi Belajar

Memberikan saran berdasarkan kategori catatan.

Contoh:

* Matematika → latihan rumus
* Pemrograman → latihan coding

---

#### 📌 b. Ringkasan Otomatis

AI dapat meringkas isi catatan menjadi lebih singkat.

---

#### 📌 c. Quiz Otomatis

AI memberikan soal latihan berdasarkan kategori.

Contoh:

* Matematika → soal hitungan
* Sejarah → pertanyaan tokoh

---

### 💬 6. AI Chat (Fitur Interaktif)

Telah ditambahkan fitur AI Chat seperti chatbot sederhana.

📍 Kemampuan AI:

* Menjawab pertanyaan umum
* Memberikan tips belajar
* Menjawab pertanyaan pemrograman
* Menyelesaikan soal matematika otomatis

Contoh:

* Input: `12 x 5` → Output: `60`
* Input: `cara belajar` → Output: tips belajar

---

### 🧠 7. AI Logic (Rule-Based System)

AI bekerja menggunakan metode:

* Pencocokan kata kunci (keyword matching)
* Regex untuk matematika
* Respon otomatis berdasarkan kondisi

---

### 🔄 8. Auto Refresh Data

Data akan otomatis diperbarui ketika:

* Menambah catatan
* Mengedit catatan
* Kembali ke halaman utama

---

### 🎨 9. UI/UX Sederhana

Desain aplikasi dibuat:

* Minimalis
* Mudah digunakan
* Fokus pada fungsi utama

---

## 🔧 Pengembangan Tambahan yang Dilakukan

Selama proses pengerjaan, beberapa perbaikan telah dilakukan:

* Perbaikan error pada Adapter
* Perbaikan error pada AI Helper
* Penyesuaian nama class dan file
* Penambahan Activity AI Chat
* Penambahan permission Internet di Manifest
* Perbaikan crash saat membuka AI

---

## ⚠️ Kendala yang Dihadapi

Beberapa kendala selama pengembangan:

* Error pada penamaan class (AIHelper vs BotHelper)
* Crash saat membuka halaman AI
* Resource drawable belum tersedia
* Adapter tidak sinkron dengan layout
* AI tidak merespon karena method belum dipanggil

---

## ✅ Solusi yang Dilakukan

* Menyamakan nama file dan class
* Menambahkan activity di Manifest
* Membuat layout XML yang sesuai
* Memperbaiki pemanggilan method AI
* Menambahkan validasi input

---

## 📊 Hasil Akhir

Aplikasi berhasil:

* Menyimpan dan mengelola catatan
* Menampilkan data secara dinamis
* Memberikan fitur AI sederhana
* Menyediakan chatbot interaktif

---

## 📌 Kesimpulan

Pengembangan aplikasi Study Notes telah berhasil dilakukan dengan menambahkan berbagai fitur utama seperti manajemen catatan dan AI Assistant. Aplikasi ini tidak hanya berfungsi sebagai alat pencatatan, tetapi juga sebagai media pembelajaran interaktif yang membantu pengguna dalam memahami materi.

---
