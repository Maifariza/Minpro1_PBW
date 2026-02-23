<h2 align="center">Portofolio Website</h2>

<p align="center"><em>Maifariza Aulia Dyas - Sistem Informasi Universitas Mulawarman.</em></p>

## Disusun Oleh 

| **Nama**                     | **NIM**     | **Kelas**            |
|------------------------------|------------|-------------------|
| Maifariza Aulia Dyas         | 2409116032 | Sistem Informasi A |

## Deskripsi Project

Project ini adalah website portfolio sederhana yang dibuat menggunakan HTML dan CSS. Website ini berisi informasi tentang diri saya, seperti perkenalan singkat, deskripsi diri, daftar kemampuan (skills), pengalaman, dan sertifikat yang pernah saya dapatkan.

Website ini dibagi menjadi beberapa bagian utama, yaitu Home, About Me, dan Certificates. Saya membuat tampilan website ini rapi dan responsif dengan bantuan Bootstrap 5 agar nyaman dilihat di berbagai ukuran layar. Pada bagian skills, saya menggunakan Vue JS untuk menampilkan data dengan lebih terstruktur.

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

---

## Tampilan Website (Full)


---

## Tampilan Setiap Section

### _★彡 Home (Hero Section)_

Bagian Home merupakan tampilan pertama yang dilihat saat program di running dan website dibuka. Di bagian ini terdapat sapaan singkat, nama lengkap, serta peran sebagai Web Developer. Selain itu, terdapat deskripsi singkat mengenai minat di bidang Web Development.

Pada bagian ini juga terdapat dua tombol navigasi yang mengarah ke section About Me dan Certificates. Layout disusun menggunakan sistem grid dari Bootstrap agar tampilan tetap rapi dan seimbang antara teks dan gambar. Background dibuat menggunakan warna dan gradient agar terlihat lebih menarik.

<img width="1895" height="948" alt="Screenshot 2026-02-23 074417" src="https://github.com/user-attachments/assets/c1754919-8526-423b-b539-19167f9dc56d" />

--- 

### _★彡 About Me Section_

Section About Me berisi informasi lebih lengkap tentang diri saya. Bagian ini dibagi menjadi tiga bagian utama, yaitu Deskripsi Diri, Skills, dan Pengalaman. Selain itu, pada section ini saya juga menekankan keseimbangan antara informasi personal dan kemampuan teknis. Jadi tidak hanya menjelaskan siapa saya, tetapi juga menunjukkan apa yang bisa saya lakukan dan pengalaman apa saja yang sudah saya jalani.

<img width="1873" height="949" alt="Screenshot 2026-02-23 074508" src="https://github.com/user-attachments/assets/af0d22fd-7de8-47e1-9ab8-aa77fa0ae7f5" />


---

### _★彡 Certificates Section_

Section Certificates menampilkan daftar sertifikat yang pernah saya peroleh. Sertifikat ditampilkan dalam bentuk card dan disusun menggunakan sistem grid Bootstrap agar rapi dan responsif.

Setiap card berisi gambar sertifikat, judul kegiatan, tahun, serta tombol “Lihat” untuk membuka gambar sertifikat secara lebih jelas. Penggunaan card dan grid membantu tampilan tetap teratur di berbagai ukuran layar.

<img width="1874" height="936" alt="image" src="https://github.com/user-attachments/assets/4567ad52-f897-4b0d-a919-d8d1c96c3fff" />


---

## Penjelasan Code Setiap Section

### **📌 Kode Section Home (Hero Section)**



<img width="824" height="591" alt="image" src="https://github.com/user-attachments/assets/82a295f8-5680-40cc-8df4-474677adb161" />

<Penjelasan:>

Secara umum, pada section Home saya membuat struktur utama menggunakan elemen <section yang dibagi menjadi dua kolom menggunakan sistem grid Bootstrap. Kolom pertama berisi teks perkenalan seperti nama, role, dan deskripsi singkat. Kolom kedua berisi gambar profil dengan tambahan elemen dekoratif.

Kode di section Home ini berfungsi untuk menampilkan identitas saya sebagai pembuka website. Saya menggunakan heading untuk struktur teks, button untuk navigasi ke section lain, dan grid Bootstrap untuk memastikan tampilannya tetap responsif di berbagai ukuran layar.

- Kode Struktur Section 

  > <img width="343" height="62" alt="image" src="https://github.com/user-attachments/assets/d1b7467e-de73-4ac4-b979-b69a47b7bd90" />
  >
  > Pada bagian Hero, saya membuat struktur utama menggunakan section id="home">. Saya pakai id="home" supaya bisa terhubung langsung dengan navbar. Jadi ketika tombol “Home” ditekan, halaman otomatis scroll ke bagian ini tanpa reload.

