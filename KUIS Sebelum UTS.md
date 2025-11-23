# QUIZ UJIAN AKHIR SEMESTER
## PEMROGRAMAN WEB - STUDI KASUS

---

**Mata Kuliah:** Pemrograman Web  
**Jenis Ujian:** Ujian Akhir Semester  
**Kelompok:** 2-3 Orang per kelompok

---

## PETUNJUK UMUM

1. Baca dan pahami studi kasus dengan seksama sebelum mengerjakan
2. Bagi tugas dengan jelas antara anggota kelompok
3. Upload semua file yang diminta ke dalam folder dengan nama: `KELOMPOK_XX_NIM1_NIM2`

---

## STUDI KASUS: WEBSITE KAFE "KOPI SANTAI"

Anda diminta untuk membuat sebuah website untuk sebuah kafe modern bernama **"Kopi Santai"**. Kafe ini adalah kafe lokal yang ingin meningkatkan presence online mereka dengan website yang menarik dan informatif. Website ini akan digunakan untuk menampilkan menu, informasi kafe, galeri, dan sistem reservasi online.

---

## SPESIFIKASI UMUM

### Struktur File yang Harus Dibuat:
```
KELOMPOK_XX_NIM1_NIM2/
│
├── index.html
├── menu.html
├── about.html
├── reservation.html
├── css/
│   ├── style.css
│   └── responsive.css
├── images/
│   └── (tempat menyimpan gambar)
```

### Pembagian Tugas Kelompok (Pembagian bisa bebas sesuai persetujuan masing-masing kelompok):

**Anggota 1 - Fokus pada:**
- Halaman Home (index.html)
- Halaman Menu (menu.html)
- CSS: Navigation, Hero Section, Menu Cards
- Responsive design untuk halaman tersebut

**Anggota 2 - Fokus pada:**
- Halaman About (about.html)
- Halaman Reservation (reservation.html)
- CSS: About Section, Form Styling, Footer
- Responsive design untuk halaman tersebut

**Dikerjakan Bersama:**
- Color scheme & typography
- Overall layout consistency
- Testing & debugging
- Documentation

---

## BAGIAN 1: HTML5 & ELEMEN SEMANTIK

### A. Halaman Home (index.html)

Buat halaman utama dengan struktur HTML5 semantik yang mengandung:

1. **Header** yang berisi:
   - Logo atau nama kafe "Kopi Santai"
   - Tagline: "Nikmati Setiap Tegukan"
   - Navigasi menu dengan link ke: Home, Menu, About, Reservation
   - Gunakan elemen `<nav>` dengan tepat

2. **Hero Section** (menggunakan `<section>`) yang berisi:
   - Background image kafe/kopi (gunakan CSS)
   - Judul utama: "Selamat Datang di Kopi Santai"
   - Subtitle: "Tempat Terbaik untuk Bersantai dengan Secangkir Kopi"
   - 2 Tombol CTA: "Lihat Menu" dan "Reservasi Sekarang"

3. **Featured Menu Section** yang menampilkan:
   - Judul section: "Menu Favorit Kami"
   - 4 card menu populer dengan:
     - Gambar produk
     - Nama menu
     - Harga
     - Deskripsi singkat
   - Gunakan elemen `<article>` untuk setiap card

4. **Why Choose Us Section**:
   - Judul: "Mengapa Memilih Kami?"
   - 3 keunggulan kafe (contoh: Biji Kopi Premium, Suasana Nyaman, Wifi Gratis)
   - Gunakan icons atau gambar
   - Setiap keunggulan dalam elemen `<article>`

5. **Footer** yang berisi:
   - Informasi kontak (alamat, phone, email)
   - Jam operasional
   - Social media links (Instagram, Facebook, WhatsApp)
   - Copyright information
   - Gunakan elemen `<footer>` dan `<address>` dengan tepat

---

### B. Halaman Menu (menu.html)

Buat halaman menu dengan struktur yang lengkap:

1. **Menu Categories Filter** (menggunakan `<nav>`):
   - Buttons untuk filter: All, Coffee, Non-Coffee, Food, Snacks
   - Gunakan elemen `<button>` dengan attribute `data-filter`

2. **Menu Grid Section**:
   - Judul: "Daftar Menu Lengkap"
   - Grid layout menampilkan minimal 12 item menu
   - Setiap menu item menggunakan `<article>` dengan:
     - Gambar menu (gunakan `<figure>` dan `<figcaption>`)
     - Nama menu (gunakan `<h3>`)
     - Kategori (attribute `data-category`)
     - Deskripsi singkat
     - Harga
     - Tag "Best Seller" atau "New" jika ada (gunakan `<span>` atau `<mark>`)

3. **Menu Categories** yang harus ada:
   - **Coffee**: Espresso, Cappuccino, Latte, Americano (min. 4 items)
   - **Non-Coffee**: Chocolate, Matcha, Tea (min. 3 items)
   - **Food**: Pasta, Sandwich, Salad (min. 3 items)
   - **Snacks**: Cake, Cookies, Pastry (min. 2 items)

---

### C. Halaman About (about.html)

Buat halaman tentang kafe dengan struktur:

1. **Story Section** yang mengandung:
   - Foto kafe (gunakan `<figure>` dan `<figcaption>`)
   - Judul: "Cerita Kami"
   - Paragraf tentang sejarah dan filosofi kafe (minimal 3 paragraf)
   - Quote/moto kafe (gunakan `<blockquote>`)

2. **Our Values Section**:
   - Judul: "Nilai-Nilai Kami"
   - Daftar nilai kafe menggunakan `<ul>`:
     - Kualitas Premium
     - Pelayanan Terbaik
     - Sustainability
     - Community
     - dll (minimal 5 items)

3. **Gallery Section**:
   - Judul: "Galeri Kafe"
   - Grid foto-foto kafe (interior, eksterior, barista, suasana)
   - Minimal 6 foto
   - Setiap foto menggunakan `<figure>` dengan caption

4. **Location & Hours Section**:
   - Judul: "Lokasi & Jam Buka"
   - Embed Google Maps (gunakan `<iframe>`)
   - Tabel jam operasional (gunakan `<table>`)
   - Informasi alamat lengkap (gunakan `<address>`)

---

### D. Halaman Reservation (reservation.html)

Buat halaman reservasi dengan:

1. **Reservation Info Section**:
   - Judul: "Reservasi Meja"
   - Paragraf informasi tentang sistem reservasi
   - List persyaratan reservasi (gunakan `<ul>`)

2. **Reservation Form** yang mengandung:
   - **Personal Information:**
     - Input: Nama Lengkap (required)
     - Input: Email (required, type="email")
     - Input: No. Telepon (required, type="tel")
   
   - **Reservation Details:**
     - Input: Tanggal (required, type="date")
     - Input: Waktu (required, type="time")
     - Select: Jumlah Orang (dropdown 1-10 orang)
     - Select: Tipe Meja (Regular, Window Seat, Private Room)
   
   - **Additional:**
     - Textarea: Catatan Khusus (optional)
     - Checkbox: Persetujuan syarat dan ketentuan (required)
   
   - Submit button: "Kirim Reservasi"

3. **Form Requirements**:
   - Semua input harus memiliki `<label>` yang sesuai
   - Gunakan HTML5 validation (required, pattern, min, max)
   - Gunakan `placeholder` yang informatif
   - Grouping menggunakan `<fieldset>` dan `<legend>`

4. **Contact Alternative**:
   - Informasi kontak untuk reservasi via telepon/WhatsApp
   - Gunakan elemen `<aside>` untuk informasi tambahan

---

## BAGIAN 2: CSS STYLING

### A. File style.css - Styling Utama

Buat styling untuk semua halaman dengan ketentuan:

#### 1. CSS Reset & Base Styles
- Reset default margins, paddings, dan box-sizing
- Set base styles untuk body (font-family, line-height, color)

