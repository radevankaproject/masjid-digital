# Changelog

Semua perubahan penting pada project **Masjid Digital by RadevankaProject** akan didokumentasikan di file ini.

## [v1.0.2] - 2026-08-27

### Ditambahkan

- Menambahkan file `.env.example` untuk mempermudah setup environment.
- Menambahkan dokumentasi lengkap pada `README.md`.
- Mengimplementasikan dukungan aset lokal/offline (Offline CDN).

### Diubah

- Mengoptimasi kode dengan membersihkan _duplicated query_ (N+1 query problem) untuk performa yang lebih baik.
- Memperbarui `DatabaseSeeder` terkait konfigurasi `ThemeColor` default.
- Memperbaiki bug z-index pada loading modal dan error modal jadwal sholat agar tampil sempurna menutupi halaman.
- Menambahkan _Additional Terms_ pada lisensi untuk atribusi kepemilikan dan kolaborasi.
- _Finishing touches_ dan stabilisasi sistem.

## [v1.0.1] - 2026-02-17

### Diubah

- Pembaruan minor, perbaikan bug kecil, dan stabilisasi fitur dari versi perdana.

## [v1.0.0] - 2026-02-13

### Ditambahkan

- Rilis perdana (Initial Release) aplikasi Masjid Digital.
- Fitur sinkronisasi Jadwal Sholat (API MyQuran / Kemenag RI).
- Panel Administrator untuk manajemen Masjid, pengaturan dasar, jadwal, dan operasional.
