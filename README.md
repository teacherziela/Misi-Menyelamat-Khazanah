# Mission History: Code Red

Game berasingan untuk Sejarah Tingkatan 1, Bab 5: Tamadun Awal Dunia. HTML/CSS/JavaScript biasa; tiada pemasangan, akaun, pelayan aplikasi atau kunci API diperlukan. Portal HistoryVerse asal tidak diubah.

## Cuba pada komputer

Ekstrak ZIP, kemudian buka `index.html` dalam Chrome, Edge, Firefox atau Safari moden. Semua aset permainan dibungkus bersama dan boleh digunakan tanpa internet. Pautan bahan rujukan memerlukan internet. Bunyi dijana oleh Web Audio selepas interaksi pengguna.

## Muat naik ke GitHub Pages

1. Ekstrak `mission-history-code-red-github-pages.zip`.
2. Cipta repositori **baharu** untuk game ini, contohnya `mission-history-code-red`.
3. Muat naik **kandungan** ZIP: `index.html`, `styles.css`, `app.js`, folder `assets`, `.nojekyll` dan dokumen panduan. Jangan muat naik ZIP sahaja. Pastikan `index.html` berada pada aras utama repositori.
4. Dalam tetapan repositori, buka **Pages**. Pilih penerbitan daripada branch `main`, folder `/ (root)`, kemudian simpan.
5. Tunggu penerbitan selesai. Buka alamat Pages yang dipaparkan GitHub dan uji pada telefon.

Semua pautan aset menggunakan laluan relatif supaya game boleh berada dalam subfolder GitHub Pages. Jangan gantikan fail portal HistoryVerse.

Panduan rasmi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Aliran permainan

- Nama murid → sambutan peribadi dan mesej RED CODE.
- Misi peta: empat label tamadun, kemudian enam sungai (Nil, Tigris, Euphrates, Indus, Huang He dan Yangtze). Kedudukan geografi kekal tepat; susunan label dan nombor pin diacak.
- Misi arkib: empat ilustrasi objek/model, dengan kad dan ruang arkib diacak setiap sesi.
- Simulasi tapak: avatar bergerak ke objek. Gunakan sarung tangan, radio atau kanopi untuk menangani sampah, vandalisme dan artifak terdedah. Teguran selamat dan mengabaikan risiko turut direkodkan.
- Cabaran KBAT: hujan, pelawat di kawasan licin dan saliran tersumbat. Pasang penghadang sebelum mengurus saliran moden. Visual berubah apabila tindakan berjaya.
- Laporan akhir: markah, sebab tindakan penting, rekod keputusan dan muat turun laporan teks.

## Kawalan

Peta: seret label ke pin, atau pilih label kemudian pin. Pada telefon, leret kawasan peta untuk melihat timur/barat dan gunakan zum apabila pin rapat. Alternatif papan kekunci: Tab untuk memilih kawalan dan Enter untuk mengaktifkan.

Simulasi: sentuh/klik tanah atau objek untuk bergerak. Anak panah/WASD juga boleh digunakan apabila fokus bukan pada butang. Dekati objek, pilih alat, kemudian tekan `Gunakan alat`. Paparan radio menerangkan kesan tindakan. Tiada pemasa.

## Pemarkahan (100)

| Bahagian | Markah maksimum | Peraturan |
|---|---:|---|
| Peta | 30 | 10 label × 3; salah bagi sesuatu label mengurangkan nilainya kepada 2, sekali sahaja |
| Arkib | 20 | 4 objek × 5; salah bagi sesuatu objek mengurangkan nilainya kepada 3, sekali sahaja |
| Sampah | 8 | Sarung tangan |
| Vandalisme | 10 | Radio / laporan kepada pengawal |
| Artifak terdedah | 12 | Kanopi di tempat asal, disertai laporan automatik |
| Keselamatan pelawat | 10 | Penghadang semasa hujan |
| Saliran moden | 10 | Penyodok selepas pelawat dilindungi |

Untuk setiap tugasan simulasi, alat salah/keutamaan tidak selamat menolak 3 markah sekali sahaja. Mengabaikan tugasan menolak 2 markah lagi sekali sahaja. Tindakan yang sudah berjaya tidak memberi markah tambahan. Murid boleh kembali dan membetulkan tindakan.

Keputusan: 90–100 Cemerlang; 75–89 Berjaya; kurang 75 Dalam Latihan. Ini maklum balas pembelajaran, bukan pentaksiran rasmi. Bahagian akhir menilai keputusan yang direkod dalam simulasi; tiada checklist atau slogan wajib.

## Data, kebolehcapaian dan batas

- Nama dan rekod berada dalam memori sesi; tiada analitik atau penghantaran data.
- Muat semula halaman memulakan sesi baharu. Tiada simpanan sambung automatik.
- Pilihan senyap, sokongan papan kekunci, fokus jelas, teks maklum balas dan alternatif ketik untuk seretan.
- Tapak ialah latihan rekaan. Objek/model ialah ilustrasi, bukan foto artifak sebenar. Rawatan konservasi sebenar mesti dikendalikan pakar.
- Peta menggunakan sempadan moden untuk orientasi. Pin menunjukkan kawasan rujukan dan bukan keluasan tamadun.

Lihat `SUMBER.md` untuk pemetaan fakta dan kredit. Lihat `UJIAN.md` untuk hasil semakan versi ini.

## Pembukaan CODE ERROR

Selepas nama dihantar, intro operasi selama kira-kira 11 saat memaparkan CODE ERROR, gangguan isyarat, amaran arkib, kira detik 10 saat dan panggilan ejen. Bunyi denyutan cemas mengikut suis Bunyi. Butang Langkau intro terus membuka sambutan. Kira detik ialah elemen cerita dan tidak menolak markah. Tetapan peranti untuk mengurangkan gerakan dihormati.

## Pembetulan peta GitHub Pages (27 September)
Peta kini dibenamkan terus dalam app.js. Paparan peta tidak lagi memerlukan permintaan fail assets/world-map.svg. Untuk membaiki pemasangan sedia ada, gantikan app.js dengan versi ini, kemudian muat semula halaman selepas GitHub Pages selesai menerbitkan perubahan.
