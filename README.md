# Aplikasi Peminjaman Kendaraan & Ruangan

Aplikasi web untuk mengelola peminjaman kendaraan dan ruangan instansi, mencakup pengajuan peminjaman, persetujuan admin, pencatatan otomatis tanggal peminjaman/pengembalian, hingga penerbitan Berita Acara digital.

**Instansi:** BPK Perwakilan DIY (Magang — Data Visualisasi / Data Analyst Support)
**Peran saya:** System Analyst — merancang alur sistem, struktur peran pengguna, dan menyusun buku panduan penggunaan aplikasi

> ⚠️ **Catatan Keamanan**
> Aplikasi ini telah ditanam di server internal instansi dan kemungkinan masih aktif digunakan. Oleh karena itu, **kredensial login, data pribadi pegawai (nama & NIP), dan dokumen Berita Acara asli tidak ditampilkan** di repositori ini. Hanya alur kerja dan tampilan antarmuka umum yang didokumentasikan.

---

## Peran Saya sebagai System Analyst

- Merancang alur sistem multi-role: **User (Pegawai)**, **Admin Kendaraan**, **Admin Ruangan**, dan **Super Admin**
- Menentukan struktur navigasi dan hak akses tiap peran
- Merancang alur persetujuan peminjaman & pengembalian (pengajuan → menunggu persetujuan → disetujui/ditolak → Berita Acara otomatis)
- Menyusun buku panduan penggunaan aplikasi secara lengkap untuk seluruh peran pengguna

---

## Ringkasan Alur Sistem

**Sisi User (Pegawai):**
1. Registrasi & login akun
2. Memilih modul Peminjaman Ruangan atau Peminjaman Kendaraan
3. Melihat katalog & detail unit yang tersedia
4. Mengisi form peminjaman (tanggal pinjam, tanggal kembali)
5. Menunggu persetujuan admin terkait
6. Menerima notifikasi hasil persetujuan
7. Mengajukan pengembalian setelah selesai digunakan

**Sisi Admin Kendaraan / Admin Ruangan:**
- Dashboard ringkasan (total unit, unit dipinjam, unit tersedia)
- Grafik tren peminjaman mingguan & bulanan
- Persetujuan/penolakan permintaan peminjaman & pengembalian
- Kelola data unit (tambah/edit/hapus kendaraan atau ruangan)
- Laporan mingguan & bulanan (dapat diunduh sebagai CSV)

**Sisi Super Admin:**
- Dashboard menyeluruh (total user, total ruangan, total kendaraan, total peminjaman)
- Kelola data user & hak akses (role)
- Akses cepat ke dashboard Admin Ruangan & Admin Kendaraan
- Melihat seluruh riwayat peminjaman lintas kategori

---

## Tampilan Aplikasi

### Alur User (Pegawai)

| Login | Register |
|---|---|
| ![Login](images/01-login-kosong.jpg) | ![Register](images/02-register-kosong.jpg) |

| Menu Peminjaman Ruangan | Menu Peminjaman Kendaraan |
|---|---|
| ![Home Ruangan](images/03-home-card-ruangan.jpg) | ![Home Kendaraan](images/04-home-card-kendaraan.jpg) |

![Katalog Kendaraan](images/05-katalog-kendaraan.jpg)
*Katalog kendaraan yang tersedia untuk dipinjam.*

| Detail Kendaraan | Form Peminjaman Kendaraan |
|---|---|
| ![Detail Kendaraan](images/06-detail-kendaraan.jpg) | ![Form Kendaraan](images/07-form-peminjaman-kendaraan.jpg) |

![Katalog Ruangan](images/08-katalog-ruangan.jpg)
*Katalog ruangan yang tersedia untuk dipinjam.*

| Detail Ruangan | Form Peminjaman Ruangan |
|---|---|
| ![Detail Ruangan](images/09-detail-ruangan.jpg) | ![Form Ruangan](images/10-form-peminjaman-ruangan.jpg) |

### Alur Admin

![Statistik Kendaraan](images/11-stat-kendaraan.jpg)
*Ringkasan total kendaraan, sedang dipinjam, dan tersedia.*

![Grafik Tren Peminjaman](images/12-grafik-tren-kendaraan.jpg)
*Tren peminjaman kendaraan per minggu dan per bulan.*

![Tabel Kelola Kendaraan](images/13-tabel-kendaraan.jpg)
*Kelola data inventaris kendaraan (bukan data pengguna).*

![Dashboard Super Admin](images/14-superadmin-stats.jpg)
*Ringkasan menyeluruh: total user, ruangan, kendaraan, dan peminjaman.*

---

## Insight & Pembelajaran

Melalui proyek ini saya belajar merancang sistem dengan banyak peran pengguna sekaligus (4 role berbeda dengan hak akses masing-masing), termasuk alur persetujuan bertingkat dan penerbitan dokumen otomatis (Berita Acara). Saya juga belajar pentingnya menjaga keamanan data saat sebuah aplikasi internal instansi didokumentasikan untuk kebutuhan di luar organisasi.

---

## Kontak
Synthia Wulandari — [Synthiawln@gmail.com](mailto:Synthiawln@gmail.com) · [LinkedIn](https://linkedin.com/in/synthia-wln)
