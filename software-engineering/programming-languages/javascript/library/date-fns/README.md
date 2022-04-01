## Judul
Mengubah Format Tanggal dan Waktu di Halaman Website dengan Library Javascript date-fns

## Instalasi
- via CDN
- via npm / yarn

## Teori
- Alur konversi format tanggal: tanggal format sumber -> objek Date -> tanggal format tujuan 
- Alur manipulasi tanggal: tanggal format sumber -> objek Date -> manipulasi objek Date -> tanggal format tujuan 

## Penggunaan
- Mengubah format SQL datetime jadi format date
  - Method utama:
    - [parse()](https://date-fns.org/v2.28.0/docs/parse)
    - [format()](https://date-fns.org/v2.28.0/docs/format)

  ```js
  const dateStringSource = '2020-03-22 08:22:00'
  const dateObject = parse(dateStringSource, 'yyyy-MM-dd HH:mm:ss', new Date())
  const dateStringDestination = format(dateObject, 'd MMM yyyy')
  ```

- Menambah Mengurangi Tanggal
  - Method utama:
    - [add()](https://date-fns.org/v2.28.0/docs/add)

- Mengubah format date jadi tanggal pake hari dan bulan bahasa Indonesia 
