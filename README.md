# SIAP LAPOR (versi awal)

> Sistem pelaporan dan pengaduan internal Instalasi SIMRS RSUD Mohammad Natsir Solok, ditulis dengan PHP native. **Sudah digantikan oleh [SIAP LAPOR v2](https://github.com/izanmaizan/lapor-v2-docs)** (Laravel 13), yang membawa seluruh fitur versi ini plus peta 3D perangkat, gudang, dan notifikasi real-time.

| | |
|---|---|
| Instansi | RSUD Mohammad Natsir Solok, Instalasi SIMRS |
| Peran saya | Desain dan pengembangan end-to-end: arsitektur, logika bisnis, integrasi database |
| Status | Digantikan SIAP LAPOR v2; data lama dimigrasikan |

## Fitur

- Form laporan kendala perangkat, jaringan, dan aplikasi dari unit/ruangan.
- Penugasan ke teknisi dan pencatatan tindak lanjut.
- Kartu perbaikan dan riwayat laporan per ruangan.
- Rekap bulanan untuk laporan kinerja instalasi.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Aplikasi | PHP native, JavaScript, Bootstrap |
| Data | MySQL |

## Kenapa ditulis ulang

Versi awal dibuat cepat dengan dependensi minimal. Seiring bertambahnya kebutuhan (inventaris perangkat, gudang, LAKIP, notifikasi real-time, peran dan izin), aplikasi dipindahkan ke Laravel agar lebih mudah diuji dan dirawat. Proses migrasi memakai uji paralel dan cutover bertahap.

---

> **Catatan kerahasiaan.** Kode sumber aplikasi ini private karena milik/dipakai instansi. Repo ini hanya menjelaskan konteks, fitur, arsitektur, dan peran saya. Tidak ada kode, data pegawai, data pasien, alamat server, maupun kredensial di sini.

**Maizan Insani Akbar** · Software Engineer & System Analyst · [Portfolio](https://izanmaizan.vercel.app) · [LinkedIn](https://www.linkedin.com/in/izanmaizan/) · [GitHub](https://github.com/izanmaizan)
