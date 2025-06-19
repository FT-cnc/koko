# Dongeng dari Yus seputar kerjaan

Semenjak awal taon 2024 Yus mulai kerja biasa di toko sayur dan buah buahan dekat rumah. Kerjanya biasa namun cukup menarik walau membutuhkan kekuatan fisik saben hari.
Ada baiknya kerja berkeringat seperti ini buat menurunkan gula darah. Semenjak bekerja di sini selama setahun obat obatan kencing manis hampir tidak dibutuhkan lagi.

![Description of gif](https://github.com/FT-cnc/koko/blob/main/Screen-Recording4-ezgif.com-video-to-gif-converter.gif?raw=true)

Kerjaan Yus sangat diarahkan ke sayur mayur yang datang segar terkadang dengan bongkahan es di dalam kotaknya. Memang perlu sarung tangan supaya tangan tidak keram karena dingin. 
Yus bekerja enam hari seminggu, 6 sampe 8 jam sehari. Masuk jam enam pagi sewaktu jumat, sabtu dan minggu. Hari lainnya jam tujuh. Awalnya selalu libur kemis, belakangan libur senin.

## Pengolahan Citra
Dari segi teknis, ada cerita lainnya disamping keringat peluh dan angkat angkat dari kerjaan ini. Coba simak gambar di atas yang menampilkan dinamika barang barang di gudang belakang selama dua minggu terakhir.
tentu kerja di dalam kulkas lebih tidak terasa menyiksa karena temepraturnya antara 4-5 derajat. Kalau musim panas tempat ini enak juga jadinya. 

![Description of gif](https://github.com/FT-cnc/koko/blob/main/image1.jpg?raw=true)

Coba simak tulisan di dalam kotak kuning di atas. SPIN katakanlah singkatan dari spinach (bayam). Memang pengolahan citra sangat membantu menafsirkan tulisan apa yang tertulis di atas masing masing kotak.
Cara lama memang segampang mengambil gambar dan mencatat ulang inventori gudang berdasarkan apa yang tertulis. Kita akan melompati proses klasifikasi dan pengelompokan seperti berikut ini

![Description of gif](https://github.com/FT-cnc/koko/blob/main/image2.png?raw=true)

Dengan menggunakan account google, cobak simak link [**ini**](https://colab.research.google.com/drive/1HpR8_-ui5gHZwDNVXjsHyiys8EkRUs3I#scrollTo=5MCn6m648yV-), dimana akan kita bahas satu per satu.

## Unggah Gambar
Salah satu keterbatasan google colab yang kita pakai di sini adalah dihapusnya segala macam gambar secara otomatis kalau notebooknya tidak aktif selama sejam lebih. Tujuannya memang buat menghemat biaya.
Teknologi cloud computing sekarang memang luar biasa karena kita tidak perlu meng install apa pun namun beban kerja di data center yang dalam hal ini dimiliki Google juga sangat berat apalagi mereka tidak mendapat income dari iklan.
Singkat kata mari kita simak bagaimana caranya menyimpan gambar secara permanen tanpa harus diupload lagi satu per satu.

![Description of gif](https://github.com/FT-cnc/koko/blob/main/image3.png?raw=true)

Gambar di atas ini adalah contoh 20 macam tipe barang dengan 3 variasi tulisan tangan Yus. Totalnya dalam hal ini ada 60 gambar. Dalam kondisi nyata tipe barang bisa mencapai 40 macam dan idealnya variasi tulisan tangan harus lebih dari tiga.
Semakin banyak variasinya, semakin pintar kecerdasan buatan menafsirkan tiap tiap tulisan.

Di bawah ini adalah salah satu contoh tulisan tangan yang di digitalisasi dengan numpy array (istilah canggih dari bahasa [**python**](https://en.wikipedia.org/wiki/NumPy)).
Coba ligat salah satu tulisan tangan berikut dengan resolusi (176, 394) yang menampilkan tulisan Boston.

![Description of gif](https://github.com/FT-cnc/koko/blob/main/image4.png?raw=true)


(bersambung)
