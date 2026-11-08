# 🌿 BunCOP Web Frontend (Vercel & GitHub Ready)

Frontend Sistem Monitoring & Deteksi Etiolasi Bibit Pakcoy Berbasis Web.

## 🚀 Fitur:
- **Dual-Model Real-Time Prediction**: Menampilkan hasil Model Stabil (Lama) dan Model Sensitif (Baru) secara berdampingan.
- **Kamera HP & Upload File**: Dukungan kamera fisik smartphone dengan autofocus resolusi tinggi.
- **Auto-Baseline & Pengukuran Tinggi Samping (12 Kolom)**.
- **Pengaturan URL Backend Mandiri**: Dapat diarahkan ke IP lokal laptop (`http://192.168.x.x:5000`) atau domain publik Anda.

## 📦 Cara Deploy ke Vercel:
1. Buat Repository baru di GitHub (misal: `buncop-frontend`).
2. Masukkan file `index.html` ini ke dalam repository tersebut.
3. Buka [Vercel](https://vercel.com/) -> **Add New Project** -> Pilih repo GitHub Anda -> **Deploy**.
4. Website langsung aktif dengan domain gratis, contoh: `https://buncop-pakcoy.vercel.app`.

## 💻 Menghubungkan ke Server AI di Laptop:
1. Di laptop Anda, jalankan server backend AI:
   ```bash
   python app_web_pakcoy.py
   ```
2. Buka web Vercel Anda di HP/Browser.
3. Di kotak **"⚙️ URL Server Laptop"**, masukkan alamat IP laptop Anda, contoh:
   `http://192.168.100.9:5000`
4. Selesai! Web di Vercel akan otomatis mengirim foto ke laptop dan menampilkan hasil deteksi AI.

