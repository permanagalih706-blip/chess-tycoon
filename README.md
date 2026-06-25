# ♟️ Chess Tycoon Pro - Tournament Edition

**Chess Tycoon Pro** adalah game catur inovatif yang menggabungkan strategi taktis catur klasik dengan **manajemen ekonomi ketat (Tycoon)**. Di sini, bidak tidak gratis! Anda harus memutar otak untuk mengelola modal, membeli pasukan di waktu yang tepat, membayar biaya perawatan (maintenance) setiap kali melangkah, dan memburu bidak lawan demi mendapatkan hadiah uang (*bounty*).

Versi *Tournament Edition* ini sudah dilengkapi dengan **Sistem Turn Timer** serta deteksi akhir game otomatis untuk memastikan tensi pertandingan tetap tinggi dan kompetitif.

---

## ✨ Fitur Utama

* **Sistem Ekonomi & Toko Global (Board 2):** Setiap pemain memulai dengan modal awal **$5.00**. Anda bisa membeli bidak baru dari toko selama stok tersedia dan ruang promosi di papan masih kosong.
* **Biaya Perawatan (Maintenance Move Fee):** Setiap pergerakan bidak membutuhkan biaya operasional. Bidak yang lebih kuat membutuhkan biaya jalan yang lebih mahal. Khusus pergerakan **Raja (King)** justru akan memberikan Anda pendapatan pasif sebesar **+$1.00**.
* **Graveyard Cooldown (Kuburan Bidak):** Bidak yang berhasil dimakan oleh lawan tidak langsung lenyap, melainkan masuk ke area kuburan selama **3 giliran** sebelum akhirnya kembali menjadi stok di toko global.
* **Turn Timer (Batas Waktu Gerak):** Setiap pemain hanya memiliki waktu **30 detik** per giliran untuk melangkah atau membeli bidak. Jika waktu habis, pemain tersebut dinyatakan **Kalah Waktu (Timeout)**.
* **Mekanisme Akhir Game Otomatis:**
* 👑 **Checkmate (Skakmat):** Deteksi otomatis saat Raja terjebak dan tidak memiliki langkah legal.
* 🤝 **Stalemate (Seri/Remis):** Deteksi saat pemain tidak dalam kondisi skak, tetapi tidak memiliki langkah legal yang bisa dijalankan.
* ⏳ **Anti-Stall Limit:** Game otomatis berakhir seri jika pertandingan berjalan selama 15 ronde berturut-turut (30 plies) tanpa ada bidak yang maju atau mati.


* **Dua Mode Gameplay:**
* 👥 **2 Players (Local):** Bermain bersama teman secara bergantian di satu perangkat.
* 🤖 **VS Bot AI:** Melawan komputer dengan 3 tingkat kesulitan berbeda (**Easy, Normal, Hard**).



---

## 📊 Tabel Harga & Biaya Operasional Unit

Berikut adalah rincian kalkulasi ekonomi untuk setiap unit di dalam game:

| Simbol (W/B) | Nama Unit | Harga Beli | Biaya Gerak (*Maintenance*) | Catatan Khusus |
| --- | --- | --- | --- | --- |
| ♙ / ♟ | **Pawn** | $1.00 | $0.10 | Langkah pertama gratis ($0.00). Biaya Promosi: $1.00. |
| ♞ / ♞ | **Knight** | $3.00 | $0.30 | Dapat melompati bidak lain. |
| ♗ / ♝ | **Bishop** | $3.00 | $0.30 | Bergerak secara diagonal. |
| ♖ / ♜ | **Rook** | $5.00 | $0.50 | Bergerak lurus vertikal/horizontal. |
| ♕ / ♛ | **Queen** | $9.00 | $0.90 | Unit paling kuat dengan biaya jalan tertinggi. |
| ♔ / ♚ | **King** | *N/A* | **-$1.00** | Tidak bisa dibeli. Melangkah justru **menghasilkan $1.00**. |

---

## 🚀 Cara Menjalankan Game

Game ini dibangun menggunakan arsitektur *Single-File Web App* (HTML5, CSS3, dan Vanilla JavaScript murni tanpa *framework* luar), sehingga sangat ringan dan mudah dijalankan.

1. **Salin Kode:** Copy seluruh kode sumber `index.html` yang telah disediakan.
2. **Simpan File:** Paste kode tersebut ke dalam aplikasi teks editor (seperti Notepad, VS Code, atau Sublime Text) dan simpan dengan nama `index.html`.
3. **Jalankan:** Klik dua kali file `index.html` tersebut. Game akan langsung terbuka dan siap dimainkan di browser kesayangan Anda (Chrome, Edge, Firefox, atau Safari).

---

## 🛠️ Teknologi yang Digunakan

* **HTML5:** Struktur papan catur dan panel toko.
* **CSS3 (Variabel & Grid):** Desain antarmuka gelap (*dark mode*) yang modern, responsif, dan scannable.
* **Vanilla JavaScript (ES6+):** Logika algoritma catur, kecerdasan buatan (Bot AI) berbasis kalkulasi skor bobot, sistem timer, dan validasi *check/checkmate*.

---

## 📜 Lisensi

Proyek ini bersifat *Open Source*. Silakan modifikasi, kembangkan, atau tambahkan fitur baru seperti sistem *leaderboard*, visual efek animasi, atau mode *online multiplayer* sesuka hati Anda!

> **Tips Kemenangan:** Jangan biarkan uang Anda habis membusuk di bank, tapi jangan juga terlalu boros membeli Queen sampai tidak punya sisa uang untuk menggerakkannya! Selamat bertanding!
