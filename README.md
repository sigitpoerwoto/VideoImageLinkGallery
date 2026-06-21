# 🌟 WP7 Smart Visual Bookmark & Media Gallery (Ultimate Engine)

![Version](https://img.shields.io/badge/Version-Ultimate_V8-blue.svg)
![Build](https://img.shields.io/badge/Build-Client--Side_HTML5-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Selamat datang di **WP7 Smart Gallery** — bukan sekadar pengelola *bookmark* biasa, melainkan **mesin database visual dan pemutar multimedia lokal paling tangguh** yang berjalan murni 100% di dalam memori *browser* Anda. 

Dibangun khusus untuk menangani koleksi data berskala masif (mampu menelan **50.000+ link dalam waktu kurang dari 1 detik**), aplikasi ini menyatukan antarmuka yang elegan dengan algoritma komputasi tingkat tinggi. Tidak perlu *install software*, tidak perlu *database server*, cukup buka file HTML dan koleksi Anda siap dinikmati.

---

## 🔥 FITUR UNGGULAN (The Ultimate Features)

Aplikasi ini dipersenjatai dengan fitur kelas *enterprise* yang dirancang untuk kecepatan, keamanan, dan kenyamanan:

- ⚡ **O(1) Hash Map Smart Merge:** Import puluhan ribu link tanpa membuat *browser lag*. Algoritma *Smart Merge* secara otomatis mencegah URL ganda, memperkaya tag/catatan jika ada data yang bersinggungan, dan mengabaikan duplikat.
- 🛡️ **Auto-Fallback Engine (Toleransi Server Mati):** Simpan 1 URL Utama dan 3 URL Cadangan. Jika URL Utama mati (Error 404/Server Down), *viewer* akan otomatis melompat dan memutar server cadangan tanpa memunculkan layar *error*!
- 🧹 **Smart URL Cleaner:** Mesin sapu bersih yang jenius. Masukkan nama domain yang mati (misal: `domainmati.com`), aplikasi akan menyapu puluhan ribu data Anda secara instan. Jika URL Utama mati, sistem akan otomatis mempromosikan URL Cadangan menjadi URL Utama.
- 📺 **Universal Media Player:** Memutar segalanya langsung di dalam aplikasi. Mendukung Gambar (JPG/PNG/WEBP/GIF), Video (MP4/WEBM), Live Streaming/IPTV (HLS/m3u8), DASH (.mpd), hingga sematan Iframe dan Auto-Bypass YouTube.
- ☁️ **Auto-Proxy Cloud Sync:** Fitur `IMPORT URL` memungkinkan Anda menyedot *database* `.txt` atau `.m3u` langsung dari link raw GitHub atau situs lain, lengkap dengan auto-proxy untuk menembus pemblokiran jaringan (*CORS Bypass*).
- 🔞 **Instant Safe Mode:** Punya koleksi sensitif? Gunakan *Safe Mode* untuk menyembunyikan semua konten dengan tag `NSFW` dalam satu kali klik.
- 🌐 **Bilingual UI:** Antarmuka mendukung 2 bahasa (Indonesia & Inggris) yang bisa diubah kapan saja secara *real-time* tanpa *refresh* halaman.

---

## 🎬 CARA MENDAPATKAN URL VIDEO MEDIA

Aplikasi ini membutuhkan *Direct Link* (URL langsung ke file medianya), bukan link halaman web (kecuali Anda menggunakan fitur "Paksa Tipe: Website"). Berikut cara mendapatkan URL mentah dari berbagai sumber:

### 1. Ekstrak URL Video/M3U8 (Cara Manual via Browser)
- Buka video streaming yang ingin Anda simpan di browser PC Anda.
- Tekan **F12** (atau klik kanan -> Inspect Element).
- Pergi ke tab **Network**.
- Di kolom filter, ketik `m3u8` (untuk streaming) atau `mp4` (untuk video statis).
- Putar videonya. Anda akan melihat file muncul di daftar Network.
- Klik kanan file tersebut -> **Copy** -> **Copy link address**. Link ini yang Anda masukkan ke aplikasi WP7.

### 2. Menggunakan Ekstensi Browser (Lebih Mudah)
- Instal ekstensi seperti **"Video DownloadHelper"**, **"HLS Downloader"**, atau **"The Stream Detector"** di Chrome/Edge/Firefox.
- Saat memutar video di suatu situs, klik ikon ekstensi tersebut.
- Pilih opsi **"Copy URL"** atau **"Copy M3U8"**. Link siap disimpan ke galeri!

### 3. Mengambil dari YouTube
- Cukup *copy* URL YouTube seperti biasa (contoh: `https://www.youtube.com/watch?v=xxxxx`). Aplikasi WP7 akan otomatis mengenalinya sebagai YouTube, membuatkan *thumbnail* resolusi tinggi, dan menyematkannya di *Viewer*.

---

## 💡 TIPS & TRICK PENGGUNAAN MAKSIMAL

Memaksimalkan alur kerja (*workflow*) Anda dengan WP7:

1. **Gunakan GitHub Sebagai "Cloud Database" Anda:**
   Karena aplikasi ini tidak punya server, Anda bisa membuat server cloud gratis Anda sendiri!
   - Ekspor data Anda (`⬇️ EXPORT TXT`).
   - *Upload* file TXT tersebut ke repositori GitHub.
   - Klik file TXT di GitHub, klik tombol **"Raw"**, dan salin URL-nya.
   - Kapanpun Anda membuka HTML WP7 ini di laptop lain atau HP, cukup gunakan menu **`☁️ IMPORT URL`** dan *paste* link Raw GitHub tadi. Data Anda akan sinkron seketika!

2. **Manfaatkan "Jadikan Utama & Hapus Lama":**
   Jika saat memutar video muncul *Banner Merah* peringatan bahwa Server Utama mati dan sedang memutar Server Alternatif, segera klik tombol **"Jadikan Utama & Hapus Lama"**. Ini akan menggeser server yang sehat menjadi utama dan membuang link busuk dari memori agar galeri Anda tetap optimal.

3. **Gunakan Pembersih Pintar Secara Berkala:**
   Dunia *streaming* tidak ada yang abadi. Server sering tumbang. Evaluasi koleksi Anda tiap bulan, kumpulkan awalan domain yang sudah mati (misal: `vip.server-rusak.net`), dan masukkan ke **🧹 BERSIHKAN URL**. Biarkan mesin membersihkan "sampah" memori dalam hitungan detik.

4. **Shortcut Keyboard untuk Navigasi Cepat:**
   - Gunakan spasi saat mencari untuk multi-kata (contoh ketik: `Porn IGO` untuk mencari data dengan kategori Porn dan tag IGO).
   - Tekan **Enter** setelah mengisi nomor pada kolom `LOMPAT` untuk langsung meluncur ke halaman media yang dituju.

---

## ⚙️ CARA INSTALASI

Sangat sederhana, tidak perlu instalasi!
1. Unduh file `My_WP7_Gallery.html`.
2. Klik ganda file tersebut untuk membukanya di browser modern apa saja (Chrome, Edge, Firefox, Safari).
3. Selesai! Mulai tambahkan koleksi Anda.

*Catatan: Sangat disarankan mem-bookmark file HTML lokal ini di browser Anda agar mudah diakses setiap hari.*

---
**Engine by Sigit Poerwoto & Gemini** | *Built for Speed, Privacy, and Scalability.*

# 🌟 WP7 Smart Visual Bookmark & Media Gallery (Ultimate Engine)

![Version](https://img.shields.io/badge/Version-Ultimate_V8-blue.svg)
![Build](https://img.shields.io/badge/Build-Client--Side_HTML5-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Welcome to **WP7 Smart Gallery** — not just another bookmark manager, but the **most powerful local visual database and multimedia player engine** that runs 100% natively in your browser's memory. 

Engineered specifically to handle massive-scale data collections (capable of swallowing **50,000+ links in under 1 second**), this application bridges an elegant interface with high-tier computational algorithms. No software installation, no database servers needed. Just open the HTML file, and your collection is ready to roll.

---

## 🔥 THE ULTIMATE FEATURES

This application is armed with enterprise-grade features designed for speed, security, and absolute convenience:

- ⚡ **O(1) Hash Map Smart Merge:** Import tens of thousands of links without freezing your browser. The *Smart Merge* algorithm automatically prevents duplicate URLs, enriches tags/notes on colliding data, and safely ignores identical entries.
- 🛡️ **Auto-Fallback Engine (Dead Server Tolerance):** Store 1 Main URL and up to 3 Backup URLs. If the Main URL dies (Error 404/Server Down), the viewer will automatically jump and play the backup servers without ever showing an error screen!
- 🧹 **Smart URL Cleaner:** A genius mass-cleanup engine. Input a dead domain name (e.g., `dead-server.com`), and the app will instantly scan your massive database. If a Main URL dies, the system automatically promotes your Backup URL to take the throne.
- 📺 **Universal Media Player:** Play everything directly inside the app. Supports Images (JPG/PNG/WEBP/GIF), Videos (MP4/WEBM), Live Streaming/IPTV (HLS/m3u8), DASH (.mpd), Iframe embeds, and Auto-Bypass YouTube viewing.
- ☁️ **Auto-Proxy Cloud Sync:** The `IMPORT URL` feature allows you to fetch `.txt` or `.m3u` databases directly from a GitHub raw link or any website, complete with a built-in auto-proxy to bypass network blocks (CORS Bypass).
- 🔞 **Instant Safe Mode:** Have a sensitive collection? Use *Safe Mode* to instantly hide all content tagged with `NSFW` in a single click.
- 🌐 **Bilingual UI:** The interface fully supports 2 languages (English & Indonesian), switchable in real-time without reloading the page.

---

## 🎬 HOW TO EXTRACT MEDIA URLs

This app requires *Direct Links* (URLs pointing directly to the media file), not webpage links (unless using the "Force Type: Website" feature). Here is how to get raw URLs from various sources:

### 1. Extract Video/M3U8 URLs (Manual via Browser)
- Open the streaming video you want to save in your PC browser.
- Press **F12** (or Right-Click -> Inspect Element).
- Go to the **Network** tab.
- In the filter box, type `m3u8` (for streaming) or `mp4` (for static videos).
- Play the video. You will see the file appear in the Network list.
- Right-click the file -> **Copy** -> **Copy link address**. Paste this link into the WP7 app.

### 2. Using Browser Extensions (The Easy Way)
- Install extensions like **"Video DownloadHelper"**, **"HLS Downloader"**, or **"The Stream Detector"** on Chrome/Edge/Firefox.
- While playing a video on a site, click the extension icon.
- Select the **"Copy URL"** or **"Copy M3U8"** option. The link is ready to be saved!

### 3. Fetching from YouTube
- Simply copy the YouTube URL as usual (e.g., `https://www.youtube.com/watch?v=xxxxx`). WP7 will automatically recognize it, generate a high-res thumbnail, and embed it perfectly in the Viewer.

---

## 💡 MAXIMIZING YOUR WORKFLOW (TIPS & TRICKS)

Take full advantage of the WP7 Engine with these pro tips:

1. **Use GitHub as Your Free "Cloud Database":**
   Since this app is serverless, you can build your own cloud sync!
   - Export your data (`⬇️ EXPORT TXT`).
   - Upload the TXT file to a GitHub repository.
   - Click the TXT file in GitHub, click the **"Raw"** button, and copy the URL.
   - Whenever you open this WP7 HTML on another laptop or phone, just use the **`☁️ IMPORT URL`** menu and paste the GitHub Raw link. Your data syncs instantly!

2. **Utilize "Make Main & Delete Old":**
   If a red warning banner appears during playback stating the Main Server is dead and an Alt Server is playing, simply click the **"Make Main & Delete Old"** button. This will instantly promote the healthy server to the main slot and permanently purge the dead link from memory.

3. **Routine Smart Cleanups:**
   Nothing lasts forever in the streaming world. Servers go down. Evaluate your collection monthly, gather the prefixes of dead domains (e.g., `vip.dead-server.net`), and feed them into the **🧹 CLEAN URLS** tool. Let the engine wipe the memory garbage in milliseconds.

4. **Lightning-Fast Keyboard Navigation:**
   - Use spaces in the search bar for multi-keyword filtering (e.g., typing `Nature 4K` will find items containing both the Category 'Nature' and the tag '4K').
   - Press **Enter** after typing a number in the `JUMP` box to instantly scroll to your target media card.

---

## ⚙️ INSTALLATION

Ridiculously simple. Zero installation required!
1. Download the `My_WP7_Gallery.html` file.
2. Double-click to open it in any modern browser (Chrome, Edge, Firefox, Safari).
3. Done! Start building your ultimate collection.

*Note: It is highly recommended to bookmark this local HTML file in your browser for quick daily access.*

---
**Engine by Sigit Poerwoto & Gemini** | *Built for Speed, Privacy, and Scalability.*
