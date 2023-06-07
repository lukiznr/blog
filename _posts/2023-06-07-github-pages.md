---
layout: post
title:  "GitHub Pages: Membuat Situs Webmu dengan Mudah!"
author: luki
---
Halo teman-teman! Hari ini kita akan membahas tentang GitHub Pages, sebuah fitur menakjubkan yang disediakan oleh GitHub untuk membuat situs web secara gratis. Tanpa perlu repot-repot mengatur hosting, kamu dapat mempublikasikan proyekmu langsung dari repositori GitHub. Ayo, ikuti langkah-langkah di bawah ini!

## Apa itu GitHub Pages?

GitHub Pages adalah layanan hosting statis yang disediakan oleh GitHub. Ini berarti kamu dapat membuat situs web yang berisi file HTML, CSS, dan JavaScript. GitHub Pages akan meng-host dan mempublikasikan situs webmu secara online agar dapat diakses oleh siapa pun di seluruh dunia.

## Cara Menggunakan GitHub Pages

Berikut adalah langkah-langkah mudah untuk menggunakan GitHub Pages:

1. **Buatlah Repositori**: Buatlah repositori baru di GitHub atau gunakan repositori yang sudah ada.
2. **Tambahkan File HTML dan CSS**: Buatlah file HTML dan CSS untuk desain situs webmu. Kamu juga bisa menambahkan file JavaScript jika perlu.
3. **Pindahkan ke Branch `gh-pages`**: Buat branch baru dengan nama `gh-pages` di repositorimu. Inilah branch yang akan digunakan untuk mempublikasikan situs webmu.
4. **Pindahkan File**: Pindahkan file HTML, CSS, dan file pendukung lainnya ke branch `gh-pages`.
5. **Publikasikan Situs Web**: Tunggu beberapa saat, kemudian akses situs webmu dengan URL https://username.github.io/repository. Ganti `username` dengan nama pengguna GitHub-mu dan `repository` dengan nama repositori yang kamu gunakan.

## Tips dan Trivia

- Pastikan file HTML utama kamu bernama `index.html`. GitHub Pages akan secara otomatis menampilkan halaman ini sebagai halaman beranda situs webmu.
- Kamu dapat menggunakan berbagai framework seperti Bootstrap atau CSS preprocessors seperti Sass dalam pengembangan situs webmu di GitHub Pages.
- Jika situs webmu memerlukan formulir atau fungsi server-side, kamu perlu menggunakan layanan hosting yang mendukung server-side seperti Heroku.

## Template HTML dan CSS

Berikut adalah contoh template HTML dan CSS sederhana yang dapat kamu gunakan sebagai titik awal dalam membuat situs web di GitHub Pages:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>GitHub Pages Template</title>
</head>
<body>
  <header>
    <h1>Selamat Datang di Situs Webku!</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#">Beranda</a></li>
      <li><a href="#">Tentang</a></li>
      <li><a href="#">Kontak</a></li>
    </ul>
  </nav>

  <section>
    <h2>Tentang Saya</h2>
    <p>Halo, nama saya John Doe. Saya seorang pengembang web dengan minat dalam HTML, CSS, dan JavaScript.</p>
  </section>

  <footer>
    <p>Hak Cipta &copy; 2023 Situs Webku</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

```css
/* styles.css */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
}

nav li {
  display: inline-block;
  margin: 0;
}

nav li a {
  display: block;
  padding: 10px;
  text-decoration: none;
  color: #333;
}

section {
  padding: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}
```

Sekarang kamu sudah memiliki pengetahuan dasar tentang GitHub Pages dan cara menggunakannya. Segera buat situs web kerenmu sendiri dengan mudah menggunakan GitHub Pages! Selamat mencoba!


Semoga penjelasan di atas dapat membantu kamu memahami konsep dan penggunaan GitHub Pages dengan lebih baik. Jika kamu memiliki pertanyaan lebih lanjut, jangan ragu untuk bertanya. Selamat berkoding! 😄✨