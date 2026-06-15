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

*  GenerateKode Method
  <img width="328" height="170" alt="SS01_GenerateKode_Method" src="https://github.com/user-attachments/assets/e051f904-b427-4923-823f-47774ed56ee3" />

*  Create Controller
  <img width="373" height="256" alt="SS02_Create_Controller" src="https://github.com/user-attachments/assets/fce29de9-4d8a-4d2d-94b7-674330672b9c" />

*  Form Create Kode Otomatis
  <img width="419" height="161" alt="SS03_Form_Create_KodeOtomatis" src="https://github.com/user-attachments/assets/6c8cd70c-7070-4f11-8d2e-782bd5230409" />

*  Hasil Kode Anggota
  <img width="421" height="271" alt="SS04_Hasil_Kode_Anggota" src="https://github.com/user-attachments/assets/6e684e08-c1a7-4f54-a3a2-82865bd44486" />

---

# Tugas 2 - Export Data Anggota ke Excel

Implementasi menggunakan package Laravel Excel (maatwebsite/excel).

Fitur:

* Export seluruh data anggota ke file Excel (.xlsx)
* Nama file otomatis berdasarkan tanggal dan waktu export
* Menggunakan class AnggotaExport

Dokumentasi:

*  Install Package
  <img width="827" height="437" alt="SS06_Install_Maatwebsite_Excel" src="https://github.com/user-attachments/assets/6f6d20fc-168f-4c79-9c8c-0c10781293e9" />

*  AnggotaExport Class
  <img width="822" height="371" alt="SS07_AnggotaExport_Class" src="https://github.com/user-attachments/assets/6f468882-3d71-40c1-a975-28739116b0cb" />

*  Controller Export Method
  <img width="380" height="52" alt="SS08_Controller_Export_Method" src="https://github.com/user-attachments/assets/c1b3c0fd-f3e9-4224-8c2d-9ade6ce67606" />

*  Route Export
  <img width="304" height="29" alt="SS09_Route_Export" src="https://github.com/user-attachments/assets/9d9e919e-bf42-47b4-ab80-d5c80803099b" />

*  Button Export
  <img width="245" height="65" alt="SS10_Button_Export" src="https://github.com/user-attachments/assets/2cc41cc2-8c2b-4819-819f-7a7408ac79a8" />

*  Halaman Daftar Anggota
  <img width="539" height="306" alt="SS11_Halaman_DaftarAnggota" src="https://github.com/user-attachments/assets/4ac16735-7dbe-481f-b36e-349462ea8dde" />

*  Hasil File Excel
  <img width="272" height="143" alt="SS12_Hasil_File_Excel 1" src="https://github.com/user-attachments/assets/40bdd169-460d-441b-872d-cc1ba17a0899" />
  <img width="607" height="115" alt="SS12_Hasil_File_Excel 2" src="https://github.com/user-attachments/assets/fb579156-da76-45f5-9ad4-24de7e1bf584" />

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

*  Route Search
  <img width="284" height="32" alt="SS13_Route_Search" src="https://github.com/user-attachments/assets/7678ca26-90c8-4151-85e3-de37e622b518" />

*  Controller Search
  <img width="360" height="320" alt="SS14_Controller_Search" src="https://github.com/user-attachments/assets/ee34cf64-a4f1-4b86-b4e1-b869fcfa84cd" />

*  Form Search Filter
  <img width="332" height="363" alt="SS15_Form_Search_Filter" src="https://github.com/user-attachments/assets/3b5ebad9-3fb0-4d6f-98de-c58d42ffde65" />

*  Tampilan Search Filter
  <img width="510" height="53" alt="SS16_Tampilan_Search_Filter" src="https://github.com/user-attachments/assets/7801ba3d-47a8-4537-8e71-ebe7e33ddcd1" />
  <img width="553" height="272" alt="SS17_Search_Keyword" src="https://github.com/user-attachments/assets/6f0a1615-dfca-40d7-9156-075b2124408b" />

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
