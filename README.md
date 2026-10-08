🥗 HealthFit AI — Kalkulator Berat Ideal & Konsultan Kesehatan AI

Aplikasi web interaktif berbasis AI untuk menghitung Indeks Massa Tubuh (BMI), estimasi berat badan ideal, kebutuhan kalori harian (BMR & TDEE), rekomendasi makronutrisi (protein, karbohidrat, lemak), serta konsultasi perencanaan gaya hidup sehat berbasis AI (Gemini).

🚀 Fitur Utama

Kalkulator Kesehatan Lengkap:

Indeks Massa Tubuh (BMI): Menghitung status berat badan (Kurus, Normal, Kelebihan BB, Obesitas).

Berat Badan Ideal: Menggunakan rumus Devine beserta rentang berat badan sehat.

Metabolisme Basal (BMR): Dihitung menggunakan formula Mifflin-St Jeor.

Total Kebutuhan Kalori Harian (TDEE): Disesuaikan dengan 5 tingkat aktivitas harian dan target kesehatan (menjaga, menurunkan, atau menaikkan berat badan).

Rincian Makronutrisi: Pembagian porsi harian untuk Protein, Karbohidrat, dan Lemak.

Konsultan Kesehatan AI (Gemini):

Berinteraksi langsung dengan AI untuk meminta rekomendasi menu makanan harian (sarapan, makan siang, makan malam, dan camilan).

Mengirimkan hasil kalkulasi fisik ke AI hanya dengan 1 kali klik.

Tanya jawab seputar fitness, nutrisi, dan tips olahraga.

Responsive & Modern UI: Didesain menggunakan Tailwind CSS, kompatibel untuk tampilan ponsel maupun komputer.

🛠️ Teknologi yang Digunakan

Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla ES6+), FontAwesome Icons.

Backend & AI API: Node.js, Express.js, @google/genai (SDK Resmi Gemini API).

📂 Struktur Proyek

cek-ideal-kalori-ai/
├── public/
│   └── index.html         # Tampilan UI Utama & Aplikasi Client
├── .env                   # Environment Variables (API Key & Port)
├── package.json           # Dependensi & Script Proyek
├── package-lock.json      # File Lock Dependensi
├── server.js              # Server Express Backend & Endpoint AI
└── README.md              # Dokumentasi Proyek


⚡ Cara Menjalankan Proyek di Lokal

1. Prasyarat

Pastikan Anda telah menginstal Node.js (Versi 18+ direkomendasikan) di komputer Anda.

2. Kloning / Unduh Proyek

Unduh atau kloning repositori ini ke komputer Anda, lalu masuk ke direktori proyek:

cd cek-ideal-kalori-ai


3. Instal Dependensi

Jalankan perintah berikut untuk menginstal seluruh modul paket yang dibutuhkan:

npm install


4. Konfigurasi Environment Variable (.env)

Buat file bernama .env di direktori utama proyek dan isi konfigurasi berikut:

PORT=3000
GEMINI_API_KEY=Kunci_API_Gemini_Anda


Catatan: Anda bisa mendapatkan GEMINI_API_KEY secara gratis melalui Google AI Studio.

5. Jalankan Server

Gunakan perintah berikut untuk menjalankan server dalam mode pengembangan (development):

npm run dev


Atau untuk mode produksi:

npm start


Buka peramban (browser) Anda dan akses:

http://localhost:3000


📖 Cara Penggunaan Aplikasi

Masukan Data Tubuh:

Pilih Jenis Kelamin, isi Usia, Tinggi Badan, Berat Badan, Tingkat Aktivitas Harian, dan Target Kesehatan Anda.

Klik tombol "Hitung Hasil Saya".

Lihat Hasil Kalkulasi:

Sistem akan secara otomatis menampilkan nilai BMI, Berat Ideal, Target Kalori, BMR, TDEE, serta takaran Makronutrisi harian.

Konsultasi dengan AI:

Klik tombol "Minta Saran Menu & Latihan dari AI berdasarkan Data Ini".

Sistem akan secara otomatis menyusun data tubuh Anda menjadi prompt dan mengarahkan Anda ke tab Konsultan AI.

Kirim pesan untuk mendapatkan saran pola makan dan latihan kustom dari AI.

📄 Lisensi

Proyek ini dibuat di bawah lisensi ISC License.