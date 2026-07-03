# ⚽ Football Manager Web

Simulasi manajer sepak bola Liga 1 Indonesia — dimainkan langsung di browser, tanpa instalasi.

## 🎮 Cara Main

**[👉 Buka & Main Sekarang](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

Ganti `YOUR-USERNAME` dan `YOUR-REPO-NAME` sesuai username dan nama repositori GitHub kamu.

---

## 📲 Install Offline (PWA)

Game ini mendukung **offline play** setelah dibuka pertama kali:

- **Android/Chrome**: Tap ikon ⋮ → *Add to Home Screen*
- **iOS/Safari**: Tap ikon share → *Add to Home Screen*
- **PC/Chrome**: Klik ikon install (⊕) di address bar

Setelah diinstall, game bisa dimainkan **tanpa koneksi internet sama sekali**.

---

## ✨ Fitur

- 🏆 Liga 1 Indonesia lengkap (16 klub)
- 💰 Transfer Market dengan sistem negosiasi (BID)
- ⚽ Simulasi pertandingan live dengan event real-time
- 📊 Career stats pemain (gol, assist, clean sheet, penampilan)
- 🌙 Dark / Light mode
- 🤝 Press Conference kontekstual (derby, underdog, streak)
- 🚑 Injury proneness & recovery tracking
- 🔥 Live Match Mini-Bar (browsing tab lain saat match berlangsung)
- 📋 Heatmap rating pemain di Match Report
- 📰 Transfer Window News Feed dengan filter kategori
- 🎯 Board Confidence meter dengan tren & risiko pemecatan
- 🤖 AI lawan yang adaptif & aktif di transfer market
- 💾 Auto-save ke browser (localStorage) — data tidak hilang saat ditutup

---

## 🚀 Deploy ke GitHub Pages Sendiri

1. **Fork** atau **clone** repository ini
2. Masuk ke repository → **Settings** → **Pages**
3. Pilih **Source**: `Deploy from a branch`
4. Pilih **Branch**: `main` / `master`, folder `/` (root)
5. Klik **Save**
6. Tunggu ~1 menit, game akan live di `https://username.github.io/repo-name/`

Tidak perlu build step apapun — langsung jalan.

---

## 📁 Struktur File

```
├── index.html   # Game lengkap (self-contained, semua inline)
├── sw.js        # Service Worker untuk offline support
├── .nojekyll    # Disable Jekyll processing
└── README.md
```

> Seluruh game ada dalam satu file `index.html` (~360KB). Tidak ada dependency eksternal.
