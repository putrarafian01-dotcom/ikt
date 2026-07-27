# 📊 Dashboard Performance Area Hasan Basri

Dashboard interaktif untuk monitoring performa penjualan 18 toko Area Hasan Basri dengan visualisasi real-time dan upload data Excel otomatis.

---

## 🚀 Akses Dashboard

### **Link Utama (Recommended):**
👉 **[https://putrarafian01-dotcom.github.io/ikt/](https://putrarafian01-dotcom.github.io/ikt/)**

### **Link Alternatif (RAW):**
👉 **[https://raw.githubusercontent.com/putrarafian01-dotcom/ikt/main/index.html](https://raw.githubusercontent.com/putrarafian01-dotcom/ikt/main/index.html)**

---

## ✨ Fitur Utama

- 📈 **Dashboard Performance** - Visualisasi real-time 9 indikator KPI
- 📊 **Ranking Otomatis** - Sistem ranking dinamis per toko & indikator
- 📁 **Upload Excel** - Import data langsung dari file Excel (.xlsx / .xls)
- 🔍 **Search & Filter** - Cari toko dan sort by indikator apapun
- 📱 **Responsive Design** - Optimal di desktop, tablet, dan mobile
- 🎯 **Focus Area** - Identifikasi prioritas tinggi, menengah, dan kinerja baik
- 📋 **Detail Lengkap** - Lihat breakdown detail setiap toko

---

## 📊 Indikator KPI

1. **Net Sales (NS)** - Total penjualan bersih toko
2. **Gross Margin (GM)** - Margin keuntungan kotor
3. **APC** - Average Purchase per Customer
4. **PWP** - Program Wallet Partner
5. **PSM** - Program Susulan Member
6. **Serba Gratis** - Program gratis
7. **STD** - Standart/Kualitas layanan
8. **Continuous Member** - Member aktif berkelanjutan
9. **NSB** - Net Sales by Target

---

## 🔧 Cara Menggunakan

### 1. **Buka Dashboard**
```
https://putrarafian01-dotcom.github.io/ikt/
```

### 2. **Upload Data Excel**
- Klik tombol **📁 Upload File Excel** di header
- Pilih file Excel dengan format `.xlsx` atau `.xls`
- Sheet harus bernama "ikt area hasan" atau sheet pertama
- Data otomatis diproses dan dashboard ter-update

### 3. **Filter & Cari**
- Gunakan kotak pencarian untuk cari nama/kode toko
- Dropdown sort untuk mengurutkan by indikator
- Klik baris toko untuk lihat detail lengkap

---

## 📁 Format File Excel

Struktur kolom yang diharapkan:

| Col | Deskripsi |
|-----|-----------|
| A | Kode Toko (misal: Y116, CUMEDAK) |
| B | Nama Toko |
| C-E | NS: Target, Actual, % |
| F-I | GM: Target Rp, Actual Rp, Target %, Actual % |
| J-M | APC: Target, Actual, %, Point |
| N-Q | PWP: Target, Actual, %, Point |
| R-U | PSM: Target, Actual, %, Point |
| V-Y | Serba Gratis: Target, Actual, %, Point |
| Z-AB | STD: Target, Actual, % |
| AC-AE | Member: Target, Actual, % |
| AF-AI | NSB: Target, Target Sales, Actual, % |

---

## 🎨 Visualisasi

### Sections:
- **Header KPI** - Ringkasan 4 metrik utama area
- **Ringkasan Area** - Tabel agregat semua toko
- **Top 5 Terbaik** - Ranking terbaik per rank total
- **Top 5 Perlu Perhatian** - Toko dengan performa terendah
- **Detail Per Indikator** - Breakdown per KPI dengan top/bottom 5
- **Fokus Area** - Strategi prioritas (tinggi/menengah/baik)
- **Detail Lengkap** - Collapsible details setiap toko
- **Tabel Ringkas** - Explorer dengan search & sort

### Status Badge:
- 🟢 **HIJAU** - Pencapaian ≥ 100% (ON TRACK)
- 🟡 **KUNING** - Pencapaian 90-99% (WASPADA)
- 🔴 **MERAH** - Pencapaian < 90% (PERHATIAN)

---

## 🛠️ Teknologi

- **Frontend:** HTML5 + CSS3 + Vanilla JavaScript (ES6+)
- **Library:** SheetJS (XLSX parsing)
- **Design:** Responsive Grid Layout
- **Data Processing:** Real-time calculation & ranking

---

## 📱 Browser Support

- ✅ Chrome/Chromium 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers

---

## 🎯 Fitur Lanjutan

### Ranking System:
- Setiap toko di-rank per indikator (1-18)
- Total Rank Sum = jumlah semua ranking
- Rank Total Area = urutan berdasarkan Total Rank Sum
- **Lebih kecil = lebih baik** ⭐

### Data Persistence:
- Upload data tersimpan di session browser
- Refresh browser = data kembali ke sample default
- Untuk permanent, save file Excel Anda

### Export Data:
- Semua data bisa dilihat di inspector (F12 → Console → `DATA`)
- Copy paste untuk import ke tools lain

---

## 📞 Kontak & Support

Repository: [putrarafian01-dotcom/ikt](https://github.com/putrarafian01-dotcom/ikt)

---

## 📄 Lisensi

Bebas digunakan untuk keperluan internal Area Hasan Basri.

---

**Last Updated:** 27 Juli 2026  
**Version:** 2.0 (Fully Optimized)
