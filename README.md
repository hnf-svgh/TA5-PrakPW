Kalkulator Interaktif
Kalkulator web interaktif dengan fitur lengkap yang mendukung urutan operasi matematika yang benar (perkalian/pembagian sebelum penjumlahan/pengurangan).

🚀 Fitur
✨ Fitur Utama
Operasi Aritmatika Dasar: Penjumlahan, pengurangan, perkalian, pembagian

Urutan Operasi Matematika: Menghitung dengan urutan yang benar (× ÷ sebelum + -)

Display Ganda: Menampilkan operasi saat ini dan operasi sebelumnya

Desain Responsif: Tampilan optimal untuk desktop dan mobile

Dukungan Keyboard: Input menggunakan keyboard dan mouse

🧮 Fitur Memory
M+ (Memory Plus): Menambahkan nilai display ke memory

M- (Memory Minus): Mengurangi memory dengan nilai display

MR (Memory Recall): Memanggil nilai dari memory

MC (Memory Clear): Menghapus nilai memory

📊 Fitur Tambahan
Riwayat Perhitungan: Menyimpan 5 perhitungan terakhir

Penanganan Error: Deteksi pembagian dengan nol

Clear Functions: C (Clear All) dan CE (Clear Entry)

Desain Modern: Glassmorphism design dengan animasi

🎯 Cara Penggunaan
Operasi Dasar
Input Angka: Klik tombol angka (0-9)

Operasi: Pilih operator (+, -, ×, ÷)

Hasil: Tekan = atau Enter untuk mendapatkan hasil

Contoh Perhitungan
text
3 + 3 × 6 ÷ 2 = 12
Penjelasan:

3 × 6 = 18

18 ÷ 2 = 9

3 + 9 = 12

Fungsi Memory
javascript
// Contoh penggunaan memory:
1000 → M+  // Memory = 1000
500  → M-  // Memory = 500
MR         // Display = 500
Keyboard Shortcuts
Angka 0-9: Input angka

Operator: +, -, *, /

Enter/Equal: Menghitung hasil

Escape: Clear All (C)

Backspace: Clear Entry (CE)

Decimal: . (titik)

🛠️ Teknologi
HTML5: Struktur aplikasi

CSS3: Styling dengan glassmorphism effect

JavaScript ES6: Logika kalkulator dan interaktivitas

Grid Layout: Tata letak responsif

Flexbox: Penyelarasan elemen

📁 Struktur Kode
File Structure
text
calculator/
├── index.html          # File utama
├── README.md           # Dokumentasi
└── (style dan script embedded)
JavaScript Architecture
Core Functions
javascript
// Evaluasi ekspresi matematika
evaluateExpression(expression)    // Main evaluator
tokenize(expression)             // Memecah ekspresi
processMultiplicationDivision()  // Proses × ÷
processAdditionSubtraction()     // Proses + -
State Management
javascript
let currentOperand = '0';        // Display saat ini
let expression = '';             // Ekspresi lengkap
let memoryValue = 0;             // Nilai memory
let history = [];                // Riwayat perhitungan
Event Handlers
javascript
// Button events
numberButtons.addEventListener('click')
operatorButtons.addEventListener('click') 
memoryButtons.addEventListener('click')

// Keyboard support
document.addEventListener('keydown')
🎨 Design Features
Visual Design
Glassmorphism Effect: Background transparan dengan blur

Modern Color Scheme: Orange untuk operator, biru untuk memory

Smooth Animations: Hover effects dan transitions

Responsive Grid: Layout adaptif untuk semua device

User Experience
Real-time Display: Update tampilan secara langsung

Visual Feedback: Animasi tombol saat diklik

Error Handling: Pesan error yang jelas

History Panel: Akses cepat ke perhitungan sebelumnya

🔧 Cara Menjalankan
Download File: Simpan file HTML ke komputer

Buka di Browser: Double-click file atau buka dengan browser

Gunakan: Mulai menghitung!

Requirements
Browser modern (Chrome, Firefox, Safari, Edge)

JavaScript enabled

Resolusi minimum 320px

📝 Contoh Penggunaan
Kasus 1: Perhitungan Bertingkat
text
Input: 5 + 3 × 2
Proses: 3 × 2 = 6 → 5 + 6
Hasil: 11
Kasus 2: Menggunakan Memory
text
Steps:
1. 1000 → M+ (Memory = 1000)
2. 250 → M+ (Memory = 1250) 
3. 500 → M- (Memory = 750)
4. MR → Display 750
Kasus 3: Complex Calculation
text
Input: 10 + 2 × 5 - 8 ÷ 4
Proses: 
  2 × 5 = 10
  8 ÷ 4 = 2  
  10 + 10 - 2
Hasil: 18
🐛 Troubleshooting
Masalah Umum
Hasil Tidak Sesuai: Pastikan urutan operasi matematika

Keyboard Tidak Berfungsi: Pastikan fokus pada halaman

Display Error: Gunakan C untuk reset kalkulator

Error Messages
"Error: Division by zero": Pembagian dengan angka 0

"Error": Ekspresi matematika tidak valid



Tips: Gunakan tombol C untuk mereset kalkulator sepenuhnya, dan CE hanya untuk menghapus input saat ini.