- Kode Grid Layout 

  > <img width="345" height="43" alt="image" src="https://github.com/user-attachments/assets/a6b95394-66c6-4cdf-bf79-b60e8bbc1261" />
  >
  > Saya sengaja pakai sistem grid Bootstrap supaya layout-nya responsif. Jadi di layar besar tampil dua kolom (teks dan gambar berdampingan), tapi kalau di layar kecil otomatis turun jadi satu kolom. Dengan cara ini, saya tidak perlu menulis media query manual.

- Kode Heading 

  > <img width="490" height="32" alt="image" src="https://github.com/user-attachments/assets/7c0000ac-e285-48e0-af52-48de68c3d2ff" />
  >
  > Saya menggunakan button class btn dari Bootstrap untuk styling dasar, lalu saya kombinasikan dengan CSS sendiri agar warnanya sesuai tema pink yang saya gunakan.

- Kode Button 

  > <img width="345" height="47" alt="image" src="https://github.com/user-attachments/assets/cbb2c81c-21a3-48e8-9cd7-15606f1dd291" />
  >
  > Untuk gambar, saya menggunakan kode diatas. Lingkaran itu saya buat di CSS menggunakan position: absolute agar terlihat seperti background dekoratif.
  > Kemudian saya tambahkan efek mask gradient di .hero-img supaya bagian bawah foto terlihat lebih halus dan menyatu dengan background.



---

### **📌 Kode Section About**

<img width="888" height="201" alt="image" src="https://github.com/user-attachments/assets/4b066c5a-c924-4e11-9325-80eba0846e5e" />

<Penjelasan:>

Pada section About, struktur kodenya dibagi menjadi tiga bagian utama dalam satu baris, yaitu Deskripsi, Skills, dan Pengalaman. Saya menggunakan container dan row dari Bootstrap untuk mengatur layout agar rapi dan responsif.

Setiap bagian dibungkus dalam card supaya tampilannya terstruktur dan konsisten. Untuk bagian Skills, saya menggunakan Vue JS agar data skill ini bisa ditampilkan secara dinamis melalui perulangan.

Kode di section ini berfungsi untuk menampilkan informasi yang lebih detail tentang diri saya, baik dari sisi kepribadian, kemampuan teknis, maupun pengalaman yang pernah saya lakukan.

- Kode Struktur Section About

  > <img width="268" height="45" alt="image" src="https://github.com/user-attachments/assets/f10c530e-2d20-405c-811f-01b6866d080a" />
  >
  > Pada bagian ini, saya membuat section About menggunakan <section id="about". Saya memberikan id="about" supaya bisa terhubung langsung dengan tombol “About Me” di tampilan Home (Hero) dan juga dari navbar.
  > Class py-5 berasal dari Bootstrap yang berfungsi memberikan padding atas dan bawah agar section ini tidak terlalu rapat dengan section sebelumnya.
  > Saya juga menggunakan container agar isi kontennya tetap berada dalam batas lebar yang rapi dan tidak terlalu melebar di layar besar.

- Kode Judul dan Deskripsi Singkat Section

  > <img width="839" height="91" alt="image" src="https://github.com/user-attachments/assets/151e93f5-8933-4da2-9f9d-be67e5b8ee48" />
  >
  > Kode ini digunakan untuk membuat judul section dan deskripsi singkat. Saya menggunakan text-center agar teks rata tengah, text-danger untuk warna merah sesuai tema website yang saya mau, dan Class fw-bold membuat judul terlihat lebih tegas.
  > Selain itu, saya menggunakan mb-3 dan mb-5 untuk mengatur jarak antar elemen supaya tampilannya tidak terlalu rapat. Dengan pengaturan ini, judul terlihat lebih menonjol dan berfungsi sebagai pembatas yang jelas antara satu section dengan section lainnya.

Setelah menampilkan judul dan gambaran singkat tentang diri saya, selanjutnya saya membagi Section About menjadi tiga bagian utama. Bagian pertama adalah Deskripsi Diri, lalu Skills, dan terakhir Pengalaman.

a. **Deskripsi**

