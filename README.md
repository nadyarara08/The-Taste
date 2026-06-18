# The Taste Restaurant Website 🍽️

Projek ini adalah sebuah platform website multi-halaman resmi untuk **The Taste**, sebuah restoran *semi-fine dining* modern yang menyajikan perpaduan hidangan Western dan Beverage berkualitas. Website ini dirancang untuk memberikan pengalaman menjelajah menu yang interaktif, menonjolkan estetika ambience restoran, serta mengintegrasikan sistem reservasi meja digital yang mulus untuk pelanggan (*The Tasters*).

## 🚀 Fitur Utama

- **Multi-Page Architecture**: Navigasi halaman yang terstruktur rapi meliputi `Home`, `About`, `Menu`, `Gallery`, dan `Review` untuk menunjang kebutuhan informasi bisnis kuliner yang lengkap.
- **Interactive Menu Navigation**: Menu dinamis yang memisahkan kategori *Beverages* (Tea, Juice, Coffee) dan *Food* (Appetizer, Main Course, Side Dish, Dessert) menggunakan manipulasi DOM JavaScript sehingga perpindahan kategori terasa cepat dan responsif tanpa *reload* halaman.
- **Embedded Reservation System**: Integrasi langsung dengan Google Form reservasi yang sudah dioptimasi dengan sistem percabangan logika (*conditional logic*) untuk fitur *Pre-Order* hidangan sebelum kedatangan.
- **Visual Showcase Gallery**: Bagian galeri estetik berkonsep cerita (*The Food, The Drinks, The Chef Hands, The Ambience, The Story, The Journey*) untuk memperkuat *branding* dan menarik minat calon pengunjung.
- **Customer Social Proof**: Menampilkan ulasan autentik dari pelanggan lengkap dengan sistem rating berbasis ikon *FontAwesome* untuk meningkatkan kredibilitas restoran.

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Menyusun struktur semantik dokumen web di setiap halaman.
- **CSS3**: Mengatur tata letak layout yang modern, tipografi, kombinasi warna, serta animasi transisi menu.
- **JavaScript (ES6)**: Menangani logika interaktivitas fungsi *switch-category* pada halaman menu secara *client-side*.
- **FontAwesome**: Menyediakan aset ikonik sosial media dan sistem rating bintang yang konsisten.

## 📁 Struktur Projek

```text
TheTaste/
│
├── index.html          # Halaman Utama (Welcome & Filosofi)
├── about.html          # Profil Restoran (About Us)
├── menu.html           # Daftar Menu Interaktif (Food & Beverages)
├── gallery.html        # Galeri Estetik (The Journey & Ambience)
├── review.html         # Halaman Testimoni & Ulasan Pelanggan
│
├── css/
│   └── style.css       # Berkas Styling Utama (Layout, Grid, Responsive)
│
└── images/             # Direktori Aset Gambar dan Foto Restoran