#### 32 Typography
- Gunakan minimal 2 font family (heading & body text)
- Set ukuran font yang proporsional (bisa menggunakan rem)
- Line-height yang baik untuk readability
- Font-weight yang bervariasi untuk hierarchy

#### 3. Layout & Spacing
- **Header/Navigation**: 
  - Sticky/fixed position
  - Flexbox untuk layout
  - Hover effects pada menu
  
- **Hero Section**:
  - Full width atau container
  - Center alignment
  - Spacing yang proporsional
  
- **Content Sections**:
  - Consistent padding/margin
  - Max-width untuk readability
  - Section spacing

- **Footer**:
  - Background color berbeda
  - Flex layout untuk konten

#### 4. Components Styling

**Buttons:** 
- Style untuk base button dengan coffee theme
- State styling: hover, active, focus
- Button variants: primary dan secondary

**Menu Cards:** 
- Box shadow yang subtle
- Border radius
- Hover effects (transform scale, shadow)
- Smooth transitions
- Price styling yang menarik
- Badge untuk "Best Seller" atau "New"

**Forms:**
- Input styling (border, padding, focus state)
- Label styling
- Select dropdown styling
- Textarea styling
- Error/validation states
- Submit button dengan hover effect
- Fieldset dan legend styling

**Images:**
- Responsive images (max-width: 100%)
- Object-fit untuk maintain aspect ratio
- Hover effects untuk gallery
- Border radius untuk aesthetic
- Loading placeholder (optional)

---

### B. File responsive.css - Responsive Design

Buat styling responsive untuk berbagai ukuran layar:

#### 1. Mobile First Approach 
Base styles untuk mobile, kemudian tambahkan media queries untuk layar lebih besar.

#### 2. Breakpoints

**Mobile (< 768px):**
- Navigation: hamburger menu atau vertical stack
- Single column layout
- Reduced font sizes
- Adjusted spacing

**Tablet (768px - 1024px):**
- Navigation: horizontal dengan spacing yang sesuai
- 2 column layout untuk cards/grid
- Medium font sizes

**Desktop (> 1024px):**
- Full horizontal navigation
- 3-4 column layout untuk gallery
- Larger font sizes
- More spacing

---

## BAGIAN 3: CSS Lanjutan

### A. CSS Animations & Transitions (NILAI PLUS)

Implementasikan animasi/transisi pada:

1. **Hero section fade-in** saat page load
2. **Hover effects** pada buttons dan cards
3. **Smooth scrolling** untuk navigation links
4. **Loading animation** (optional, bonus)

---

### B. Flexbox & Grid Layout (WAJIB MENGGUNAKAN TAILWIND CSS)

Gunakan dengan tepat:
1. **Flexbox** untuk: navigation, card layouts, footer
2. **CSS Grid** untuk: gallery portfolio, overall page layout

---

### C. Best Practices & Code Quality

1. **CSS Organization:**
   - Struktur kode yang rapi
   - Naming convention yang konsisten (BEM recommended)
   - Comments untuk section-section penting

2. **Performance:**
   - Minimalkan selector complexity
   - Avoid !important (kecuali benar-benar diperlukan)
   - Efficient CSS (no redundant code)

3. **Browser Compatibility:**
   - Vendor prefixes jika diperlukan
   - Fallback untuk CSS variables

---

## BAGIAN 4: LAPORAN PROJECT (FORMAT PDF)
**[Dikerjakan bersama]**

### LAPORAN_KELOMPOK_XX.pdf

Buat laporan lengkap dalam format PDF dengan struktur sebagai berikut:

---

## FORMAT LAPORAN

### Cover Laporan:
- Judul: "LAPORAN PROJECT WEBSITE KAFE KOPI SANTAI"
- Mata Kuliah: Pemrograman Web
- Nama Kelompok & Nomor Kelompok
- Nama & NIM semua anggota
- Kelas
- Semester & Tahun Ajaran
- Logo Universitas/Institusi

---

### BAGIAN 1: INFORMASI KELOMPOK

**Jawab pertanyaan berikut:**

