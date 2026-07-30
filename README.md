# Mulia Group Owner Command Center

Aplikasi owner statis untuk mengonsolidasikan data:

- CV Berkah Mulia Adv
- PT Dwi Mulia Advertising
- PT Azkia Mulia Perada

## Cara upload ke GitHub dan Vercel

1. Buat repository baru atau buka repository Vercel yang sudah ada.
2. Upload seluruh file dalam folder ini ke root repository:
   - `index.html`
   - `styles.css`
   - `app.js`
   - `vercel.json`
3. Commit perubahan.
4. Vercel akan melakukan deploy otomatis.

Tidak membutuhkan proses build atau instalasi NPM.

## Login awal

- Username: `owner`
- Password: `owner123`

Segera ganti password melalui menu **Pengaturan**.

## Cara sinkronisasi data

1. Buka aplikasi perusahaan masing-masing.
2. Gunakan menu backup/export JSON.
3. Buka Owner Command Center.
4. Masuk ke **Sinkronisasi Data**.
5. Pilih backup JSON sesuai perusahaan.

Data disimpan pada localStorage browser aplikasi owner. Untuk memindahkan ke laptop lain, gunakan **Download Backup Owner** dan **Pulihkan Backup Owner**.

## Catatan penting

Karena aplikasi perusahaan dan aplikasi owner berada pada domain berbeda, browser tidak mengizinkan pembacaan localStorage lintas domain. Oleh sebab itu versi statis ini menggunakan mekanisme impor backup JSON. Untuk sinkronisasi real-time lintas perangkat diperlukan database online/API, misalnya Supabase, Firebase, atau backend khusus.
