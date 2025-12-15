# ⚡ KOKOROBET - ZIVPN Installer

Repository ini menyediakan installer cepat untuk **ZIVPN (ZiVPN)**, sebuah protokol VPN Premium yang dirancang untuk koneksi cepat, aman, dan stabil. ZIVPN adalah bagian dari solusi server yang dikembangkan oleh GerhanaTunnel.

## 🎯 Fitur Utama ZIVPN

Protokol ZiVPN menawarkan keunggulan dalam stabilitas koneksi dan kecepatan.

* **Keamanan Tingkat Tinggi:** Menggunakan enkripsi native VPN yang kuat.
* **Performa Maksimal:** Protokol ringan yang dirancang untuk efisiensi data.
* **Kemudahan Integrasi:** Konfigurasi server yang mudah diatur menggunakan script ini.
* **Ideal untuk:** Koneksi gaming, streaming, dan browsing harian yang memerlukan latensi rendah.

## ⚙️ Persyaratan Sistem

Pastikan server Anda memenuhi persyaratan minimum berikut sebelum menjalankan script:

* Sistem Operasi: Debian 10/11 atau Ubuntu 20.04/22.04 (Disarankan).
* Akses: Akses root (Superuser) ke server.
* RAM: Minimal 512 MB.

## 🚀 Cara Instalasi ZIVPN

Untuk memulai instalasi ZIVPN di server Anda, cukup jalankan satu baris perintah berikut di terminal SSH:

```bash
apt update && apt upgrade -y && apt install wget -y && wget -O zivpn-installer [https://raw.githubusercontent.com/joytun21/kokorobet/main/install-zivpn](https://raw.githubusercontent.com/joytun21/kokorobet/main/install-zivpn) && chmod +x zivpn-installer && bash zivpn-installer
