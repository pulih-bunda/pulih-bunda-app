# Pulih Bunda

> Pendampingan ibu pasca melahirkan dan suami sebagai pendamping.

Aplikasi mobile Flutter yang membantu ibu baru dan suami pendamping mendapatkan informasi kesehatan yang terstruktur dan dapat dipercaya, mencatat kondisi emosional, serta memantau tumbuh kembang dan imunisasi bayi.

Proyek kelompok mata kuliah **CIE516 — Perancangan Aplikasi Mobile** (Semester Ganjil 2026/2027). Dosen pengampu: Ary Prabowo, S.Komp., M.Kom.

## Anggota Kelompok 4

|Nama|Peran|
|-|-|
||Front-End (FE)|
|Dwi Ahmad Maulana|UI/UX|
|Lucas Gabriel Mahatan|Integration Developer|
||Project Manager (PM)|
|Muhammad Riyan Hardiono|UI/UX|

## Latar Belakang

Ibu pasca melahirkan sering merasa cemas dan tidak percaya diri karena sulit menemukan informasi kesehatan yang tepat, sehingga hanya bisa bercerita kepada pasangan. Informasi tentang perawatan bayi, menyusui, imunisasi, dan tumbuh kembang biasanya didapat acak dari media sosial dan sering saling bertentangan.

**Pengguna sasaran:** ibu baru (persona: Ibu Wiwi, 27 tahun, anak pertama) dan suami sebagai pendamping.

**Temuan wawancara** (kualitatif, 2 ibu pasca melahirkan dan 1 suami pendamping):

1. Isu emosional dan baby blues: fluktuasi hormon, cemas mengurus bayi, takut dinilai kurang sempurna.
2. Informasi tumbuh kembang dan stimulasi sulit didapat, sehingga dibutuhkan satu platform terstruktur.
3. Suami kurang memahami perannya dan membutuhkan panduan praktis perawatan ibu dan anak.

## Fitur

|Modul|Kebutuhan pengguna|Tanda berhasil|
|-|-|-|
|Edukasi Kesehatan Ibu dan Pencegahan Baby Blues|Modul edukasi kesehatan dan jurnal mood harian|Ibu dapat mengakses modul kesehatan pascamelahirkan dan jurnal mood harian|
|Panduan Stimulasi, Imunisasi dan Tumbuh Kembang|Panduan stimulasi sesuai usia dan pengingat jadwal imunisasi|Pengguna menerima notifikasi imunisasi dan berhasil mencatat milestone stimulasi|
|Modul Pendampingan Khusus Suami|Akses cepat ke panduan "Pertolongan Pertama Bayi Rewel" dan cara mendampingi emosi istri|Suami dapat membuka halaman "Pertolongan Pertama Bayi Rewel" dalam 1 klik|

## Batasan Aplikasi

Aplikasi ini **tidak** menyediakan layanan diagnosis medis langsung atau konsultasi darurat, dan tidak menggantikan peran bidan maupun dokter spesialis.

## Risiko

* **Tantangan terbesar:** menjangkau cukup banyak ibu pasca melahirkan dan suami sebagai pengguna aktif untuk uji coba, karena target ini sulit didekati dan topiknya personal.
* **Mitigasi:** bekerja sama dengan puskesmas atau posyandu.
* **Risiko lanjutan:** proses izin dan jadwal kerja sama bisa molor dari perkiraan.

## Teknologi

* Flutter (Dart)
* Target utama: Android

## Struktur Repositori

```
lib/     kode sumber aplikasi (Dart)
test/    pengujian
docs/    dokumentasi dan catatan kontribusi anggota
android/ ios/ web/ ...   berkas platform bawaan Flutter
```

## Memulai

Prasyarat: Flutter SDK, Android Studio atau VS Code, dan Git. Pastikan `flutter doctor` tidak menampilkan error pada bagian Flutter dan Android toolchain.

```bash
git clone https://github.com/pulih-bunda/pulih-bunda-app.git
cd pulih-bunda-app
flutter pub get
flutter run
```

Pilih emulator Android atau HP Android dengan USB debugging aktif sebagai perangkat.

## Cara Berkontribusi

1. Jalankan `git pull` sebelum mulai bekerja dan sebelum push.
2. Pastikan `git config user.name` dan `git config user.email` sesuai akun GitHub masing-masing, supaya commit tercatat atas nama sendiri.
3. Tulis pesan commit yang singkat dan jelas, misalnya `Tambah halaman jurnal mood`.
4. Satu commit sebaiknya berisi satu perubahan yang saling terkait.
5. Jangan mengubah berkas anggota lain tanpa berkoordinasi. Kalau terjadi konflik, hubungi Project Manager.
6. Kendala teknis dicatat di daftar kendala kelompok melalui Project Manager.

## Status

Tahap awal: proyek Flutter sudah diinisiasi dan kelompok sedang menyiapkan lingkungan kerja serta rancangan antarmuka.



