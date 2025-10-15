Berikut contoh panduan yang bisa kamu masukkan ke **README.md** untuk menjelaskan penggunaan gambar di folder `assets`:

```markdown
## Assets / Images

Semua gambar yang digunakan di proyek ini berada di dalam folder `assets`.  
Jika kamu ingin **mengganti gambar default**, lakukan langkah berikut:

1. Masukkan gambar baru ke dalam folder `assets`.
2. Pastikan nama file gambar sama dengan gambar yang ingin diganti, atau ubah referensinya di kode HTML/CSS/JS sesuai nama baru.
3. Periksa ukuran gambar agar proporsional dengan tampilan website.

**Contoh struktur folder:**

```

project-root/
│
├─ assets/
│  ├─ logo.png
│  ├─ background.jpg
│  └─ profile.jpg
│
├─ index.html
├─ style.css
└─ script.js

```

> ⚠️ Catatan: Folder `assets` di-*ignore* dari Git (tidak ikut di-upload), jadi pastikan setiap orang yang ingin menjalankan proyek menambahkan sendiri file gambar di folder ini.
```

Kalau mau, gue bisa bikin versi **lebih singkat & to the point** yang cocok langsung dipasang di README. Mau gue bikinin?
