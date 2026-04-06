# 🚀 Latihan WSL & Git SSH

Project sederhana untuk mencoba alur kerja pengembangan web menggunakan **Windows Subsystem for Linux (WSL)** dan koneksi **SSH** ke GitHub.

## 🛠️ Tech Stack
* **OS:** Ubuntu (WSL2)
* **Shell:** Zsh (Oh My Zsh)
* **Version Control:** Git
* **Connection:** SSH (Port 443 via HTTPS)

## 📂 Struktur Folder
* `index.html` - Halaman web sederhana pertama.
* `.ssh/config` - Konfigurasi jalur SSH untuk menembus firewall jaringan.

## 📝 Catatan Belajar
1. **Akses Root:** Menggunakan `sudo` untuk izin administrator.
2. **SSH Setup:** Berhasil konfigurasi `id_ed25519` dan bypass port 22 ke port 443.
3. **Zsh:** Menggunakan Zsh untuk tampilan terminal yang lebih informatif.

## 🚀 Cara Menjalankan
Cukup buka file `index.html` di browser favoritmu atau jalankan via terminal WSL:
```bash
explorer.exe index.html
