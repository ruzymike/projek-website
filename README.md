# Website Sertifikat Online FIK UI

Sistem informasi penerbitan & verifikasi sertifikat online untuk Fakultas Ilmu Komputer Universitas Indonesia (FIK UI).

## Tech Stack (planned)

- **Backend:** Laravel 11
- **Database:** MySQL
- **Frontend:** Blade + Livewire + Tailwind CSS
- **PDF Engine:** DomPDF / Snappy
- **Hosting:** cPanel shared hosting
- **Queue:** Database queue untuk generate sertifikat massal

## Roles

- **Pengaju** — input data pengajuan sertifikat (tanpa akun)
- **Admin** — approve / reject, manage template, generate massal
- **Peserta** — unduh sertifikat via nomor
- **Publik** — verifikasi keaslian via QR

## Status

🚧 Project initialization — PRD v4.0, June 2026.

## Setup lokal (planned)

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
npm install
npm run build
```

## Lisensi

Proprietary © FIK UI.
