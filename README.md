# 🖨️ Kalkulator Percetakan Visual Pro

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-indigo?style=for-the-badge&logo=github)](https://jefry195.github.io/kalkulator-visual/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Aplikasi web modern interaktif untuk menghitung estimasi ukuran pola bentangan cetak, visualisasi layout kertas plano (SVG Canvas), kalkulasi HPP (Modal), pengaturan margin keuntungan, serta generator penawaran harga WhatsApp otomatis untuk pemilik usaha percetakan dan estimator cetak.

🌐 **Demo Website**: [https://jefry195.github.io/kalkulator-visual/](https://jefry195.github.io/kalkulator-visual/)

---

## 🚀 Fitur Utama

- 📦 **Spesifikasi Produk Kemasan, Buku & Cetak Datar**:
  - Buku / Compro (Jilid Staples Tengah / Manual) & (Jilid Jahit Kawat Mesin / Saddle Stitching)
  - Buku / Catalog (Jilid Lem Panas / Perfect Binding)
  - Buku / Agenda (Jilid Spiral / Wire-O)
  - Dus Lunch Box (1 pcs & 2 pcs gandeng)
  - Rice Box
  - Dine In Tray
  - Kotak Tutup Terpisah (Wadah & Tutup Atas)
  - Mailer Box / Dus Sambung
  - Straight Tuck End (STE) Box
  - Kebab Sleeve
  - Kotak Mug Standard
  - Burger Clamshell Box
  - Custom Flat (Brosur, Kartu Nama, Stiker, Flyer, Amplop, Folio, Nota, Banner)
- 🎨 **Visualisasi Layout Plano Interaktif (SVG Canvas)**:
  - Pratinjau layout potongan pada sheet kertas plano berbasis SVG.
  - Batas bleed (garis putus-putus merah), garis potong, label dimensi real-time, & indikator sisa sheet kertas (*waste percentage*).
  - Varian layout toggle (1 pcs vs 2 pcs gandeng).
- 💡 **Rekomendasi Kertas Plano Otomatis (*Best Value*)**:
  - Deteksi otomatis ukuran kertas plano yang paling efisien sisa bahannya dengan indikator *"⭐ Rekomendasi Terhemat"*.
- 💰 **Kalkulator HPP & Profit Margin Controller**:
  - Slider Margin Profit (%) & input Nominal Profit (Rp) yang mengkalkulasi HPP vs Keuntungan vs Harga Jual Satuan/Total secara otomatis & *real-time*.
  - Dukungan kalkulasi cetak **Mesin Offset Commercial**, **Digital Printing (A3+)**, dan **Sablon Film DTF**.
  - Opsi finishing lengkap: Laminasi (Doff/Glossy 1 & 2 Sisi), Potong Jadi, Lipat Mesin, Spot UV Varnish, Hot Foil / Poly, Kiss Cut Stiker, & Laminating Hard Press.
- 📲 **Generator Format Penawaran WhatsApp & Tier Pricing Display**:
  - Membuat format teks penawaran harga cetak yang rapi, mencantumkan spesifikasi lengkap, tiering harga kuantitas pintar:
    - **Digital Printing / DTF**: Kuantitas kecil-menengah (100, 300, 500, 1.000 pcs) tanpa biaya plat.
    - **Mesin Offset Commercial**: Kuantitas grosir volume besar (1.000, 2.000, 3.000, 5.000, 10.000 pcs) dengan efisiensi biaya plat.
  - Menampilkan visual interaktif *Tier Pricing Cards* di UI serta tombol penyalin teks WhatsApp otomatis.
- 📜 **Riwayat Estimasi Tersimpan (`localStorage`)**:
  - Menyimpan estimasi harga cetak secara lokal untuk dibuka atau dibandingkan kembali kapan saja.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Vanilla JavaScript (ES6+)**: Logika kalkulasi geometri, algoritma laying-out layout campuran, dan render SVG.
- **Tailwind CSS (v3)**: Desain UI modern bertema *dark glassmorphism* dengan efek blur dan gradient.
- **Google Fonts (Plus Jakarta Sans & Inter)**: Tipografi modern dan mudah dibaca.

---

## 💻 Cara Menjalankan Secara Lokal

1. **Clone Repositori**:
   ```bash
   git clone https://github.com/jefry195/kalkulator-visual.git
   cd kalkulator-visual
   ```
2. **Jalankan Aplikasi**:
   - Cukup buka file `index.html` langsung di browser favorit Anda (Google Chrome, Firefox, Edge, Safari).
   - Atau gunakan ekstensi *Live Server* di VS Code.

---

## 📄 Lisensi

Proyek ini dikembangkan untuk kebutuhan operasional percetakan visual dan bebas digunakan serta dikembangkan lebih lanjut.
