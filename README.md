<div align="center">

  # 💧 LIQUID UI
  ### ⚡ Kumpulan Komponen UI Web · Animasi Halus · HTML + CSS + JS Murni ⚡

  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#-tech-stack--teknologi)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#-tech-stack--teknologi)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-tech-stack--teknologi)
  [![Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen?style=for-the-badge)](#-tech-stack--teknologi)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](#-lisensi)
  [![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](#)

  <p align="center">
    <a href="https://morelaa.github.io/liquid-ui/">
      <img src="https://img.shields.io/badge/🌐_LIVE_DEMO-Klik_di_sini-00c853?style=for-the-badge" alt="Live Demo" />
    </a>
  </p>

  <p align="center">
    <a href="https://morelaa.github.io/liquid-ui/">
      <img src="preview.png" alt="Preview Liquid UI" width="85%" />
    </a>
  </p>

  <p align="center">
    <b>Koleksi komponen antarmuka web dalam satu file <code>index.html</code>, tanpa framework dan tanpa library.</b>
    <br />
    <i>15 komponen interaktif: navigasi liquid, sidebar, login slider, dropdown, kartu 3D, glassmorphism, neumorphism, dan dukungan mode gelap.</i>
  </p>

  ---

  [🌐 Live Demo](https://morelaa.github.io/liquid-ui/) •
  [🛠️ Tech Stack](#-tech-stack--teknologi) •
  [✨ Fitur Unggulan](#-fitur-unggulan) •
  [🧱 Daftar Komponen](#-daftar-komponen) •
  [📂 Struktur Project](#-struktur-project) •
  [🚀 Cara Pakai](#-cara-pakai) •
  [🌐 Deploy GitHub Pages](#-deploy-ke-github-pages) •
  [🎨 Kustomisasi](#-kustomisasi)

</div>

<br />

---

## 🛠️ Tech Stack & Teknologi

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=black" alt="SVG" />
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" />
</p>

| Komponen | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Struktur** | `HTML5` | Satu file `index.html`, semua komponen di satu halaman |
| **Styling** | `CSS3` | Flexbox, grid, CSS variable, transition, `backdrop-filter`, `perspective` 3D |
| **Interaksi** | `JavaScript` vanilla | Toggle class, event listener, filter pencarian, efek tilt mengikuti kursor |
| **Ikon** | `SVG` inline | Semua ikon digambar langsung di HTML, tanpa icon font dan tanpa request tambahan |
| **Tema** | `prefers-color-scheme` | Mode gelap otomatis mengikuti pengaturan perangkat |
| **Hosting** | `GitHub Pages` | Gratis, langsung tampil sebagai website |

<br />

---

## 🌟 Fitur Unggulan

<table>
  <tr>
    <td width="50%">
      <h3>🪶 Nol Dependensi</h3>
      <p>Tidak ada <code>npm install</code>, tidak ada CDN, tidak ada font eksternal. Cukup satu file, buka di browser, langsung jalan.</p>
    </td>
    <td width="50%">
      <h3>💧 Animasi Liquid</h3>
      <p>Indikator navigasi yang meluncur dengan lekukan cair, blob menu yang berpindah, dan panel login yang bergeser dengan transisi berurutan.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>📱 Responsif & Touch Friendly</h3>
      <p>Layout fleksibel sampai lebar HP, efek hover punya padanan <code>:active</code> untuk layar sentuh, dan memakai safe-area untuk perangkat berponi.</p>
    </td>
    <td width="50%">
      <h3>🌙 Mode Gelap Otomatis</h3>
      <p>Warna diatur lewat CSS variable dan otomatis berubah saat perangkat memakai mode gelap. Sidebar dashboard juga punya toggle dark mode sendiri.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🧊 Glass & Neumorphism</h3>
      <p>Kartu kaca dengan blur, serta tombol neumorphism dengan efek timbul dan tenggelam saat diaktifkan.</p>
    </td>
    <td width="50%">
      <h3>🔍 Pencarian Interaktif</h3>
      <p>Search bar yang melebar saat diklik, plus dropdown pencarian dengan highlight teks yang cocok secara real-time.</p>
    </td>
  </tr>
</table>

<br />

---

## 🧱 Daftar Komponen

| # | Komponen | Kategori | Interaksi |
|:-:|---|---|---|
| 1 | **Liquid Navigation** | Navigasi | Klik menu, indikator lingkaran berpindah |
| 2 | **Login / Registration Slider** | Form | Klik tombol, panel bergeser |
| 3 | **Social Buttons** | Tombol | Hover, efek 3D dan tooltip |
| 4 | **Sidebar UI** | Navigasi | Tombol buka/tutup |
| 5 | **Search Bar Expand** | Input | Klik, melebar |
| 6 | **Search Dropdown** | Input | Ketik, hasil dan highlight |
| 7 | **Card Stack** | Kartu | Klik, kartu berganti |
| 8 | **Profile Card 3D** | Kartu | Miring mengikuti kursor/sentuhan |
| 9 | **Liquid List Menu** | Navigasi | Hover/klik, blob berpindah |
| 10 | **Flip Menu** | Navigasi | Hover/klik, putar 3D |
| 11 | **Profile Card + Social** | Kartu | Klik, ikon sosial menyebar |
| 12 | **Neumorphism Buttons** | Tombol | Klik, toggle timbul/tenggelam |
| 13 | **Profile Dropdown** | Menu | Klik, buka/tutup |
| 14 | **Glass Cards** | Kartu | Hover, kartu merapat lalu meregang |
| 15 | **Sidebar Dashboard** | Navigasi | Collapse dan dark mode |

<br />

---

## 📂 Struktur Project

```text
📦 liquid-ui
 ├── 📄 index.html    # 🚀 Semua komponen (HTML + CSS + JS dalam satu file)
 └── 📄 README.md     # 📖 Dokumentasi ini
```

> Kalau nanti proyeknya membesar, bagian `<style>` dan `<script>` bisa dipisah ke `style.css` dan `script.js`.

<br />

---

## 🚀 Cara Pakai

### 1. Download atau Clone
```bash
git clone https://github.com/Morelaa/liquid-ui.git
cd liquid-ui
```

### 2. Buka di Browser
Klik dua kali `index.html`, atau jalankan server lokal:
```bash
# opsional, kalau mau pakai server lokal
npx serve .
```

### 3. Ambil Komponen yang Dibutuhkan
Salin blok HTML, CSS, dan JS dari komponen yang kamu mau ke proyekmu sendiri.

> Tidak ada langkah build. Tidak perlu install apa pun.

<br />

---

## 🌐 Deploy ke GitHub Pages

```mermaid
flowchart LR
    A[Upload index.html ke repo] --> B[Settings → Pages]
    B --> C[Deploy from a branch → main / root]
    C --> D[Save]
    D --> E[Tunggu 1-2 menit]
    E --> F[Website live 🎉]
```

Hasil akhirnya bisa dibuka di:

👉 **[https://morelaa.github.io/liquid-ui/](https://morelaa.github.io/liquid-ui/)**

<br />

---

## 🎨 Kustomisasi

Warna utama diatur lewat CSS variable di bagian atas `<style>`:

```css
:root {
  --page-bg: #7d838c;     /* warna latar halaman */
  --primary-bg: #12121f;  /* warna dasar komponen */
  --circle: #fff;         /* warna indikator navigasi */
}
```

Ubah nilainya untuk mengganti tema seluruh komponen. Untuk mode gelap, atur ulang variabel yang sama di dalam blok `@media (prefers-color-scheme: dark)`.

<br />

---

## 🤝 Kontribusi

Saran dan perbaikan sangat diterima. Silakan buat *issue* atau *pull request*.

<br />

---

## 📜 Lisensi

MIT

<div align="center">
  <sub>Built with 💧 by <a href="https://github.com/Morelaa">Morelaa</a></sub>
</div>
