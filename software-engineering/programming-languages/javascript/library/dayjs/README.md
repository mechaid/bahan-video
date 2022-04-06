## Judul
Mengubah Format Tanggal dan Waktu di Halaman Website dengan Library Javascript dayjs

## Hook
(Cukup suara + auto slide show ilustrasi sesuai narasi)
- Konversi waktu ke format tanggal Indonesia, ke SQL
- Parsing waktu dari string
- Menambahkan Waktu
- Hitung durasi antar Waktu 
- Prinsip kerja Dayjs
- Jadi bahasan sharing kali ini

##  Intro
- (Mecha TV - ) 
- Assalamualaikum Wr. Wb.
- Bismillaahirrahmaanirrahiim
- Halo teman-teman semua, semoga sehat selalu.
- Detik ini saya ingin share satu library Javascript untuk memudahkan kita mengubah format tanggal dan waktu
- Nama library nya dayjs
- Dibuat oleh user @iamkun dari Shanghai China
  - Terima kasih @iamkun
- Kenapa saya pilih share tentang Dayjs ?
  <!-- - Library populer js sejenis dayjs ada momentjs, date-fns, dan Luxon -->
  - Karena selain populer, ukurannya kecil, fiturnya banyak, kompatibel dengan library lainnya kayak Material UI  
  - Kenapa cari2 library yang lightweight / berukuran kecil
    - karena seiring aplikasi bertambah besar, library yang digunakan makin banyak,
    - kita harus memperhatikan ketersediaan resource server / client
- Informasi terkait Dayjs dan contoh script yang saya tulis,
  - dapat teman-teman lihat dan ambil di deskripsi video ini

## Prinsip Kerja Dayjs 
(Improvisasi slide)
- Mari kita bahas sedikit prinsip kerja Dayjs
  - Objek utama ketika kita menggunakan Dayjs, adalah objek Dayjs
    - perwujudan tanggal dan waktu tertentu
- Ada 3 fungsi utama yang dijalankan oleh Dayjs
  - Mengkonversi format string input jadi objek Dayjs
    - Ilustrasi : string tanggal Indonesia, timestamp, string date time dari API, string tanggal waktu format tertentu 
    - Gimana dari string yang beda2 format kita konversi jadi objek Dayjs
    - [parse()](https://day.js.org/docs/en/parse/string-format)
  - Memanipulasi dan membandingkan objek Dayjs
    - Manipulasi 
    - Query
  - Mengkonversi objek Dayjs jadi format string output
    - [format()](https://day.js.org/docs/en/display/format)
- Karena zona dan penamaan waktu di berbagai negara di dunia berbeda-beda, di Dayjs terdapat 
  1. Locale
  2. Timezone 

## Instalasi
- Bagi teman-teman pengguna NPM maupun Yarn, Dayjs dapat diinstall dengan cara 
  - npm install dayjs
  - yarn add dayjs
- Bagi teman-teman yang ingin coba langsung via html, script Dayjs dapat dipanggil melalui CDN
  - Yang kita akan gunakan sekarang adalah script Dayjs dari CDNJS
  - Sekedar informasi CDNJS ini menyimpan lebih dari 4000 library Javascript dan CSS 
    - yang dapat kita panggil dan gunakan langsung di website kita
  - Langsung kita Googling kata kunci "cdnjs dayjs" 
    - Pilih pencarian teratas, kita akan langsung masuk ke halaman Dayjs
      - [CDNJS](https://cdnjs.com/libraries/dayjs) 
  - Di halaman Dayjs CDNJS ini ada script Dayjs dan script2 tambahan (locale, plugin) dari Dayjs
  - Untuk memanggil script2 ini dari halaman HTML yang akan kita dibuat, tinggal klik copy paste di atas kanan setiap script  

- Mari kita buat file HTML sederhana untuk arena bermain kita
  - Buat struktur HTML
  - Tambahkan script2 Dayjs yang akan digunakan 
  - Inisialisasi script Dayjs
    - set locale
    - tambahkan plugin yang dibutuhkan
      - ditambahkan dayjs_plugin_ di depan nama plugin ketika akan extend plugin
  - Percobaan

## Penggunaan
(Ikut contoh file)

## Penutup
- Ok, Jika ada pertanyaan atau usul video selanjutnya, langsung tulis di kolom komentar
- Untuk dapetin info terbaru aneka riset dan teknologi digital, teman-teman bisa subscribe channel ini 
- Alhamdulillahirrabilalamiin
- Sekian sharing kali ini, semoga videonya bermanfaat
- (tunjuk) Inget, Waktumu habis untuk apa ?
- Assalamualaikum Wr. Wb.
