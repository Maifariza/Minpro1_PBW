<h3 align="center">Portofolio Website</h2>

<p align="center"><em>Maifariza Aulia Dyas - Sistem Informasi Universitas Mulawarman.</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4995b0e5-0e61-47c6-86ad-79eafdb80047" width="75%">
</p>

## Disusun Oleh 

| **Nama**                     | **NIM**     | **Kelas**            |
|------------------------------|------------|-------------------|
| Maifariza Aulia Dyas         | 2409116032 | Sistem Informasi A |

## Deskripsi Project

Project ini adalah website portfolio sederhana yang dibuat menggunakan HTML dan CSS. Website ini berisi informasi tentang diri saya, seperti perkenalan singkat, deskripsi diri, daftar kemampuan (skills), pengalaman, dan sertifikat yang pernah saya dapatkan.

Website ini dibagi menjadi beberapa bagian utama, yaitu Home, About Me, dan Certificates. Tampilan dibuat rapi dan responsif dengan bantuan Bootstrap 5 agar nyaman dilihat di berbagai ukuran layar. Pada bagian skills, saya menggunakan Vue JS untuk menampilkan data dengan lebih terstruktur.

---

## Struktur Project

<img width="235" height="275" alt="Screenshot 2026-02-23 073806" src="https://github.com/user-attachments/assets/caec50cf-7068-4b32-acbd-a1a0f8e561bf" />

Project ini terdiri dari beberapa file dan folder yang memiliki fungsi masing-masing.

- **index.html**

  File ini merupakan file utama yang berisi struktur dan isi website. Semua bagian seperti Home, About Me, dan Certificates ditulis di dalam file ini.

- **style.css**

  File ini digunakan untuk mengatur tampilan website, seperti warna, font, jarak antar elemen, background, dan efek hover. Dengan file ini, tampilan website menjadi lebih rapi dan menarik.

- **assets/**

  Folder ini berisi semua gambar yang digunakan di dalam website, seperti foto profil dan gambar sertifikat. Penyimpanan gambar dalam satu folder membuat project lebih terstruktur dan mudah dikelola.

### _★彡 Home (Hero Section)_

Bagian Home merupakan tampilan pertama yang dilihat saat website dibuka. Di bagian ini terdapat sapaan singkat, nama lengkap, serta peran sebagai Web Developer. Selain itu, terdapat deskripsi singkat mengenai minat di bidang Web Development.

Pada bagian ini juga terdapat dua tombol navigasi yang mengarah ke section About Me dan Certificates. Layout disusun menggunakan sistem grid dari Bootstrap agar tampilan tetap rapi dan seimbang antara teks dan gambar. Background dibuat menggunakan warna dan gradient agar terlihat lebih menarik.

<img width="1895" height="948" alt="Screenshot 2026-02-23 074417" src="https://github.com/user-attachments/assets/c1754919-8526-423b-b539-19167f9dc56d" />


### _★彡 About Me Section_

Section About Me berisi informasi lebih lengkap tentang diri saya. Bagian ini dibagi menjadi tiga bagian utama, yaitu Deskripsi Diri, Skills, dan Pengalaman.

<img width="1873" height="949" alt="Screenshot 2026-02-23 074508" src="https://github.com/user-attachments/assets/af0d22fd-7de8-47e1-9ab8-aa77fa0ae7f5" />


- **Deskripsi Diri**
  
  Bagian ini berisi penjelasan singkat mengenai kepribadian, minat, dan semangat belajar dalam bidang teknologi.

- **Skills**
  
  Bagian skills menampilkan daftar kemampuan yang saya miliki, seperti HTML, CSS, JavaScript, dan lainnya. Setiap skill ditampilkan dalam bentuk progress bar untuk menunjukkan tingkat pemahaman.
  
  Progress bar dibuat menggunakan komponen Bootstrap. Data skills ditampilkan menggunakan Vue JS agar lebih terstruktur dan mudah dikelola.

- **Pengalaman**
  
  Bagian pengalaman berisi beberapa kegiatan dan pengalaman yang pernah saya lakukan, seperti mengikuti workshop, mengerjakan mini project, dan kegiatan kampus.


### _★彡 Certificates Section_

Section Certificates menampilkan daftar sertifikat yang pernah saya peroleh. Sertifikat ditampilkan dalam bentuk card dan disusun menggunakan sistem grid Bootstrap agar rapi dan responsif.

Setiap card berisi gambar sertifikat, judul kegiatan, tahun, serta tombol “Lihat” untuk membuka gambar sertifikat secara lebih jelas. Penggunaan card dan grid membantu tampilan tetap teratur di berbagai ukuran layar.

<img width="1874" height="936" alt="image" src="https://github.com/user-attachments/assets/4567ad52-f897-4b0d-a919-d8d1c96c3fff" />


**Klik Lihat**

<img width="364" height="407" alt="image" src="https://github.com/user-attachments/assets/a302b6a0-b1f8-4895-a205-ef3a2ef302dd" />

---

### Teknologi yang Digunakan

Dalam pembuatan website ini, saya menggunakan beberapa teknologi dasar yang telah dipelajari, yaitu:

╰┈➤ **HTML**

HTML digunakan untuk membuat struktur dasar website. Semua bagian seperti navbar, section Home, About Me, Certificates, dan Footer disusun menggunakan elemen-elemen HTML.

╰┈➤ **CSS**

CSS digunakan untuk mengatur tampilan website agar lebih rapi dan menarik. Melalui CSS, saya mengatur warna, font, jarak antar elemen, background, serta efek hover pada card dan tombol.

╰┈➤ **Bootstrap 5**

Bootstrap 5 digunakan untuk membantu dalam pengaturan layout dan responsivitas website. Dengan sistem grid seperti container, row, dan col, tampilan website dapat menyesuaikan berbagai ukuran layar. Selain itu, beberapa komponen seperti navbar, card, button, dan progress bar juga menggunakan Bootstrap

╰┈➤ **Vue JS**

Vue JS digunakan pada bagian skills untuk menampilkan data secara lebih terstruktur. Data kemampuan disimpan dalam bentuk array dan ditampilkan menggunakan fitur seperti v-for dan interpolation ({{ }}). Meskipun menggunakan Vue, website ini tetap bersifat statis karena data tidak diambil dari luar.