> <img width="1052" height="239" alt="image" src="https://github.com/user-attachments/assets/5ddce4ab-13e8-4cc0-8646-80a5165bfbca" />
>
> Pada bagian Deskripsi Diri, saya menggunakan struktur card dari Bootstrap untuk membungkus isi teks. Kode ini berfungsi untuk membuat tampilan deskripsi terlihat rapi dan terpisah dari bagian lain.
>
> Penggunaan col-md-4 berfungsi agar bagian ini menjadi satu kolom dari tiga kolom dalam satu baris ketika dibuka di layar besar. Sedangkan di layar kecil, otomatis turun ke bawah. Elemen <h5 digunakan sebagai judul “Deskripsi Diri”, dan <p digunakan untuk isi penjelasan. Jadi secara fungsi, kode ini menampilkan informasi tentang diri saya dalam bentuk yang terstruktur dan mudah dibaca.

b. **Skills**

> <img width="512" height="369" alt="image" src="https://github.com/user-attachments/assets/d0f4b66a-6a2e-4831-a535-f7ea733e4f18" />
>
> Pada bagian Skills, kode berfungsi untuk menampilkan daftar kemampuan beserta levelnya dalam bentuk progress bar. Saya menggunakan v-for untuk melakukan perulangan data skills, sehingga setiap skill di dalam array otomatis ditampilkan tanpa harus menulis ulang struktur HTML. Artinya, kalau saya menambahkan skill baru di data Vue, maka otomatis akan muncul di tampilan.
>
> Progress bar Bootstrap digunakan untuk menampilkan visual tingkat kemampuan. Lebarnya diatur menggunakan binding :style yang mengambil nilai dari skill.level. Jadi fungsi kodenya adalah menghubungkan data dengan tampilan secara dinamis. Bagian ini membuat daftar skill menjadi lebih visual dan tidak hanya berupa teks biasa.

c. **Pengalaman**

> <img width="754" height="292" alt="image" src="https://github.com/user-attachments/assets/70de077b-b30c-420a-8034-362dc787a36c" />
>
> Pada bagian Pengalaman, saya menggunakan struktur list <ul dan <li untuk menampilkan daftar kegiatan. Kegunaan kode ini adalah untuk menyusun pengalaman dalam bentuk poin-poin agar lebih ringkas dan mudah dibaca. Struktur list juga lebih tepat secara HTML dibanding menuliskannya dalam satu paragraf panjang. Card Bootstrap tetap digunakan supaya tampilannya konsisten dengan bagian Deskripsi dan Skills.



---


### **📌 Kode Section Certificates**

<img width="981" height="839" alt="image" src="https://github.com/user-attachments/assets/76d5b16b-af5f-4b96-896a-dca874134e8a" />

<Penjelasan:>

Pada section Certificates, saya menggunakan struktur grid Bootstrap untuk menampilkan beberapa card sertifikat dalam bentuk layout yang responsif. Setiap sertifikat dibungkus dalam card yang berisi gambar, judul, tahun, dan tombol untuk melihat detail.

Kode pada bagian ini berfungsi untuk menampilkan bukti pencapaian saya secara visual. Sistem grid memastikan jumlah card dalam satu baris menyesuaikan ukuran layar. Sedangkan tombol “Lihat” memungkinkan pengunjung membuka gambar sertifikat dalam ukuran penuh tanpa meninggalkan halaman utama.

- Kode Struktur Section

  > <img width="609" height="50" alt="image" src="https://github.com/user-attachments/assets/b3b00b94-c316-40a4-a5dc-f74239587f93" />
  >
  > Pada bagian ini, saya membuat section menggunakan <section id="certificates". Penggunaan id="certificates" berfungsi agar section ini bisa terhubung langsung dengan tombol navigasi di navbar maupun tombol di Hero menggunakan anchor link.
  >
  > Saya juga menambahkan class py-5 untuk memberikan jarak atas dan bawah agar section ini tidak terlalu rapat dengan section lainnya. Selain itu, saya memberikan sedikit background berbeda supaya bagian Certificates terlihat sebagai section yang terpisah.


- Kode Grid Layout Sertifikat

  > <img width="358" height="94" alt="image" src="https://github.com/user-attachments/assets/81617d98-de9f-43c3-8497-01f13c8da2e3" />
  >
  > Pada bagian ini, saya menggunakan sistem grid dari Bootstrap seperti row, col-md-6, dan col-lg-4 untuk mengatur tata letak card sertifikat. Kode ini berfungsi supaya jumlah card dalam satu baris bisa menyesuaikan dengan ukuran layar.
  > Jadi ketika dibuka di layar besar, dalam satu baris bisa tampil tiga card sekaligus. Kalau di layar ukuran medium, tampil dua card. Sedangkan di layar kecil seperti HP, otomatis turun menjadi satu card per baris.
  >
  > Nah dengan sistem grid ini, tampilan website tetap responsif tanpa perlu menulis pengaturan layout secara manual lagi. Bootstrap sudah menangani penyesuaian tampilannya secara otomatis sesuai ukuran layar.

