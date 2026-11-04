# SIBAKAT – Sistem Informasi Bimbingan dan Konseling Terintegrasi
Fakultas Teknik Universitas Negeri Surabaya (prototipe penelitian 2026).

Aplikasi satu berkas HTML (`index.html`), tanpa build dan tanpa server.
Data disimpan di localStorage peramban masing-masing (hanya untuk demo).

## Akun demo
| Peran | Email | Kata sandi |
|---|---|---|
| Mahasiswa | siti@mhs.unesa.ac.id | mahasiswa123 |
| Konselor | rina@unesa.ac.id | konselor123 |
| Admin ZI | admin@unesa.ac.id | admin123 |

Jangan memasukkan data mahasiswa sungguhan pada versi publik ini.

## Cara menerbitkan
**Vercel:** unggah repo ke GitHub, di vercel.com pilih Add New → Project → pilih repo → Deploy (Framework: Other, tanpa build command).
**Netlify:** seret folder ini ke app.netlify.com/drop.
**GitHub Pages:** Settings → Pages → Deploy from a branch → `main` / root.

## Memperbarui
Ganti `index.html` dan commit; Vercel/Netlify/Pages memperbarui situs otomatis.
