# for-sonar · Interactive Birthday Card

Halaman ucapan ulang tahun interaktif dengan animasi, surat yang tampil bertahap, dan musik. Proyek kecil untuk mengeksplorasi HTML, CSS, dan JavaScript.

[**Lihat demo**](https://for-sonar.vercel.app) · [Kode halaman](<for sonar.html>)

## Pengalaman yang dibuat

- Tiga tampilan berurutan: ucapan, amplop, dan surat.
- Efek mengetik untuk menampilkan surat secara bertahap.
- Konfeti serta animasi hati dan bintang.
- Musik latar yang dicoba diputar setelah pengguna membuka surat.
- Penyesuaian ukuran teks dan tombol untuk layar kecil.

## Teknologi

**HTML** untuk struktur · **CSS** untuk tampilan dan animasi · **JavaScript** untuk interaksi.

Efek konfeti menggunakan [canvas-confetti](https://github.com/catdad/canvas-confetti) melalui CDN. Halaman utama tidak memerlukan proses build atau pemasangan paket.

## Menjalankan secara lokal

1. Unduh repository ini melalui **Code → Download ZIP**, lalu ekstrak.
2. Buka `for sonar.html` di browser.
3. Ikuti tombol pada halaman untuk membuka surat.

Simpan file HTML, GIF, dan audio dalam folder yang sama. Koneksi internet dibutuhkan untuk memuat library konfeti dari CDN. Pemutaran audio mengikuti kebijakan browser.

## Struktur file

| File | Kegunaan |
| --- | --- |
| `for sonar.html` | Halaman utama, gaya, dan logika interaksi |
| `1.gif` | Ilustrasi tampilan pembuka |
| `write.gif` | Ilustrasi amplop |
| `Party.mp3` | Musik latar |

## Menyesuaikan ucapan

Ubah teks pada HTML dan nilai `fullLetter` pada bagian JavaScript. Warna utama diatur pada CSS; gambar dan audio dapat diganti dengan file yang memiliki nama yang sesuai.

## Catatan pengembangan

- Source saat ini merujuk favicon `bday.png`, tetapi file itu belum tersedia dalam repository. Ada juga referensi ikon eksternal.
- Font Poppins dan Dancing Script disebut dalam CSS, tetapi belum diimpor; browser dapat menggunakan font cadangan.
- Tidak ada lisensi yang ditambahkan pada repository ini. Hak penggunaan kode, gambar, dan musik perlu diperiksa sebelum digunakan ulang.

Dikelola oleh [Shen](https://github.com/shenhe-dot).