- Kode Card Sertifikat

  > <img width="752" height="99" alt="image" src="https://github.com/user-attachments/assets/0284b8ed-48ef-431e-8350-c313fc66cd0d" />

  > Pada bagian ini, saya menggunakan komponen card dari Bootstrap untuk membungkus setiap sertifikat. Kode card ini berfungsi untuk memisahkan setiap sertifikat agar tampil lebih terstruktur dan tidak bercampur satu sama lain.
  >
  > Di dalam card terdapat gambar sertifikat, judul kegiatan, dan tahun pelaksanaan. Penggunaan card-img-top berfungsi untuk menampilkan gambar di bagian atas card supaya langsung terlihat. Kemudian bagian card-body digunakan sebagai pembungkus isi teks agar padding dan jaraknya rapi.
  >
  > Saya juga menambahkan shadow-sm supaya card memiliki efek bayangan ringan, sehingga tampilannya tidak terlihat datar banget. Dengan menggunakan card ini, tampilan sertifikat menjadi lebih profesional dan konsisten dengan bagian lain di website.

- Kode Tombol "Lihat"

  > <img width="355" height="99" alt="image" src="https://github.com/user-attachments/assets/6c7e6ebe-27cc-4383-b044-c98c7706c268" />


  > Pada bagian ini, saya menggunakan elemen <a yang diberi class btn dari Bootstrap untuk dijadikan tombol “Lihat”. Kode ini berfungsi agar pengunjung bisa membuka gambar sertifikat dengan ukuran yang full atau penuh.
  >
  > Saya menambahkan atribut target="_blank" supaya ketika tombol ditekan, gambar akan terbuka di tab baru. Tujuannya agar halaman portfolio utama tidak tertutup atau tergantikan. Selain itu, Class seperti btn-outline-danger ini saya gunakan untuk menyesuaikan warna tombol dengan tema website, sedangkan btn-sm membuat ukuran tombol lebih proporsional dan tidak terlalu besar di dalam card.

---

## Teknologi yang Digunakan

Dalam pembuatan website ini, saya menggunakan beberapa teknologi dasar yang telah dipelajari, yaitu HTML, CSS, Bootstrap 5, dan juga Vue Js. 

╰┈➤ **HTML**

<img width="117" height="35" alt="image" src="https://github.com/user-attachments/assets/4c8a7f75-8e10-47e7-a4ac-8c0df48dd04c" />

**HTML** digunakan sebagai struktur dasar dalam membangun website ini. Semua bagian utama seperti navbar, section Home, About Me, hingga Certificates disusun menggunakan elemen-elemen HTML agar konten tersusun dengan rapi dan terstruktur.

- Struktur dasar dokumen

  > <img width="618" height="130" alt="image" src="https://github.com/user-attachments/assets/33c5c0c3-c735-4b67-9cf9-14ad57b95d5c" />
  >
  > HTML digunakan untuk membentuk struktur dasar sebuah halaman website. Pada bagian ini, elemen seperti <!DOCTYPE html, <html, <head, dan <body berfungsi sebagai kerangka utama. Meta charset digunakan untuk mengatur karakter teks, meta viewport untuk membuat tampilan responsif, dan <title untuk menampilkan judul halaman pada tab browser.

- Pembuatan bagian navigasi

  > <img width="370" height="30" alt="image" src="https://github.com/user-attachments/assets/ed098719-0b9c-4c8c-8c5e-90b7294d25b7" />
  >
  > HTML digunakan untuk membuat struktur navigasi menggunakan elemen <nav. Bagian ini berfungsi untuk menghubungkan antar section seperti Home, About, dan Certificates. Dengan struktur ini, pengguna dapat berpindah ke bagian lain dalam satu halaman dengan lebih mudah.

- Pembuatan Section

  > <img width="245" height="84" alt="image" src="https://github.com/user-attachments/assets/8bf4bb94-975b-4fa3-83bb-71c3a668c228" />
  >
  > HTML digunakan untuk membagi konten website menjadi beberapa bagian menggunakan elemen <section. Setiap section diberi id agar dapat terhubung dengan menu navigasi melalui anchor link. Dengan cara ini, struktur website menjadi lebih rapi dan terorganisir.


---

╰┈➤ **CSS**

