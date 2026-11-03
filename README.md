# Finwise

Aplikasi web satu halaman (satu file HTML, JavaScript murni) untuk mencatat tabungan Fauzi dan Ayu.

- Data: Firebase Firestore, satu dokumen `tabungan/state` (field `json`), project `finwise-6733a`.
- Halaman dianggap siap setelah menerima data dari server; setiap simpan memakai transaksi Firestore.
- Peran: Viewer (hanya lihat) dan Admin (PIN default 040404, disimpan sebagai hash SHA-256). PIN hanya pengaman tampilan, bukan keamanan sungguhan.
- Laporan PDF (jsPDF 2.5.1) dan cadangan JSON dapat diunduh dari halaman.

## Memasang di GitHub Pages
Settings → Pages → Deploy from a branch → `main` / `(root)`. (Repository harus publik pada akun gratis.)
