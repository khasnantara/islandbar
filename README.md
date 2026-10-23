# IslandBar

**Pil kecil di atas layar Windows.** Musik, lirik live sync, kontrol cepat, dan daftar tugas — muncul saat kamu butuh, menyingkir saat tidak.

🌐 Website: https://khastara7.github.io/islandbar
⬇️ Download: [IslandBar-Setup.exe (versi terbaru)](https://github.com/khasnantara/islandbar/releases/latest/download/IslandBar-Setup.exe)

## Fitur

- **Musik** — cover, judul, play/pause, lagu berikutnya, lompat ke bagian lagu (Spotify, YouTube di browser, dll)
- **Lirik live sync** — lirik berjalan mengikuti lagu, di pil atau di panel
- **Pusat Kontrol** — WiFi + ping, paket daya, kecerahan, volume, kunci/sleep/restart/matikan
- **Daftar tugas** — tambah dan centang tugas langsung dari pil
- **Isi pil bisa diatur** — baterai, jam, tanggal, ping, cuaca, CPU, RAM
- **Popup** volume & clipboard, **animasi cuaca** (hujan, salju, petir)
- **Tampilan** — tema gelap/terang/otomatis, 8 warna aksen, posisi atas/bawah, transparansi, gaya animasi
- Sembunyi otomatis saat aplikasi layar penuh, bisa jalan saat Windows menyala

## Syarat

Windows 10 (versi 1809 atau lebih baru) atau Windows 11, 64-bit.

## Cara pasang

1. Download **IslandBar-Setup.exe** dari [halaman Releases](https://github.com/khastara7/islandbar/releases/latest).
2. Jalankan file tersebut. Kalau muncul *"Windows protected your PC"*, klik **More info → Run anyway** (aplikasi belum memakai tanda tangan digital berbayar).
3. Ikuti langkah pemasangan.

## Build dari source

```
py -m pip install PySide6-Essentials winsdk psutil pycaw
py islandbar.py
```

Untuk membuat `.exe` dan installer: pasang [Inno Setup](https://jrsoftware.org/isdl.php), lalu jalankan `build.bat`. Hasilnya ada di `output\IslandBar-Setup.exe`.

## Sumber data

- Lirik: [lrclib.net](https://lrclib.net)
- Cuaca: [wttr.in](https://wttr.in)

## Catatan

IslandBar adalah proyek independen dan tidak berafiliasi dengan Apple Inc. maupun Microsoft.
Dibuat dengan [PySide6 (Qt for Python)](https://doc.qt.io/qtforpython/), dilisensikan di bawah LGPL.

© 2026 jarrr
