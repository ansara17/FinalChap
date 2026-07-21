# TEXT EDITING GUIDE

## Nama, jurusan, dan topik penelitian
File: `index.html`
Cari `Akmelia Zahra`, `Pendidikan Ekonomi`, atau `Research Topic`.

## Tanggal sidang
File: `index.html`
Cari `21 · 07 · 2026`.

## Isi Journey Cards
File: `script.js`
Cari `const journeyContent = [`.

## Isi Calm Notes
File: `script.js`
Cari `const noteContent = [`.

## Respons Name the Fear
File: `script.js`
Cari `const fearResponses = {`.

## Surat dari Ansa
File: `index.html`
Cari `<article id="letterPaper"`.

## Catatan Chanyeol
File: `index.html`
Cari `<aside class="bias-note">`.

## Doa dan closing
File: `index.html`
Cari `scene--closing`.

## Foto
Masukkan `assets/photos/amel.jpg`.

## Musik
Masukkan `assets/music/background-music.mp3`.


## Palet Calm Morning

File: `style.css`

Cari:

```css
CALM MORNING EDITION
```

Warna utama:

```css
Mist Blue    #E8F0F3
Powder Blue  #AFC8D3
Slate Navy   #4E6672
Warm Beige   #E6D5C4
Soft Copper  #B78668
Deep Mocha   #4A403B
Off White    #FAF9F5
```

Animasi hanya memakai `opacity` dan `transform` agar tetap ringan.


## Automatic cache busting

File: `index.html`

Cari:

```javascript
window.__ASSET_VERSION__
```

Sistem ini menambahkan versi unik ke `style.css` dan `script.js` setiap kali
halaman dibuka. Jangan menghapus blok tersebut apabila Anda ingin perubahan
kode dapat tampil tanpa hard refresh.

Catatan:
- Refresh biasa tetap diperlukan setelah deployment selesai.
- GitHub Pages dapat membutuhkan beberapa menit untuk menyelesaikan deployment.
- Foto dan musik tidak diberi versi baru setiap reload agar tetap hemat data.


## Mobile alignment patch

File: `style.css`

Cari:

```css
MOBILE ALIGNMENT PATCH
```

Bagian ini menjaga closing, profile, dan panel lainnya tetap berada di tengah
pada layar ponsel. Jangan menghapus aturan `min-width: 0`, karena aturan tersebut
mencegah elemen CSS Grid melebar mengikuti teks yang panjang.
