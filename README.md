# REPUBLIC OF X DKV

Folder siap unggah ke root repository GitHub Pages.

## Isi
- `index.html`: website portal kelas asli (saat ini masih memakai localStorage/demo untuk data dan login).
- `supabase/schema.sql`: skema database Supabase.
- `supabase/config.example.js`: contoh konfigurasi frontend; jangan masukkan secret/service_role key.
- `.nojekyll`: membantu GitHub Pages menyajikan file/folder tanpa pemrosesan Jekyll.

## Penting sebelum digunakan sungguhan
File `index.html` ini belum mengirim seluruh data portal ke Supabase. Login PIN demo dan data keuangan masih perlu migrasi ke autentikasi/backend Supabase serta kebijakan RLS yang diuji. Jangan gunakan untuk data siswa nyata sebelum tahap itu selesai.

Untuk GitHub Pages, unggah isi folder ini ke root repository, sehingga `index.html` sejajar dengan `README.md`.
