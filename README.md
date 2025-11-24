🧮 Kalkulator Interaktif

Kalkulator web interaktif dengan fitur lengkap yang mendukung urutan operasi matematika yang benar (perkalian/pembagian sebelum penjumlahan/pengurangan).
Dilengkapi memory (M+, M-, MR, MC), riwayat perhitungan, desain modern, dan dukungan keyboard.

🚀 Fitur Utama
✨ Fitur Aritmatika

Penjumlahan, pengurangan, perkalian, pembagian

Urutan operasi otomatis (× ÷ sebelum + -)

Display ganda: current operation & previous expression

Responsif untuk desktop dan mobile

Dukungan keyboard

🧮 Fitur Memory
Tombol	Fungsi
M+	Menambah nilai display ke memory
M-	Mengurangi memory dengan nilai display
MR	Mengambil nilai memory ke display
MC	Menghapus memory

Contoh:

1000 → M+     → Memory = 1000
500  → M-     → Memory = 500
MR            → Display = 500

📊 Fitur Tambahan

Riwayat 5 perhitungan terakhir

Penanganan error (pembagian dengan nol)

Clear All (C) dan Clear Entry (CE)

Desain glassmorphism + animasi modern

🎯 Cara Penggunaan
Operasi Dasar

Klik angka (0–9)

Pilih operator + - × ÷

Tekan = atau Enter untuk hasil

Contoh:

3 + 3 × 6 ÷ 2 = 12

3 × 6 = 18
18 ÷ 2 = 9
3 + 9 = 12

⌨️ Keyboard Shortcuts
Tombol	Fungsi
0–9	Input angka
+ - * /	Operator
Enter	Hitung hasil
Backspace	CE (Clear Entry)
Escape	C (Clear All)
.	Titik desimal
🛠️ Teknologi

HTML5 untuk struktur

CSS3 (Glassmorphism + animasi)

JavaScript ES6 untuk logic

Grid Layout & Flexbox

📁 Struktur Proyek
calculator/
│── index.html     # File utama aplikasi
│── README.md      # Dokumentasi
└── (style & script embedded)

🧠 Arsitektur JavaScript
📌 Core Functions
evaluateExpression(expression)       // Evaluasi ekspresi
tokenize(expression)                // Memecah ekspresi menjadi token
processMultiplicationDivision()     // Menangani × ÷
processAdditionSubtraction()        // Menangani + -

📌 State Management
let currentOperand = '0';   // Display saat ini
let expression = '';        // Ekspresi lengkap
let memoryValue = 0;        // Nilai memory
let history = [];           // Riwayat 5 perhitungan

📌 Event Handlers
numberButtons.addEventListener('click')
operatorButtons.addEventListener('click')
memoryButtons.addEventListener('click')
document.addEventListener('keydown')   // Keyboard support

🎨 Desain & UX
Visual

Glassmorphism (blur + transparency)

Warna operator: oranye

Warna fitur memory: biru

Animasi hover + transition

Pengalaman Pengguna

Real-time display update

Tombol animatif

Error handling yang jelas

Riwayat perhitungan mudah diakses

🔧 Cara Menjalankan

Download folder atau file index.html

Buka file menggunakan browser modern

Kalkulator siap digunakan

Requirements:

Browser modern

JavaScript aktif

Minimal resolusi 320px

📝 Contoh Penggunaan
1️⃣ Perhitungan Bertingkat
Input : 5 + 3 × 2
Proses: 3 × 2 = 6 → 5 + 6
Hasil : 11

2️⃣ Memory
1000 → M+  → Memory = 1000
250  → M+  → Memory = 1250
500  → M-  → Memory = 750
MR         → Display = 750

3️⃣ Perhitungan Kompleks
Input : 10 + 2 × 5 - 8 ÷ 4
Proses: 2 × 5 = 10
        8 ÷ 4 = 2
        10 + 10 - 2
Hasil : 18

🐛 Troubleshooting
Masalah Umum
Masalah	Penyebab	Solusi
Hasil tidak sesuai	Salah urutan operasi	Periksa ekspresi
Keyboard tidak berfungsi	Halaman tidak fokus	Klik area kalkulator
Display error	Ekspresi tidak valid	Tekan C
Pesan Error

"Error: Division by zero" → Pembagian oleh 0

"Error" → Ekspresi tidak valid
