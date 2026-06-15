# Tugas Pemrograman Web 2 - Pertemuan 13

## Identitas Mahasiswa

* Nama : Dwinta Vivian Acintya Syahda
* NIM : 60324053
* Mata Kuliah : Pemrograman Web 2
* Pertemuan : 13

---

# Deskripsi Tugas

Pada pertemuan 13 dilakukan pengembangan modul Anggota pada Sistem Perpustakaan berbasis Laravel.

Terdapat tiga tugas utama yang dikerjakan:

1. Auto Generate Kode Anggota
2. Export Data Anggota ke Excel
3. Advanced Search & Filter Anggota

---

# Tugas 1 - Auto Generate Kode Anggota

Format kode anggota:

AGT-[TAHUN]-[NOMOR_URUT]

Contoh:

AGT-2026-001
AGT-2026-002
AGT-2026-003

Implementasi dilakukan menggunakan helper function generateKodeAnggota() pada AnggotaController.

Fitur:

* Nomor anggota dibuat otomatis
* Nomor urut bertambah secara otomatis
* Mengikuti tahun pembuatan data

Dokumentasi:

* SS01 GenerateKode Method
* SS02 Create Controller
* SS03 Form Create Kode Otomatis
* SS04 Hasil Kode Anggota
* SS05 Data Anggota Tersimpan

---

# Tugas 2 - Export Data Anggota ke Excel

Implementasi menggunakan package Laravel Excel (maatwebsite/excel).

Fitur:

* Export seluruh data anggota ke file Excel (.xlsx)
* Nama file otomatis berdasarkan tanggal dan waktu export
* Menggunakan class AnggotaExport

Dokumentasi:

* SS06 Install Package
* SS07 AnggotaExport Class
* SS08 Controller Export Method
* SS09 Route Export
* SS10 Button Export
* SS11 Halaman Daftar Anggota
* SS12 Hasil File Excel

---

# Tugas 3 - Advanced Search & Filter

Fitur pencarian dan filter anggota berdasarkan beberapa kriteria.

Fitur:

* Search nama anggota
* Search email anggota
* Search nomor telepon
* Filter jenis kelamin
* Filter status anggota
* Filter pekerjaan
* Reset filter

Dokumentasi:

* SS13 Route Search
* SS14 Controller Search
* SS15 Form Search Filter
* SS16 Tampilan Search Filter
* SS17 Search Keyword
* SS18 Filter Jenis Kelamin
* SS19 Filter Status
* SS20 Hasil Kombinasi Filter

---

# Teknologi yang Digunakan

* Laravel 12
* PHP 8.1
* MySQL
* Bootstrap 5
* Laravel Excel (maatwebsite/excel)

---

# Kesimpulan

Seluruh tugas pada Pertemuan 13 berhasil diimplementasikan dengan baik. Sistem mampu menghasilkan kode anggota secara otomatis, melakukan export data anggota ke format Excel, serta menyediakan fitur pencarian dan filter data anggota yang lebih fleksibel.