1. **Identitas Kelompok**
   - Nomor Kelompok:
   - Nama Kelompok (jika ada):
   
2. **Data Anggota Kelompok**
   
   **Anggota 1:**
   - Nama Lengkap:
   - NIM:
   - Email:
   - GitHub Username:
   - Bagian yang dikerjakan:
   
   **Anggota 2:**
   - Nama Lengkap:
   - NIM:
   - Email:
   - GitHub Username:
   - Bagian yang dikerjakan:

---

### BAGIAN 2: DESKRIPSI PROJECT

**Jawab pertanyaan berikut dengan lengkap (minimal 1 paragraf per pertanyaan):**

1. **Jelaskan konsep dan tujuan dari website Kopi Santai yang Anda buat?**
   - Apa visi dari website ini?
   - Apa yang membuat website ini unik?

2. **Siapa target audience dari website ini?**
   - Usia
   - Karakteristik pengunjung
   - Kebutuhan yang dipenuhi

3. **Sebutkan dan jelaskan fitur-fitur utama yang diimplementasikan dalam website?**
   - Minimal 5 fitur utama
   - Penjelasan fungsi masing-masing fitur

---

### BAGIAN 3: DOKUMENTASI TEKNIS

**Jawab pertanyaan berikut:**

1. **Struktur File & Folder**
   
   Jelaskan struktur folder project Anda:
   ```
   KELOMPOK_XX_NIM1_NIM2/
   ├── index.html          → (jelaskan fungsinya)
   ├── menu.html           → (jelaskan fungsinya)
   ├── about.html          → (jelaskan fungsinya)
   ├── reservation.html    → (jelaskan fungsinya)
   ├── css/
   │   ├── style.css       → (jelaskan fungsinya)
   │   └── responsive.css  → (jelaskan fungsinya)
   └── images/             → (jelaskan isi foldernya)
   ```

2. **Teknologi yang Digunakan**
   
   a. **HTML5 Features:**
   - Sebutkan minimal 5 elemen semantik HTML5 yang digunakan
   - Jelaskan mengapa memilih elemen tersebut
   - Berikan contoh penggunaan dalam project
   
   b. **CSS Techniques:**
   - Sebutkan teknik CSS yang diimplementasikan (Flexbox, Grid, Variables, dll)
   - Jelaskan bagaimana penerapannya dalam project
   - Berikan screenshot hasil implementasi
   
   c. **Tools & Resources:**
   - Editor code yang digunakan
   - Browser untuk testing
   - Tools kolaborasi
   - Sumber assets (images, fonts, icons)

3. **Color Scheme & Typography**
   
   a. Tampilkan color palette yang digunakan:
   - Primary Color: (kode warna + contoh penggunaan)
   - Secondary Color: (kode warna + contoh penggunaan)
   - Accent Color: (kode warna + contoh penggunaan)
   - Background: (kode warna + contoh penggunaan)
   - Text Color: (kode warna + contoh penggunaan)
   
   b. Font yang digunakan:
   - Heading Font: (nama font + alasan pemilihan)
   - Body Font: (nama font + alasan pemilihan)

---

### BAGIAN 4: PEMBAGIAN TUGAS & KONTRIBUSI

**Jawab dengan detail:**

1. **Pembagian Tugas Anggota 1**
   - Halaman HTML yang dikerjakan: (sebutkan)
   - CSS yang dikerjakan: (sebutkan bagian-bagian)
   - Fitur khusus yang diimplementasikan: (sebutkan)
   - Estimasi waktu pengerjaan: (berapa jam/hari)
   - Persentase kontribusi: (%)

2. **Pembagian Tugas Anggota 2**
   - Halaman HTML yang dikerjakan: (sebutkan)
   - CSS yang dikerjakan: (sebutkan bagian-bagian)
   - Fitur khusus yang diimplementasikan: (sebutkan)
   - Estimasi waktu pengerjaan: (berapa jam/hari)
   - Persentase kontribusi: (%)

