# Portofolio Tita Valen Rivaldo — PCB Designer

Website portofolio satu halaman, dibuat menggunakan HTML, CSS, dan JavaScript biasa agar mudah diedit melalui Visual Studio Code.

## Cara menjalankan di VS Code

1. Ekstrak folder `portfolio_tita` dari file ZIP.
2. Buka Visual Studio Code.
3. Pilih **File → Open Folder**, lalu pilih folder `portfolio_tita`.
4. Cara termudah: pasang ekstensi **Live Server** dari panel Extensions.
5. Klik kanan `index.html` lalu pilih **Open with Live Server**.

Website juga bisa dibuka langsung dengan klik dua kali `index.html`, tetapi Live Server lebih nyaman saat mengedit karena halaman dapat dimuat ulang otomatis.

## Sebelum dipublikasikan

- Ganti ilustrasi SVG di folder `assets/` dengan screenshot atau foto asli hasil proyek. Gambar yang disediakan sekarang hanya ilustrasi visual sementara, bukan hasil asli dari proyek pribadi.
- Cari teks `[Belum diisi]` di `index.html`, kemudian lengkapi informasi yang benar atau hapus bagian yang tidak relevan.
- Konfirmasi nama resmi program studi dan status/tahun pendidikan.
- Ganti `email-kamu@example.com` pada tautan `mailto:` dengan alamat email aktif.
- Tambahkan tautan LinkedIn, GitHub, dan demo hanya jika benar-benar tersedia.
- Jangan cantumkan alamat rumah lengkap atau data pribadi yang tidak diperlukan pada website publik.

## Struktur file

```text
portfolio_tita/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    ├── favicon.svg
    ├── hero-circuit.svg
    ├── project-psu.svg
    ├── project-line-follower.svg
    └── project-gear.svg
```

## Mengedit konten

- `index.html`: teks, tautan, daftar skill, dan informasi proyek.
- `style.css`: warna, tata letak, tipografi, responsivitas, dan animasi.
- `script.js`: navigasi mobile, filter proyek, animasi saat scroll, dan indikator progres.
- `assets/`: ilustrasi SVG sementara.

Website menggunakan Google Fonts untuk Manrope dan DM Mono. Jika tanpa internet, halaman tetap dapat digunakan; browser akan memakai font cadangan jika Google Fonts tidak dapat dimuat.
