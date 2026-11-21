# Linux Pelajar Edition 1.0

## Deskripsi Proyek
Linux Pelajar Edition 1.0 merupakan sistem operasi hasil
remastering Kubuntu 26.04.1 menggunakan Cubic.

Proyek ini berfokus pada penyesuaian identitas sistem operasi,
tampilan installer, animasi boot, dan konfigurasi pengguna.

## Teknologi yang Digunakan
- Kubuntu 26.04.1
- Cubic (Custom Ubuntu ISO Creator)
- KDE Plasma
- Plymouth
- SDDM
- Calamares
- Qt 6 dan CMake
- Shell Script dan systemd

## Struktur Repository

### scripts/
Berisi skrip linux-pelajar-default-avatar untuk mengatur
avatar bawaan pengguna.

### configs/
Berisi konfigurasi SDDM dan layanan systemd yang digunakan
untuk pengaturan avatar pengguna.

### plymouth/
Berisi berkas tema Plymouth, skrip animasi, dan logo
untuk tampilan boot Linux Pelajar.

### installer/
Berisi berkas antarmuka Qt dan gambar yang dimodifikasi
pada aplikasi kubuntu-installer-prompt.

### assets/
Berisi gambar avatar bawaan Linux Pelajar Edition.

## Proses Remastering
1. Menyiapkan ISO dasar Kubuntu.
2. Membuka proyek menggunakan Cubic.
3. Menyesuaikan identitas Linux Pelajar.
4. Mengonfigurasi tema Plymouth dan tampilan login.
5. Memodifikasi antarmuka installer.
6. Mengompilasi ulang aplikasi installer menggunakan CMake.
7. Menambahkan konfigurasi avatar pengguna.
8. Membangun kembali ISO menggunakan Cubic.
9. Menguji hasil remastering menggunakan VirtualBox.

## Hasil
ISO yang dihasilkan:
linux-pelajar-edition-1.0-amd64.iso

Repository ini menyimpan skrip, konfigurasi, dan aset
pendukung proses remastering, bukan file ISO secara langsung.

## Catatan
Fungsi setiap konfigurasi perlu diverifikasi melalui
pengujian sistem hasil instalasi.

Linux Pelajar Edition dikembangkan berdasarkan Kubuntu
dan tetap menggunakan komponen perangkat lunak dari
proyek open-source terkait.