3. **Tugas yang Dikerjakan Bersama**
   - Sebutkan bagian-bagian yang dikerjakan bersama
   - Bagaimana cara membagi pekerjaan bersama ini?
   - Waktu yang dihabiskan untuk bagian ini

---

### BAGIAN 5: PROSES PENGEMBANGAN

**Jawab pertanyaan berikut:**

1. **Timeline Pengerjaan**
   
   Buat timeline dalam bentuk tabel:
   
   | Tanggal | Aktivitas | Anggota | Status |
   |---------|-----------|---------|--------|
   | DD/MM | Planning & Design | Semua | Selesai |
   | DD/MM | HTML Structure | ... | ... |
   | DD/MM | CSS Styling | ... | ... |
   | ... | ... | ... | ... |

2. **Metodologi Kolaborasi**
   
   a. **Bagaimana cara kolaborasi dilakukan?**
   - Tools komunikasi yang digunakan (WhatsApp, Discord, dll)
   - Frekuensi meeting/diskusi
   - Platform untuk sharing code
   
   b. **Penggunaan Git/GitHub**
   - Link repository GitHub:
   - Jumlah total commits:
   - Distribusi commits per anggota:
   - Screenshot commit history
   - Screenshot contributors graph
   
   c. **Pembagian Waktu Pengerjaan**
   - Kapan waktu yang digunakan untuk coding?
   - Berapa total jam yang dihabiskan?
   - Apakah ada pembagian waktu khusus?


### BAGIAN 6: CHALLENGES & SOLUTIONS

**Jawab pertanyaan berikut dengan lengkap:**

1. **Tantangan Teknis yang Dihadapi**
   
   Sebutkan minimal 3 tantangan teknis:
   
   **Tantangan 1:**
   - Masalah: (jelaskan detail masalahnya)
   - Kapan terjadi: (pada bagian apa)
   - Solusi: (bagaimana menyelesaikannya)
   - Pembelajaran: (apa yang dipelajari)
   - Screenshot (jika ada)
   
   **Tantangan 2:**
   - Masalah:
   - Kapan terjadi:
   - Solusi:
   - Pembelajaran:
   - Screenshot (jika ada)
   
   **Tantangan 3:**
   - Masalah:
   - Kapan terjadi:
   - Solusi:
   - Pembelajaran:
   - Screenshot (jika ada)

2. **Tantangan Kolaborasi**
   
   a. Apakah ada kesulitan dalam berkolaborasi? Jelaskan!
   b. Bagaimana cara mengatasi perbedaan pendapat dalam kelompok?
   c. Apa yang bisa diperbaiki untuk kolaborasi yang lebih baik?

3. **Hal yang Paling Sulit**
   
   a. Bagian mana yang paling sulit dikerjakan? Mengapa?
   b. Berapa lama waktu yang dihabiskan untuk bagian tersebut?
   c. Apa strategi yang digunakan untuk mengatasinya?

---

### BAGIAN 7: SCREENSHOT & DOKUMENTASI VISUAL

**Sertakan screenshot berikut:**

1. **Screenshot Halaman Lengkap**
   - Homepage (Desktop view)
   - Menu Page (Desktop view)
   - About Page (Desktop view)
   - Reservation Page (Desktop view)

2. **Screenshot Responsive Design**
   - Homepage (Mobile view)
   - Menu Page (Tablet view)
   - Form Reservation (Mobile view)

3. **Screenshot Fitur Interaktif**
   - Hover effects pada buttons
   - Navigation menu
   - Menu cards dengan hover
   - Form dengan validation
   - Gallery section

4. **Screenshot Code**
   - Contoh HTML semantik yang digunakan
   - Contoh CSS Variables
   - Contoh Flexbox/Grid implementation
   - Contoh media queries

---

### BAGIAN 8: ANALISIS & REFLEKSI

**Jawab pertanyaan reflektif berikut:**

