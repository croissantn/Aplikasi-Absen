## 📘 Aplikasi Absensi

### 📌 Deskripsi Singkat

Aplikasi ini digunakan untuk mencatat kehadiran pengguna (siswa) dengan status **Hadir**, **Izin**, **Sakit**, atau **Alpha**. Sistem memiliki tiga level pengguna: **Siswa**, **Guru**, dan **Admin**, yang masing-masing memiliki peran dan fungsi berbeda.

---

### 🛠️ Cara Kerja Aplikasi

1. **User membuka aplikasi dan login.**
2. Sistem akan mengecek role pengguna:

   * Jika **Siswa**, diarahkan ke halaman absensi.
   * Jika **Guru**, diarahkan ke halaman verifikasi absensi.
   * Jika **Admin**, diarahkan ke dashboard pengelolaan data.
3. Aksi yang dilakukan sesuai dengan role masing-masing.
4. Semua data absensi akan tersimpan ke dalam database dan bisa direkap oleh admin.

---

### 👥 Role & Fungsi Masing-masing User

#### 1. 👨‍🎓 Siswa

* **Fungsi:**

  * Melakukan pengisian absensi setiap hari.
  * Memilih salah satu status kehadiran: **Hadir**, **Izin**, **Sakit**, atau **Alpha**.
* **Proses:**

  * Login ke aplikasi.
  * Akses halaman absensi.
  * Pilih status kehadiran.
  * Kirim absensi.

#### 2. 👨‍🏫 Guru

* **Fungsi:**

  * Melihat absensi siswa berdasarkan kelas dan tanggal.
  * Melakukan verifikasi atau perubahan data absensi (jika perlu).
* **Proses:**

  * Login sebagai guru.
  * Pilih kelas dan tanggal.
  * Lihat rekap absensi siswa.
  * Verifikasi atau koreksi jika diperlukan.

#### 3. 🛠️ Admin

* **Fungsi:**

  * Mengelola data pengguna (siswa dan guru).
  * Mengatur data kelas dan jadwal.
  * Melihat rekapitulasi data absensi (harian/bulanan).
  * Ekspor data absensi (opsional: PDF/Excel).
* **Proses:**

  * Login sebagai admin.
  * Akses dashboard admin.
  * Kelola pengguna dan kelas.
  * Lihat dan ekspor rekap absensi.

---

