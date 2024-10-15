# Belajar Database SQLITE

Proyek ini bertujuan untuk mempelajari dasar-dasar penggunaan SQLite, sebuah database relasional yang ringan dan tertanam. Melalui proyek ini, kita akan belajar cara membuat database, tabel, memasukkan data, melakukan query, dan memanipulasi data menggunakan bahasa SQL.

## Prasyarat

* SQLite: Pastikan SQLite sudah terinstal di sistem operasi Anda. Anda bisa mengunduhnya dari situs resmi SQLite.
* Editor teks: Pilih editor teks favorit Anda, seperti Visual Studio Code, Sublime Text, atau Atom.
* Pengetahuan dasar SQL: Memahami konsep dasar SQL akan sangat membantu dalam mengikuti proyek ini.

## Struktur Proyek

```bash
proyek_sqlite/
├── chinook.db
├── script.sql
└── README.md
```

* chinook.db: File database SQLite yang akan kita gunakan.
* script.sql: File berisi script SQL untuk membuat tabel, memasukkan data, dan melakukan query.
* README.md: File ini, yang sedang Anda baca.

## Cara Menggunakan

### 1. Membuka database

```bash
sqlite3 chinook.db
```

### 2. Run Query

```bash
SELECT * FROM albums;
```

## Materi yang Dipelajari

* Membuat database dan tabel
* Memasukkan, membaca, memperbarui, dan menghapus data (CRUD)
* Menggunakan berbagai jenis data (teks, angka, tanggal)
* Membuat query sederhana dan kompleks
* Menggunakan fungsi agregasi (COUNT, SUM, AVG, dll)
* Membuat indeks untuk meningkatkan performa query

## Pengembangan Selanjutnya

* **Integrasi dengan bahasa pemrograman**: Pelajari cara mengakses SQLite dari bahasa pemrograman favorit Anda (Python, Java, C#, dll).
* **Proyek yang lebih kompleks**: Buat aplikasi sederhana yang menggunakan SQLite sebagai backend, seperti aplikasi todo list atau buku alamat.
* **Fitur SQLite lainnya**: Explore fitur-fitur SQLite yang lebih lanjut, seperti trigger, view, dan foreign key.

## Sumber Belajar

* [SQLITE TURORIAL](https://www.sqlitetutorial.net/sqlite-sample-database/)