1. **Evaluasi Hasil Kerja**
   
   a. **Apa yang sudah berhasil dikerjakan dengan baik?**
   - Sebutkan minimal 3 hal yang berhasil
   - Jelaskan mengapa bisa berhasil
   
   b. **Apa yang masih bisa ditingkatkan?**
   - Sebutkan minimal 3 area improvement
   - Jelaskan rencana perbaikannya
   
   c. **Apakah project ini sudah memenuhi requirements?**
   - Ya/Tidak, jelaskan alasannya
   - Checklist requirements yang terpenuhi

2. **Pembelajaran yang Didapat**
   
   **Anggota 1:**
   - Skill teknis apa yang dipelajari?
   - Skill non-teknis apa yang dipelajari?
   - Apa yang paling berkesan?
   
   **Anggota 2:**
   - Skill teknis apa yang dipelajari?
   - Skill non-teknis apa yang dipelajari?
   - Apa yang paling berkesan?

3. **Rencana Pengembangan Lanjutan**
   
   a. Jika diberi waktu lebih, apa yang ingin ditambahkan?
   b. Fitur apa yang ingin diimplementasikan selanjutnya?
   c. Apakah website ini akan dikembangkan lebih lanjut?

---


### BAGIAN 9: REFERENSI & SUMBER

**Cantumkan semua sumber yang digunakan:**

1. **Sumber Pembelajaran**
   - Tutorial yang diikuti (link)
   - Dokumentasi yang dibaca (link)
   - Video tutorial (link)

2. **Assets & Resources**
   - **Images:** 
     - Sumber (Unsplash, Pexels, dll)
     - Link spesifik untuk setiap gambar
   - **Icons:**
     - Library yang digunakan (Font Awesome, dll)
     - Link CDN
   - **Fonts:**
     - Google Fonts yang digunakan
     - Link import

3. **Inspirasi Design**
   - Website referensi (link)
   - Color palette tools (link)
   - Layout inspiration (link)

4. **Tools yang Digunakan**
   - Code Editor: (nama & versi)
   - Browser: (nama & versi)
   - Git/GitHub: (link repository)
   - Collaboration tools: (nama tools)
   - Screenshot tools: (nama tools)

---

### LAMPIRAN

1. **Link GitHub Repository:** [sertakan link]
2. **Link Website hasil deploy :** [sertakan link]
4. **Video Demo (optional) (NILAI PLUS ):** [link drive]

---

### PERNYATAAN

**Sertakan pernyataan berikut yang ditandatangani oleh semua anggota:**

"Kami menyatakan bahwa laporan dan project ini adalah hasil karya kelompok kami sendiri. Kami memahami dan dapat menjelaskan seluruh code yang telah kami buat. Kami siap untuk melakukan demo dan wawancara terkait project ini."

**Tanda Tangan:**

Anggota 1: _________________ Tanggal: _______

Anggota 2: _________________ Tanggal: _______

---

## KETENTUAN LAPORAN:

1. **Format File:**
   - Format: PDF
   - Nama file: `LAPORAN_KELOMPOK_XX_NIM1_NIM2.pdf`
   - Contoh: `LAPORAN_KELOMPOK_05_2024001_2024002.pdf`

2. **Format Penulisan:**
   - Font: Arial atau Times New Roman
   - Size: 12pt untuk body text, 14pt-16pt untuk heading
   - Line spacing: 1.5
   - Margin: 2.5cm (semua sisi)
   - Halaman: Diberi nomor

3. **Panjang Laporan:**
   - Minimal: 12 halaman (tidak termasuk cover dan lampiran)
   - Maksimal: 30 halaman
   - Sertakan banyak screenshot dan visual

---

## CATATAN PENTING

1. **Submission**:
   - Link Github Repository (Buat 1 repository, bisa invite salah satu / dua anggotanya untuk jadi collaborator)
   - Deadline: [Nanti Dibicarakan]
   - Late submission: -1 poin per detik

2. **Version Control**:
   - Gunakan Git/GitHub untuk kolaborasi
   - Commit history akan menunjukkan kontribusi masing-masing
   - Sertakan link repository jika menggunakan GitHub

---

## CARA KOLABORASI MENGGUNAKAN GITHUB

### Setup Repository (Dilakukan oleh 1 anggota):

