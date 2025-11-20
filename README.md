
# Cara Menjalankan dan Meng-online-kan CV Modern Ini

Proyek ini merupakan CV Modern berbasis HTML, CSS, dan JavaScript yang dapat dijalankan secara lokal maupun dipublikasikan secara online melalui GitHub Pages, Vercel, atau platform hosting statis lainnya.

## 1. Jalankan Secara Lokal

Kamu bisa menjalankan file ini langsung di perangkat kamu.

### Langkah-langkah:

1. Buat sebuah file baru bernama index.html
2. Salin seluruh kode HTML yang sudah ada ke dalam file tersebut
3. Simpan file
4. Klik dua kali file index.html untuk membuka di browser

Tidak diperlukan server atau instalasi apa pun.

---

## 2. Cara Upload ke GitHub (Agar Bisa Online)

Untuk membuat CV ini online menggunakan GitHub Pages, lakukan langkah berikut:

### Langkah-langkah:

1. Login ke akun GitHub

2. Klik tombol New Repository

3. Nama repository bebas, misalnya:

   ```
   cv-modern
   ```

4. Upload file index.html ke repository tersebut

5. Pergi ke menu:
   Settings → Pages

6. Pada bagian "Build and deployment", pilih:

    Source: Deploy from branch
    Branch: main
    Folder: /(root)

7. Klik Save

Dalam ±10–30 detik website kamu akan online dalam format:

```
https://username.github.io/nama-repository
```

Contoh:

```
https://dikacodes.github.io/cv-modern
```

---

## 3. Deploy ke Vercel (Alternatif Lebih Cepat)

Jika kamu ingin URL lebih pendek dan proses lebih cepat:

### Langkah-langkah:

1. Masuk ke [https://vercel.com](https://vercel.com)
2. Klik Add New → Project
3. Pilih repository GitHub yang berisi file index.html
4. Klik Deploy

Dalam hitungan detik, CV kamu akan online.

---

## Struktur Folder yang Direkomendasikan

Jika suatu hari kamu ingin memisahkan file CSS / JS, gunakan format berikut:

```
/assets
   /css/style.css
   /js/script.js
index.html
```

Namun saat ini, seluruh style & script sudah berada dalam satu file sehingga cukup upload index.html saja.

---

## Responsif & Mobile Friendly

Template CV ini sudah:

 Mendukung mobile & tablet (hamburger menu)
 Animasi fade-in saat scroll
 Background parallax
 Navbar shrink saat discroll

Tidak memerlukan framework tambahan.

---

## Kustomisasi

Silakan ubah bagian berikut sesuai data kamu:

 Nama pada header

  ```
  <h1>Halo, Saya Dika</h1>
  ```
 Deskripsi singkat
 Pendidikan & Pengalaman
 Email & Nomor HP
 Background foto pada CSS:

  ```css
  background: url('https://images.unsplash.com/...') 
  ```

  Bisa diganti dengan URL gambar kamu sendiri.

---
