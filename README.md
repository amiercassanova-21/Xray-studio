<div align="center">

# 👑 CASSANOVA STUDIO
### **Xray Multi-Protocol & Multi-Mode Studio (LoadBalance & BestPing)**

[![Live Website](https://img.shields.io/badge/🌐_Live_App-xray--studio.cassanova.my.id-amber?style=for-the-badge&logo=googlechrome&logoColor=white)](https://xray-studio.cassanova.my.id/)
[![Status](https://img.shields.io/badge/Status-Active-emerald?style=for-the-badge)]()
[![Platform](https://img.shields.io/badge/Platform-Web%20Browser-blue?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-gold?style=for-the-badge)]()

*Platform utilitas profesional berbasis web untuk mengonversi, mengoptimalkan, dan mengintegrasikan multi-akun proxy (`VLESS`, `VMess`, dan `Trojan` dengan dukungan TLS & Non-TLS) ke dalam satu konfigurasi Xray JSON terpusat berbasis strategi **LoadBalancing** dan **BestPing** berkinerja tinggi.*

---

### 🌐 [Akses Aplikasi Web Langsung di Sini](https://xray-studio.cassanova.my.id/)

</div>

---

## ✨ Fitur Utama & Keunggulan

* **⚡ Multi-Protocol Live Parser**: Penguraian dan penggabungan berbagai format akun proxy populer (`vless://`, `vmess://`, `trojan://`) secara otomatis dengan indikator hitung status real-time (*Live Status Badge*).
* **⚖️ Dual Routing Strategy Optimization**:
  * **LoadBalance (`leastLoad`)**: Membagi beban trafik secara cerdas menggunakan *Burst Observatory* ke semua node aktif (ideal untuk streaming, mengunduh file besar, dan browsing multi-tab).
  * **Best Ping (`leastPing`)**: Mengunci dan menyalurkan koneksi ke node dengan latensi/pilihan ping terendah secara real-time (ideal untuk gaming online dan VoIP).
* **📁 Profile Manager (Penyimpanan Lokal)**: Simpan, muat, dan kelola banyak konfigurasi profil favorit Anda langsung di `localStorage` browser tanpa khawatir data hilang saat halaman di-refresh.
* **📋 Tempel Instan & Drag-and-Drop**: Tombol **Tempel** langsung dari clipboard hp/desktop serta dukungan *drag-and-drop* file langganan (`.txt` atau `.json`).
* **⚙️ Pengaturan Lanjutan (Accordion)**: Bebas sesuaikan Nama Remarks Config, Probe URL (*connectivity check*), Custom Tag Prefix (`TLS-`, `NTLS-`), Interval pengujian, serta Port SOCKS/HTTP (`10808`/`10809`).
* **📲 v2rayNG Ready Export**: Didesain khusus agar hasil **Salin JSON Mentah** atau **Download .json** dapat langsung di-impor ke aplikasi **v2rayNG** (Android) / **v2rayN** (Windows) tanpa error/failure.
* **🎨 3D Gold Luxury UI (Full Responsive)**: Antarmuka modern bernuansa gelap (*Dark Mode*) dengan sentuhan aksen emas 3D, sangat presisi dan nyaman digunakan baik pada layar smartphone maupun desktop.
* **🔒 100% Secure Client-Side Engine**: Seluruh proses parsing dan konversi dilakukan 100% di dalam browser Anda. Tidak ada data akun atau password proxy yang dikirimkan ke server luar.

---

## 📖 Cara Penggunaan

### 1. Membuat Konfigurasi di Cassanova Studio
1. Buka [https://xray-studio.cassanova.my.id/](https://xray-studio.cassanova.my.id/).
2. Pilih Strategi Routing: **LoadBalance** atau **Best Ping**.
3. Masukkan akun proxy Anda pada kotak input (Gunakan tombol **Tempel** untuk menempelkan link dari clipboard, atau seret file `.txt`/`.json`).
4. (Opsional) Buka **Pengaturan Lanjutan** untuk mengisi nama remarks konfigurasi Anda (misal: `Cassanova - LoadBalance`).
5. Klik **Generate Xray JSON**.

### 2. Mengimpor ke Aplikasi v2rayNG (Android)
* **Cara 1 (Salin Clipboard):**
  1. Klik tombol **Salin JSON Mentah** di Cassanova Studio.
  2. Buka aplikasi **v2rayNG** $\rightarrow$ Ketuk ikon **`+`** di pojok kanan atas.
  3. Pilih **Import config from Clipboard**.
* **Cara 2 (Download File):**
  1. Klik tombol **Download .json** di Cassanova Studio.
  2. Buka aplikasi **v2rayNG** $\rightarrow$ Ketuk ikon **`+`** di pojok kanan atas.
  3. Pilih **Import custom config** $\rightarrow$ Pilih file `.json` yang telah diunduh.

---

## ⚙️ Struktur Konfigurasi Output

Konfigurasi JSON yang dihasilkan oleh **Cassanova Studio** mencakup parameter jaringan teroptimasi:
* **Buffer Size**: Expanded `512 KB` level policy untuk menghilangkan *speed limit / bottleneck* saat streaming HD.
* **Sniffing Optimization**: Memprioritaskan `http` & `tls` pendeteksian domain tanpa QUIC untuk menghindari packet loss / ping spike pada ISP lokal.
* **DNS Resolution**: Multi-server DNS (`1.1.1.1` & `8.8.8.8`) dengan kueri `UseIPv4`.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & Modern JavaScript (ES6+)**
* **Tailwind CSS** (Styling & Responsive Layout Engine)
* **FontAwesome 6** (Vector Icons)
* **Google Fonts** (Inter & JetBrains Mono)

---

## 👤 Author & Branding

* **Amier Cassanova**
* **Domain Website:** [xray-studio.cassanova.my.id](https://xray-studio.cassanova.my.id/)
* **Telegram:** [@kang_rebahan](https://t.me/kang_rebahan)

---

## 📄 Lisensi

Proyek ini didistribusikan di bawah lisensi MIT. Bebas digunakan, dimodifikasi, dan dibagikan untuk kemajuan komunitas Xray/V2Ray.