1. **Buat Repository Baru di GitHub:**
   - Login ke GitHub
   - Klik tombol "New Repository"
   - Nama repository: `kopi-santai-website` (atau nama lain)
   - Pilih "Public" atau "Private"
   - Centang "Add a README file"
   - Klik "Create Repository"

2. **Menambahkan Collaborator:**
   - Di halaman repository, klik tab **"Settings"**
   - Di sidebar kiri, klik **"Collaborators"** (atau "Manage Access")
   - Klik tombol **"Add people"**
   - Masukkan username GitHub atau email anggota kelompok lainnya
   - Klik "Add [username] to this repository"
   - Anggota lain akan menerima email invitation

3. **Anggota Lain Accept Invitation:**
   - Cek email untuk invitation dari GitHub
   - Atau buka link invitation yang dikirim
   - Klik "Accept Invitation"
   - Sekarang kedua anggota punya akses untuk push/pull ke repository

### Workflow Kolaborasi:

#### Clone Repository (Kedua Anggota):
```bash
# Clone repository ke komputer masing-masing
git clone https://github.com/username/kopi-santai-website.git
cd kopi-santai-website
```

#### Bekerja dengan Branch (Recommended):

**Anggota 1 - Mengerjakan Home & Menu:**
```bash
# Buat branch baru untuk halaman home
git checkout -b feature/home-page

# Setelah selesai coding
git add .
git commit -m "Add home page with hero section and featured menu"
git push origin feature/home-page

# Buat branch untuk menu
git checkout -b feature/menu-page
# ... coding ...
git add .
git commit -m "Add menu page with filter and grid layout"
git push origin feature/menu-page
```

**Anggota 2 - Mengerjakan About & Reservation:**
```bash
# Buat branch baru untuk halaman about
git checkout -b feature/about-page

# Setelah selesai coding
git add .
git commit -m "Add about page with gallery and location"
git push origin feature/about-page

# Buat branch untuk reservation
git checkout -b feature/reservation-page
# ... coding ...
git add .
git commit -m "Add reservation page with form validation"
git push origin feature/reservation-page
```

#### Merge ke Main Branch:
```bash
# Setelah review, merge branch ke main
git checkout main
git pull origin main  # Update main branch terlebih dahulu
git merge feature/home-page
git push origin main
```

#### Best Practices:

1. **Commit Sering dengan Pesan Jelas:**
   ```bash
   git add index.html
   git commit -m "Add hero section structure"
   
   git add css/style.css
   git commit -m "Add navigation styling with hover effects"
   ```

2. **Pull Sebelum Push:**
   ```bash
   # Selalu pull dulu sebelum push untuk hindari conflict
   git pull origin main
   git push origin main
   ```

3. **Komunikasi Saat Mengerjakan File yang Sama:**
   - Koordinasi jika mengerjakan file CSS yang sama
   - Gunakan comment untuk marking siapa yang mengerjakan apa
   ```css
   /* Navigation Styling - Anggota 1 */
   .navbar { }
   
   /* Footer Styling - Anggota 2 */
   .footer { }
   ```

4. **Resolve Conflicts Jika Terjadi:**
   ```bash
   # Jika terjadi conflict saat merge
   git pull origin main
   # Edit file yang conflict
   # Pilih versi yang benar atau gabungkan
   git add .
   git commit -m "Resolve merge conflict"
   git push origin main
   ```

### Struktur Commit Message yang Baik:

```
Add: Menambahkan fitur baru
Update: Mengubah/memperbaiki yang sudah ada
Fix: Memperbaiki bug
Style: Perubahan styling saja
Docs: Update dokumentasi
```

Contoh:
- `Add hero section to home page`
- `Update menu card styling with hover effects`
- `Fix navigation responsive on mobile`
- `Style button variants primary and secondary`
- `Docs: Update README with project description`


**GOOD LUCK & HAPPY CODING! ☕🚀**

*"Good code is its own best documentation." - Steve McConnell*

*"Coming together is a beginning, staying together is progress, and working together is success." - Henry Ford*