<img width="116" height="35" alt="image" src="https://github.com/user-attachments/assets/ec84e5ed-bc93-4ecb-a7ef-39c0e6d11aed" />

CSS digunakan untuk mengatur tampilan visual website agar terlihat lebih rapi, menarik, dan memiliki identitas desain yang konsisten. Jika HTML berfungsi sebagai struktur, maka CSS berperan dalam mempercantik dan mengatur bagaimana struktur tersebut ditampilkan di layar.

<img width="646" height="926" alt="image" src="https://github.com/user-attachments/assets/a0c6f87e-dbcd-47d4-8722-d0914cbdc24b" />

---

╰┈➤ **Bootstrap 5**

<img width="212" height="49" alt="image" src="https://github.com/user-attachments/assets/59449d6c-3957-43da-8212-04b079583e12" />

Bootstrap 5 digunakan dalam website ini untuk membantu pengaturan layout, struktur grid, serta komponen UI agar tampilan menjadi responsif dan lebih rapi tanpa harus menulis semua styling dari nol.

Bootstrap dihubungkan melalui CDN berikut:

<img width="810" height="56" alt="image" src="https://github.com/user-attachments/assets/ab1acbd9-6296-4f55-8323-40acb74edd35" />

Dengan menghubungkan file tersebut, saya dapat menggunakan berbagai class bawaan Bootstrap untuk mempercepat proses pembuatan tampilan.

- Grid System

  > <img width="497" height="136" alt="image" src="https://github.com/user-attachments/assets/1a8185fe-9dcf-432d-bee8-c936f21a2747" />
  >
  > Bootstrap digunakan untuk mengatur tata letak menggunakan sistem grid seperti container, row, dan col-lg-6. Grid system ini berfungsi untuk membagi tampilan menjadi beberapa kolom yang dapat menyesuaikan ukuran layar. Dengan cara ini, layout tetap responsif tanpa perlu membuat media query manual.

- Navbar

  > <img width="370" height="59" alt="image" src="https://github.com/user-attachments/assets/d889cb58-35da-4170-a052-625efc55c217" />
  >
  > Bootstrap digunakan untuk membuat navigasi menggunakan class seperti navbar, navbar-expand-lg, dan bg-light. Komponen ini berfungsi untuk menampilkan menu navigasi yang responsif dan otomatis menyesuaikan tampilan di berbagai ukuran layar.

- Button

  > <img width="376" height="37" alt="image" src="https://github.com/user-attachments/assets/8b5b9a24-4285-4610-a80a-2c2c3cdfcdf5" />
  >
  > Bootstrap digunakan untuk membuat tombol dengan class seperti btn, btn-outline-danger, dan btn-sm. Class ini berfungsi untuk memberikan styling tombol secara cepat dan konsisten sesuai tema website.

- Card Component

  > <img width="301" height="66" alt="image" src="https://github.com/user-attachments/assets/efce1a8e-fc66-4a00-b6fa-620c6050e350" />
  >
  > Bootstrap digunakan untuk membungkus konten dalam bentuk card menggunakan class seperti card, card-body, dan shadow-sm. Komponen ini berfungsi untuk membuat tampilan konten seperti sertifikat dan deskripsi terlihat lebih terstruktur dan rapi.



---

╰┈➤ **Vue JS**

<img width="172" height="57" alt="image" src="https://github.com/user-attachments/assets/01411d9a-f77e-4f27-a50c-ca708a2fbf29" />

Vue JS digunakan pada bagian Skills untuk menampilkan data kemampuan secara lebih terstruktur dan dinamis. Data skill saya simpan dalam bentuk array di dalam instance Vue, lalu ditampilkan menggunakan fitur seperti v-for untuk perulangan dan interpolasi {{ }} untuk menampilkan nilai data ke dalam HTML.

Meskipun menggunakan Vue, website ini tetap bersifat statis karena seluruh data ditulis langsung di dalam file dan tidak mengambil data dari database atau API eksternal.

Vue dihubungkan menggunakan CDN berikut:

<img width="533" height="37" alt="image" src="https://github.com/user-attachments/assets/4a64461a-603f-4f9b-8b42-448eee419059" />

Setelah itu, saya membuat instance Vue dengan createApp() yang berisi data skills. Instance ini kemudian di-mount ke elemen dengan id #app, sehingga seluruh bagian di dalam div tersebut dapat menggunakan fitur Vue.

<img width="548" height="372" alt="image" src="https://github.com/user-attachments/assets/447f8e15-0c3f-4c24-becf-70c7f49db803" />


