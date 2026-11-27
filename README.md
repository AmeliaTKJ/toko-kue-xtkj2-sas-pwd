# Bakery Enaak

Bakery Enaak adalah platform website profil dan katalog digital untuk toko roti dan kue artisan yang menyajikan aneka produk segar setiap hari. Mengusung estetika **"Espresso & Sage"**, website ini dirancang untuk menghadirkan nuansa hangat, elegan, dan profesional, serta memudahkan pelanggan dalam melihat menu, daftar harga, informasi bahan, hingga memesan kue custom secara online.

---

## 1. Lembar Konsep Usaha
* **Jenis Usaha & Ciri Khas:** Usaha kuliner (*Artisan Bakery & Pastry*) yang bercirikan penggunaan bahan-bahan alami berkualitas tinggi tanpa pengawet buatan, serta melayani kustomisasi kue ulang tahun dan perayaan sesuai permintaan pelanggan.
* **Lokasi & Tahun Berdiri:** Jl. Dandelion No. 8, Pontianak| Berdiri sejak tahun 2024.
* **Pendiri:** Kelompok 4 (X TKJ 2).
* **Target Pelanggan:** Keluarga, pencinta kopi dan pastry, serta masyarakat umum yang membutuhkan produk roti harian maupun kue perayaan khusus.
* **3 Warna Utama & Alasan Memilihnya:**
  1. **Cokelat Tua:** Memberikan kesan hangat, klasik, dan mencerminkan aroma kopi serta roti panggang yang lezat.
  2. **Hijau Sage:** Menghadirkan sentuhan natural, tenang, serta kesan kesegaran alami tanaman herbal.
  3. **Putih:** Melambangkan kebersihan dapur produksi serta kemurnian bahan baku berkualitas tinggi.

---

## 2. Anggota Kelompok & Pembagian Tugas
| Anggota | Tugas Halaman / Sistem | Berkas yang Dikerjakan |
| :--- | :--- | :--- |
| **Andrew** | Halaman Beranda & Halaman Kontak | `index.html`, `styles/index.css`, `pages/contact.html`, `styles/contact.css` |
| **Ryco** | Halaman Tentang Kami & Halaman Galeri | `pages/about.html`, `styles/about.css`, `pages/gallery.html`, `styles/gallery.css` |
| **Madeline** | Halaman Produk & Halaman Harga dan Paket | `pages/products.html`, `styles/products.css`, `pages/pricing.html`, `styles/pricing.css` |
| **Amelia** | Halaman Custom Order, Halaman Bahan & Alergen, serta Sistem CSS Global | `pages/custom-order.html`, `styles/custom-order.css`, `pages/ingredients.html`, `styles/ingredients.css`, `styles/global.css` |

---

## 3. Cara Menjalankan Website
1. Unduh atau *clone* seluruh repositori proyek ini ke dalam komputer Anda.
2. Buka folder proyek menggunakan **Visual Studio Code**.
3. Pasang ekstensi **Live Server**.
4. Klik kanan pada file **`index.html`** di direktori utama, lalu pilih **"Open with Live Server"**.
5. Website akan otomatis terbuka di peramban web (*browser*) bawaan Anda.

---

## 4. Struktur Folder Proyek

```
toko-kue-xtkj2-sas-pwd/
│
├── index.html
├── readme.md
│
├── assets/
│   ├── fonts/
│   │   └── .gitkeep
│   └── images/
│       ├── about/
│       │   └── about-bake-cake.jpg
│       ├── gallery/
│       │   ├── clean-kitchen.jpg
│       │   ├── croissants.jpg
│       │   ├── custom-cake.jpg
│       │   ├── fresh-bread.jpg
│       │   ├── pineapple-tart.jpg
│       │   ├── premium-bread.jpg
│       │   └── slice-cake.jpg
│       ├── hero/
│       │   └── background-bakery.jpg
│       ├── logo/
│       │   └── logo-bakery.jpeg
│       └── products/
│           ├── birthday-cake-products.jpg
│           ├── bread-products.jpg
│           ├── brownies-products.jpg
│           ├── croissant-products.jpg
│           ├── custom-cake-products.jpg
│           ├── kastengel-products.jpg
│           ├── pineapple-tart-products.jpg
│           ├── slice-cake-products.jpg
│           └── snow-white-cookies-products.jpg
│
├── pages/
│   ├── about.html
│   ├── contact.html
│   ├── custom-order.html
│   ├── gallery.html
│   ├── ingredients.html
│   ├── pricing.html
│   └── products.html
│
└── styles/
    ├── about.css
    ├── contact.css
    ├── custom-order.css
    ├── gallery.css
    ├── global.css
    ├── index.css
    ├── ingredients.css
    ├── pricing.css
    └── products.css
```

