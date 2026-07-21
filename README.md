# THE FINAL CHAPTER

Kartu digital ringan untuk Akmelia Zahra sebelum sidang skripsi tanggal 21 Juli 2026.

## Cara menggunakan

1. Ekstrak seluruh isi ZIP.
2. Masukkan foto Amel ke `assets/photos/amel.jpg`.
3. Masukkan musik ke `assets/music/background-music.mp3`.
4. Buka `index.html` untuk mencoba secara lokal.
5. Upload seluruh isi folder ke repository GitHub.
6. Aktifkan GitHub Pages dari branch utama.

## Foto

Nama file wajib: `amel.jpg`

Saran:
- Rasio portrait 4:5
- Ukuran 1200 × 1500 px
- Kompres sekitar 300–700 KB

Jika file belum ada, website otomatis menampilkan placeholder “AZ”.

## Musik

Nama file wajib: `background-music.mp3`

Saran:
- Instrumental piano, akustik, atau lofi
- Ukuran ideal di bawah 5 MB
- Bitrate 128–160 kbps

## Performa

Proyek ini sengaja dibuat ringan:
- Tidak memakai canvas
- Tidak memakai particle system
- Tidak memakai blur berat
- Hanya satu foto
- Enam scene
- Tombol Reduce Motion tersedia
- Semua scene dapat di-scroll


## Tema visual: Calm Morning Edition

Palet:

- Mist Blue: `#E8F0F3`
- Powder Blue: `#AFC8D3`
- Slate Navy: `#4E6672`
- Warm Beige: `#E6D5C4`
- Soft Copper: `#B78668`
- Deep Mocha: `#4A403B`
- Off White: `#FAF9F5`

Animasi ringan:

- Buku membuka satu kali di opening
- Teks muncul bertahap
- Journey Cards dan Calm Notes muncul berurutan
- Garis dekoratif tumbuh perlahan
- Amplop surat tetap terbuka secara interaktif
- Cahaya lembut bergerak pada closing
- Tidak menggunakan canvas, partikel, confetti, atau blur berat


## Automatic cache refresh

The project now uses automatic cache busting for:

- `style.css`
- `script.js`

Each page load adds a unique query version, for example:

```text
style.css?v=m5x8abc
script.js?v=m5x8abc
```

After a GitHub Pages deployment finishes, a normal refresh is usually enough.
`Ctrl + Shift + R` should no longer be needed for CSS or JavaScript changes.

Photo and music files remain cacheable so the website does not download large
media files again on every visit. If the photo or music itself is replaced and
an old version still appears, rename the media file and update its path once.


## Mobile alignment revision

Perbaikan ini menangani:

- Closing yang melebar ke kanan pada ponsel.
- Judul `Bismillahirrahmanirrahim.` yang memaksa seluruh panel menjadi lebih lebar.
- Panel doa dan reminder yang tidak berada tepat di tengah.
- Foto profil yang terlalu mendominasi layar ponsel.
- Grid item yang dapat memperbesar lebar scene karena aturan minimum-content CSS Grid.

Ukuran yang diuji:

- 390 × 844
- 360 × 800
- 320 × 568

Hasil pengujian: seluruh enam scene memiliki lebar scroll yang sama dengan
lebar viewport dan tidak menghasilkan horizontal overflow.
