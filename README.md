# KALANIRVATA — Website

Website landing page untuk **Kalanirvata** (System Maker / Digital Structuring Unit).

## 🚀 Deploy ke Vercel

### Cara 1 — Via Vercel CLI (Paling Cepat)
```bash
# Install Vercel CLI
npm install -g vercel

# Masuk ke folder ini
cd kalanirvata-web

# Deploy
vercel

# Ikuti instruksinya:
# - Set up and deploy? → Y
# - Which scope? → pilih akun Anda
# - Link to existing project? → N
# - Project name? → kalanirvata (atau sesuai keinginan)
# - In which directory? → ./ (tekan Enter)
# - Override settings? → N
```

### Cara 2 — Via GitHub + Vercel Dashboard
1. Upload folder ini ke repository GitHub baru
2. Buka [vercel.com](https://vercel.com) → **Add New Project**
3. Import repository GitHub Anda
4. Vercel otomatis detect sebagai static site
5. Klik **Deploy** → selesai! 🎉

### Cara 3 — Drag & Drop
1. Buka [vercel.com/new](https://vercel.com/new)
2. Pilih **"Deploy without a Git provider"**
3. Drag & drop folder `kalanirvata-web` ke browser
4. Deploy!

---

## ✏️ Kustomisasi

Edit file `index.html`:

### Nomor WhatsApp
Cari `6281234567890` → ganti dengan nomor WA bisnis Anda (format: 62xxx tanpa tanda +)

### Username Instagram
Cari `kalanirvata` di link Instagram → ganti dengan username IG Anda

### Harga Layanan
Cari bagian `<!-- PRICING -->` → sesuaikan harga sesuai kebutuhan

---

## 📁 Struktur File
```
kalanirvata-web/
├── index.html      ← Semua konten website (satu file)
├── vercel.json     ← Konfigurasi Vercel
└── README.md       ← Panduan ini
```

---

*Dibuat untuk Kalanirvata — "Mengatur sistem, membangun hasil."*