## 5. Sumber Gambar
| Nama Berkas | Sumber |
| :--- | :--- |
| about-bake-cake.jpg | Sumber berlisensi bebas |
| clean-kitchen.jpg | Sumber berlisensi bebas |
| croissants.jpg | Sumber berlisensi bebas |
| custom-cake.jpg | Sumber berlisensi bebas |
| fresh-bread.jpg | Sumber berlisensi bebas |
| pineapple-tart.jpg | Sumber berlisensi bebas |
| premium-bread.jpg | Sumber berlisensi bebas |
| slice-cake.jpg | Sumber berlisensi bebas |
| background-bakery.jpg | Sumber berlisensi bebas |
| logo-bakery.jpeg | Dibuat sendiri |
| birthday-cake-products.jpg | Sumber berlisensi bebas |
| bread-products.jpg | Sumber berlisensi bebas |
| brownies-products.jpg | Sumber berlisensi bebas |
| croissant-products.jpg | Sumber berlisensi bebas |
| custom-cake-products.jpg | Sumber berlisensi bebas |
| kastengel-products.jpg | Sumber berlisensi bebas |
| pineapple-tart-products.jpg | Sumber berlisensi bebas |
| slice-cake-products.jpg | Sumber berlisensi bebas |
| snow-white-cookies-products.jpg | Sumber berlisensi bebas |

## 6. Catatan Proses (Kendala dan Solusi)

Berikut adalah beberapa kendala selama proses pengerjaan proyek website Bakery Enaak dan cara penyelesaiannya:

* **Kendala 1: Anggota Belum Mengerti Cara Kerja Push dan Pull di Terminal**
  * **Masalah:** Beberapa anggota masih merasa bingung dan asing dalam menggunakan perintah Git melalui *terminal* (seperti `git push`, `git pull`, atau mengatasi *merge conflict*), sehingga proses pengumpulan kode sempat terhambat.
  * **Solusi:** Melakukan sesi *sharing* dan latihan singkat secara bersama-sama untuk mempraktikkan perintah dasar Git, serta membuat panduan langkah seperti screenhoot pada hasil commitnya.

* **Kendala 2: Tampilan Website Kurang Menarik**
  * **Masalah:** Desain awal halaman web terasa terlalu biasa, kurang hidup, dan belum mencerminkan kesan estetis serta hangat layaknya sebuah toko roti profesional.
  * **Solusi:** Melakukan perombakan desain dengan memilih palet warna yang lebih hangat (kombinasi warna cokelat roti dan krem), menambahkan gambar-gambar berkualitas tinggi, serta mempercantik tata letak menggunakan efek *hover* dan *typography* yang lebih rapi.

* **Kendala 3: Kesulitan Menghubungkan File Image ke HTML dan CSS**
  * **Masalah:** Gambar pada website sempat gagal tampil (*broken link*) karena anggota tim mengalami kesulitan dalam menentukan jalur direktori relatif (*relative path*) yang tepat dari file HTML atau CSS menuju folder penyimpanan gambar (`assets/images/`).
  * **Solusi:** Mempelajari kembali konsep dasar penulisan *path* relatif (penggunaan tanda `./` dan `../`), merapikan struktur folder aset, serta memastikan nama file dan ekstensi gambar ditulis dengan benar tanpa spasi atau huruf kapital yang keliru.

## 7. Refleksi Anggota
Berikut adalah refleksi dan kesan pesan dari masing-masing anggota kelompok 4 (XTKJ-2) selama membuat proyek website *Bakery Enaak*:

**Andrew:**
Saya mengalami kendala dalam menulis beberapa baris kode serta merasa bingung ketika hasil tampilannya tidak sesuai dengan yang diinginkan, namun dari hal tersebut saya menyadari betapa pentingnya kerja sama kelompok karena bantuan rekan-rekan tim yang menunjukkan bagian mana yang salah dan yang benar membuat proses belajarnya menjadi lebih terarah, dengan harapan ke depan bisa terus berkembang dalam menguasai pembuatan kode.

**Ryco:**
Saya sempat merasa kesulitan dalam memahami struktur dan arti dari kode-kode yang tertera di dalam Visual Studio Code, sehingga saya belajar untuk tidak menyerah dengan cara mencari tahu sendiri arti dari kode tersebut, serta merasa sangat terbantu dengan dukungan dan bantuan kelompok yang saling tolong-menolong hingga membuat kerja sama ini terasa sangat baik dan keren, dengan harapan dapat terus berkembang menjadi lebih baik ke depannya.

**Madeline:**
Bagian yang paling sulit adalah mengalami kendala teknis saat menggunakan aplikasi Laragon di awal pengerjaan, yang membuatnya memahami bahwa kerja kelompok itu sangat penting karena memungkinkan anggota tim untuk berdiskusi bersama, sehingga menumbuhkan rasa percaya diri dalam bekerja sama dalam berkelompok.

**Amelia:**
Bagian yang paling sulit bagi saya adalah membuat custom order formnya karena sempat merasa bingung, namun saya mencoba untuk memahami kodingannya dan mencobanya sendiri, sehingga memberikan pengalaman berharga tentang pentingnya ketekunan serta dukungan kerja sama tim.
