# Pembukuan
Aplikasi web pencatatan keuangan untuk bisnis: transaksi, anggaran, dan laporan (PDF/Excel) dalam satu file HTML. Tanpa server dan tanpa library luar, data tersimpan di browser. Mendukung mode gelap dan tampilan HP.
# Finance HCD

Aplikasi web untuk mencatat transaksi, mengatur anggaran, dan membuat laporan keuangan. Seluruh aplikasi ada dalam satu file `index.html` (HTML, CSS, dan JavaScript), tanpa server dan tanpa library luar.

## Fitur

- **Dashboard**: ringkasan Income, Expenses, Savings, dan Savings Rate, grafik bulanan, rincian per kategori, serta perbandingan anggaran dengan realisasi.
- **Transaksi**: tambah, ubah, duplikat, dan hapus (bisa dibatalkan). Ada filter tahun, jenis, kategori, dan bulan, pencarian deskripsi, pengelompokan per bulan, dan ekspor CSV.
- **Anggaran**: target per kategori untuk setiap bulan, per jenis (Income, Expenses, Savings).
- **Laporan**: laporan harian, mingguan, bulanan, dan tahunan, dengan ekspor ke PDF (cetak) dan Excel.
- **Pengaturan**: mode gelap, cadangan dan pemulihan JSON, riwayat cadangan, log aktivitas, serta sinkron cloud (Firebase, opsional).
- **Responsif**: nyaman dipakai di desktop, tablet, dan HP.

## Cara pakai

Buka `index.html` di browser, atau buka alamat GitHub Pages repo ini.

## Penyimpanan data

Data disimpan di `localStorage` browser, jadi tetap ada di perangkat yang sama dan tidak dikirim ke server. Data tidak otomatis pindah antar perangkat atau antar alamat web. Gunakan **Pengaturan → Cadangkan (JSON)** dan **Pulihkan dari file** untuk memindahkannya.

## Deploy ke GitHub Pages

1. Upload `index.html` ke repo.
2. Buka **Settings → Pages**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Buka `https://USERNAME.github.io/NAMA-REPO/`.

## Teknologi

HTML, CSS, dan JavaScript murni (vanilla), tanpa dependensi.
