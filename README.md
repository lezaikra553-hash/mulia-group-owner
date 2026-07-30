# Mulia Group Owner Command Center — Mobile Ready

Upload seluruh isi folder ini ke root repository GitHub:

- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `vercel.json`
- folder `icons`

## Agar Login Google berfungsi di HP

1. Buka aplikasi dari URL Vercel **HTTPS**, bukan membuka `index.html` langsung dari penyimpanan HP.
2. Di Google Cloud Console, tambahkan URL Vercel sebagai **Authorized JavaScript origin** pada OAuth Client ID yang digunakan aplikasi.
3. Gunakan email yang diizinkan oleh aplikasi.
4. Izinkan pop-up/cookie Google saat browser meminta izin.

Data perusahaan tetap read-only dan diambil otomatis dari file JSON Google Drive yang telah ditentukan di `CONFIG`.
