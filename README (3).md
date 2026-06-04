# 🗺 Peta Sebaran Koperasi Desa Merah Putih

[![GitHub Pages](https://img.shields.io/badge/Live%20Dashboard-GitHub%20Pages-blue?style=flat-square&logo=github)](https://yanuprasetyo.github.io/monitor-kdmp/peta-kopdes.html)
[![Data](https://img.shields.io/badge/Data-Mei%202026-green?style=flat-square)](https://simkopdes.go.id)
[![Kecamatan](https://img.shields.io/badge/Kecamatan-7.276-orange?style=flat-square)]()
[![Kopdes](https://img.shields.io/badge/Total%20Kopdes-83.376-red?style=flat-square)]()

Dashboard spasial interaktif sebaran **Koperasi Desa Kelurahan Merah Putih** di seluruh Indonesia — tingkat kecamatan, 38 provinsi, 514 kabupaten/kota.

🔗 **Buka Dashboard:**
```
https://yanuprasetyo.github.io/monitor-kdmp/peta-kopdes.html
```

---

## 📌 Tentang Dashboard

Dashboard ini menampilkan distribusi spasial Koperasi Desa (Kopdes) Merah Putih per kecamatan di seluruh Indonesia, mencakup indikator kelembagaan utama seperti kepemilikan NIB, NPWP, dan pelaksanaan RAT 2025.

### Fitur Utama

| Tab | Konten |
|-----|--------|
| 🗺 **Peta Sebaran** | Peta interaktif dengan 3 mode: Klaster / Heatmap / Titik · Filter per provinsi · Popup info per kecamatan |
| 📊 **Statistik** | Distribusi kopdes per provinsi · Ranking % NIB · Ranking % RAT 2025 |
| 📋 **Tabel Data** | 7.270 kecamatan · Pencarian teks · Filter provinsi · Sort kolom · Progress bar NIB & RAT |

---

## 📊 Statistik Ringkas

| Indikator | Nilai |
|-----------|-------|
| Total Koperasi Desa | **83.376** |
| Kecamatan tercakup | **7.276** |
| Kabupaten/Kota | **514** |
| Provinsi | **38** |
| Kopdes memiliki NIB | **72,7%** |
| Kopdes telah RAT 2025 | **60,2%** |
| Provinsi terbesar | **Jawa Tengah** (8.524 kopdes) |

---

## 🗂 Sumber Data

| Sumber | Data | Periode |
|--------|------|---------|
| **Simkopdes / Kemenkop** | Data kelembagaan Kopdes (NIB, NPWP, RAT, transaksi) | Mei 2026 |
| **GADM v4.1** | Batas administrasi kecamatan (ADM3) untuk koordinat | 2023 |
| **BPS** | Kode wilayah administrasi Indonesia | 2022 |

> Koordinat menggunakan titik centroid polygon kecamatan dari GADM. 6 kecamatan terpencil (Papua, Maluku, NTT) tidak memiliki data koordinat dan tidak ditampilkan di peta.

---

## 🛠 Teknologi

Dashboard dibangun sebagai **single-file HTML statis** — tidak memerlukan server, database, atau proses build.

```
peta-kopdes.html
├── HTML + CSS (desain responsif, light theme)
├── Leaflet.js 1.9.4 (peta interaktif)
├── Leaflet.markerCluster 1.5.3 (clustering titik)
├── Leaflet.heat 0.2.0 (heatmap)
├── Chart.js 4.4.1 (visualisasi statistik)
├── DM Sans + IBM Plex Mono (tipografi)
└── Data embed langsung (7.270 titik koordinat)
```

**Cara menjalankan secara lokal:**
1. Unduh file `peta-kopdes.html`
2. Buka langsung di browser (Chrome / Firefox / Edge)
3. Tidak perlu instalasi apapun

---

## 📁 Struktur Repositori

```
monitor-kdmp/
├── peta-kopdes.html    # Dashboard utama ← buka ini
├── README.md           # Dokumentasi repositori
└── .nojekyll           # Agar GitHub Pages tidak proses Jekyll
```

---

## 📬 Kontak & Kolaborasi

Dibuat sebagai bagian dari kajian kebijakan distribusi Koperasi Desa Merah Putih.

**Pusat Riset Kependudukan — BRIN**
📧 yanu005@brin.go.id

Untuk pertanyaan atau kolaborasi, silakan buka **Issues** di repositori ini.

---

<div align="center">
  <sub>Data per Mei 2026 · 7.276 Kecamatan · 514 Kabupaten/Kota · 38 Provinsi</sub><br>
  <sub>Simkopdes · GADM · BPS · Pusat Riset Kependudukan BRIN</sub>
</div>
