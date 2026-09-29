# 📅 Jadwal Kuliahku

Aplikasi penjadwal kuliah berbasis web dalam satu berkas HTML — menampilkan jadwal mingguan, tab per hari, dan perencanaan jadwal kuliah online.

Dibuat untuk kebutuhan pribadi sebagai mahasiswa: mata kuliah, ruangan, dosen, dan jam kuliah dalam satu tampilan yang cepat dibuka dari ponsel.

---

## ✨ Fitur

- **Jadwal mingguan** — seluruh mata kuliah dalam satu tampilan per pekan.
- **Tab per hari** — memfilter jadwal berdasarkan hari tertentu.
- **Toggle jadwal online** — tab khusus untuk perencanaan jadwal kuliah daring.
- **Informasi lengkap per mata kuliah** — nama, kode kelas, ruangan, dosen, dan jam.
- **Mode gelap/terang** — tema menyesuaikan preferensi.
- **Responsif** — nyaman dibaca di ponsel maupun desktop.
- **Satu berkas** — seluruh aplikasi berada di `index.html`, cukup dibuka di browser.

## 🧰 Teknologi

| Lapisan | Teknologi |
|---|---|
| Markup & logika | HTML5, JavaScript vanilla |
| Styling | Tailwind CSS (CDN), konfigurasi kustom (mode gelap, tipografi) |
| Tipografi | Google Fonts — Inter & JetBrains Mono |

Tanpa dependensi npm dan tanpa build step: cukup buka berkasnya di browser.

## 🚀 Cara Menjalankan Lokal

```bash
# 1. Clone
git clone https://github.com/fabian-syah/jadwalkuliahku.git
cd jadwalkuliahku

# 2. Buka langsung di browser
xdg-open index.html      # Linux
# atau
start index.html          # Windows
```

Alternatif lewat server lokal:

```bash
python3 -m http.server 8080
```

Lalu buka [http://localhost:8080](http://localhost:8080).

## 🛠️ Menyesuaikan Jadwal

Seluruh data jadwal berada di dalam `index.html`. Untuk memakai proyek ini dengan jadwal Anda sendiri:

1. Buka `index.html` di editor teks.
2. Cari bagian data jadwal (objek/array berisi mata kuliah).
3. Ganti nama mata kuliah, kode kelas, ruangan, dosen, dan jam sesuai jadwal Anda.
4. Simpan dan muat ulang halaman.

## 📁 Struktur Berkas

| Berkas | Isi |
|---|---|
| `index.html` | Seluruh aplikasi: struktur, gaya, data jadwal, dan logika |

## 🗺️ Rencana Pengembangan

- [ ] Memisahkan data jadwal ke berkas JSON terpisah
- [ ] Dukungan multi-semester dengan penyimpanan lokal
- [ ] Ekspor jadwal ke format kalender (.ics)
- [ ] Pengingat mata kuliah berikutnya

## 📄 Lisensi

MIT
