# 📊 Dashboard Monitoring IDN Sentul

Dashboard monitoring pencapaian SKL dan Tahfidz santri **SMP IDN Sentul Boarding School** — Tahun Ajaran 2025/2026 Semester 2.

🔗 **Live Demo:** `https://username.github.io/dashboard-idn-sentul` *(ganti dengan URL kamu)*

---

## ✨ Fitur

- **Summary SKL** — monitoring pengumpulan project per kelas & mata pelajaran (IT, English, Diniyah)
- **Summary Tahfidz** — pencapaian hafalan Al-Qur'an per santri dan per kelas
- Sidebar navigasi antar halaman
- Hover tooltip interaktif di semua grafik
- Bar chart, donut chart, dan tabel data lengkap
- Fully responsive & self-contained (satu file HTML)

---

## 📁 Struktur File

```
dashboard-idn-sentul/
├── index.html      # File utama dashboard (rename dari Dashboard_SKL_Sentul.html)
└── README.md       # Dokumentasi ini
```

---

## 🚀 Cara Deploy

### GitHub Pages

1. Upload `index.html` ke repository GitHub
2. Buka **Settings → Pages**
3. Source: `Deploy from branch` → `main` → `/ (root)`
4. Klik **Save** — tunggu ±1 menit
5. Akses di: `https://username.github.io/nama-repo`

### Netlify

1. Login di [netlify.com](https://netlify.com)
2. Klik **"Add new site" → "Import from Git"**
3. Hubungkan GitHub → pilih repository ini
4. Klik **Deploy Site**
5. Akses di URL yang diberikan Netlify (bisa custom domain)

---

## 📊 Data Dashboard

### Summary SKL

| Kelas | Siswa | IT | English | Diniyah | Total |
|-------|-------|----|---------|---------|-------|
| 7A    | 18    | 6  | 5       | 5       | 16 project |
| 8A    | 15    | 9  | 5       | 8       | 22 project |
| 9A    | 10    | 2  | 5       | 5       | 12 project |
| **Total** | **43** | **17** | **15** | **18** | **50 project** |

### Summary Tahfidz

| Kelas | Santri | Total Hafalan | Santri Terbaik |
|-------|--------|---------------|----------------|
| Kelas 7 | 18 | 18 Juz 121 Halaman | Ahmad Bilal (2 Juz) |
| Kelas 8 | 15 | 44 Juz 42 Halaman 10 Baris | M. Ja'far Aly (6 Juz) |
| **Total** | **33** | **±62 Juz 163 Halaman** | — |

---

## 🛠️ Teknologi

- **HTML5 / CSS3 / Vanilla JavaScript** — tanpa framework tambahan
- **Google Fonts** — Plus Jakarta Sans + DM Mono
- Tidak memerlukan backend atau database

---

## 🏫 Tentang

**SMP IDN Sentul Boarding School**
*"Membangun Generasi Qurani Berbasis Teknologi"*

---

*Dashboard dibuat untuk keperluan internal monitoring akademik IDN Sentul.*
