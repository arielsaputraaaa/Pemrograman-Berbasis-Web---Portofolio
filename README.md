# WEBSITE PORTOFOLIO

NAMA : Mohamad Ariel Saputra D Loi 

NIM : 2409116087

WEBSITE PORTOFOLIO  

<img width="1880" height="1092" alt="image" src="https://github.com/user-attachments/assets/2794040e-52af-4c26-8bec-5cfcd2440b8f" />

## Deskripsi Website

Website ini merupakan website portfolio pribadi yang menampilkan profil, keahlian, serta riwayat pengalaman 
kerja dari seorang Graphic Designer.Website dirancang dengan tampilan modern, clean, responsif, dan memiliki 
animasi interaktif untuk meningkatkan pengalaman pengguna. Tujuan utama dari website ini adalah sebagai media 
personal branding dan dokumentasi profesional yang dapat diakses secara online.

## Struktur Website

+ Navbar

+ Hero Section

+ About Section

+ Skills Section

+ History Section

+ Footer

<img width="771" height="339" alt="image" src="https://github.com/user-attachments/assets/8ca7a371-9bea-40a2-b748-1747558c3340" />

## Penjelasan Tampilan Setiap Section / Fitur

### ==== Navbar

<img width="1887" height="109" alt="image" src="https://github.com/user-attachments/assets/952a2469-81d8-4a6d-a4d8-1b96d81d673c" />

Navbar merupakan bagian navigasi utama yang berada di posisi paling atas halaman dan menggunakan sistem fixed-top sehingga tetap terlihat ketika pengguna melakukan scroll. Navbar dirancang dengan tampilan gelap (dark theme) agar kontras dengan section lainnya serta memberikan kesan profesional.
Menu navigasi dibuat dinamis menggunakan Vue.js sehingga lebih fleksibel dan mudah dikelola.

+ Menggunakan Bootstrap 5 (navbar, navbar-expand-lg) untuk sistem responsive.

+ Posisi tetap di atas menggunakan fixed-top.

+ Menu dibuat dinamis dengan Vue melalui array menus.

+ Menggunakan v-for untuk melakukan perulangan menu.

+ Toggler button dibuat custom dengan CSS (bukan default icon Bootstrap).

+ Animasi slideDown saat halaman pertama kali dimuat.

### ==== Hero Section

<img width="1873" height="877" alt="image" src="https://github.com/user-attachments/assets/e8cf833b-1e5d-4771-b4b0-b4551795c2c7" />

Hero section merupakan bagian pertama yang ditampilkan ketika website dibuka. Section ini memiliki ukuran full screen (100vh) 
dengan background image serta elemen visual utama di tengah. Tujuan dari hero section adalah memberikan kesan pertama yang kuat serta menampilkan identitas visual designer.

+ Menggunakan height: 100vh agar memenuhi layar.

+ Background menggunakan background-image.

+ Elemen gambar utama berada di tengah.

+ Icon Photoshop dan Illustrator diberi animasi floating.

+ Animasi fade dan zoom saat pertama kali muncul.

+ Menggunakan sistem animation CSS dengan @keyframes.

### ==== About Section

<img width="1908" height="895" alt="image" src="https://github.com/user-attachments/assets/29c83cd1-0b19-4510-8c48-00c643873671" />

About section berfungsi untuk menampilkan profil lengkap pemilik portfolio. Section ini berisi foto dan deskripsi diri yang menjelaskan latar belakang serta keahlian utama.
Layout menggunakan sistem grid Bootstrap agar responsif di berbagai ukuran layar.
Menggunakan Bootstrap Grid (row, col-md-5, col-md-7).

+ Layout dua kolom (gambar dan teks).

+ Font khusus (Parisienne) untuk nama agar terlihat elegan.

+ Background abu muda untuk membedakan dengan hero section.

+ Responsive: pada layar kecil akan berubah menjadi layout vertikal.

+ Menggunakan class .reveal untuk animasi saat scroll.

### ==== Skills Section

<img width="1879" height="723" alt="image" src="https://github.com/user-attachments/assets/228cb620-c3c2-436e-8abf-df12dab094bf" />

Skills section menampilkan daftar kemampuan dalam bentuk progress bar dengan persentase 
tingkat penguasaan. Data skills dikelola menggunakan Vue.js sehingga mudah 
ditambahkan atau diubah tanpa mengubah struktur HTML.

### ==== History Section

<img width="1901" height="806" alt="image" src="https://github.com/user-attachments/assets/e6a0d44e-1282-4920-be5e-d0eb3ac9d42f" />

History section menampilkan pengalaman kerja dan pelatihan dalam bentuk card. Informasi ditampilkan secara dinamis menggunakan Vue.js sehingga struktur tetap rapi dan mudah diperbarui. 
Di bagian bawah terdapat tampilan sertifikat sebagai bukti kompetensi.

+ Menggunakan Bootstrap Card.

+ Data pengalaman disimpan dalam array history.

+ Ditampilkan menggunakan v-for.

+ Memiliki hover effect (scale dan translate).

+ Responsive di mobile (full width).

+ Sertifikat ditampilkan dalam container terpisah.

+ Menggunakan animasi reveal saat discroll.

### ==== Footer

<img width="1825" height="126" alt="image" src="https://github.com/user-attachments/assets/b96a05ca-0a8a-4af0-98b2-b9dde272d1cb" />

Footer merupakan bagian penutup website yang berisi informasi hak cipta dan identitas profesi.
Footer dibuat sederhana dengan warna gelap agar konsisten dengan navbar.

## Teknologi yang Digunakan

+ Teknologi yang kamu gunakan adalah:

+ HTML5

+ CSS3

+ Bootstrap

+ Vue.js 

+ Google Fonts


