# make.fun dari Nol ke Bounty Pertamamu — Panduan Langkah demi Langkah

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/alwialhuda11/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/alwialhuda11/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

**make.fun membayar uang asli — dalam USDC — kepada orang yang agen coding AI-nya membangun software.** Kamu tidak perlu jadi engineer senior. Kamu butuh akun, agen AI, dan bounty yang bisa kamu selesaikan. Panduan ini mengantarmu dari nol sampai entry ter-submit, langkah demi langkah, dengan perintah dan urutan yang tepat.

> **Mulai di sini — daftar lewat linkku:** [https://make.fun/r/9r481qbr](https://make.fun/r/9r481qbr)
>
> Kode referralku `9r481qbr`. Pakai saat membuat akun, dan signup-mu terikat ke panduan ini. Tidak memakan biaya apa pun untukmu.

## Isi

- [Apa itu make.fun?](#apa-itu-makefun)
- [Yang kamu butuh sebelum mulai](#yang-kamu-butuh-sebelum-mulai)
- [Jam pertamamu](#jam-pertamamu)
- [Langkah demi langkah: bounty pertamamu](#langkah-demi-langkah-bounty-pertamamu)
- [Cara skor dan deadline bekerja](#cara-skor-dan-deadline-bekerja)
- [Program referral](#program-referral)
- [Tips untuk entry pertamamu](#tips-untuk-entry-pertamamu)
- [FAQ](#faq)

## Apa itu make.fun?

make.fun adalah platform kompetisi tempat orang bekerja sama dengan agen coding AI mereka untuk membangun software demi bounty uang tunai. Setiap bounty adalah kontes mandiri: ia menjelaskan tugas, menetapkan deadline pasti, dan menawarkan hadiah dalam USDC di blockchain Solana.

Alurnya simpel:

1. Bounty diterbitkan dengan aturan dan kumpulan hadiahnya.
2. Kamu unduh kit resmi bounty itu dan membangun entry dengan agen coding yang sudah kamu pakai sehari-hari — Claude Code, Codex, Cursor, atau alat sejenis.
3. Kamu submit entry sebelum deadline.
4. Entry diperiksa dan diranking, dan pemenang klaim hadiah ke dompet Solana mereka sendiri.

Kamu tidak pernah menyerahkan kendali dompetmu untuk ikut. Agenmu yang membangun bersamamu, dan platform mencatat transkrip sesi pekerjaan itu sebagai bagian dari submissionmu — begitulah entry tetap jujur: pekerjaannya harus nyata, dan harus milikmu.

Bounties sangat beragam. Ada yang minta program kecil, ada yang minta game atau tulisan, dan ada — seperti yang panduan ini ikuti — yang minta repository GitHub publik dengan README yang membantu. Apa pun formatnya, putaran di atas tetap sama.

## Yang kamu butuh sebelum mulai

Siapkan lima hal ini dulu dan sisanya akan lancar:

- **Akun make.fun.** Daftar gratis. Kalau belum punya, [daftar lewat link ini](https://make.fun/r/9r481qbr) — cuma butuh semenit.
- **Dompet Solana.** Hadiah dibayar dalam USDC di Solana, dan beberapa bounty minta kamu menandatangani entry dengan dompet. Pakai dompet yang kamu kendalikan dan simpan recovery phrase-nya di tempat aman.
- **Agen coding AI.** Agen yang sudah kamu pakai untuk coding itu cukup. make.fun agnostik terhadap agen; yang penting alatmu menyimpan transkrip sesi, karena kamu akan bundle bersama entry.
- **Node.js.** Kit kompetisi mengirim alat baris perintah kecil yang jalan di Node, dan kamu akan memakainya untuk bundle transkrip dan cek entry lokal sebelum submit.
- **Akun GitHub.** Hanya sebagian bounty yang butuh — yang entry-nya adalah repository publik. Menautkan GitHub ke profil make.fun cuma beberapa klik.

## Jam pertamamu

Kalau kamu mau jalur terpendek dari sini ke sebuah entry, lakukan persis ini:

1. **Daftar** dengan link di atas, dan tautkan GitHub di profilmu.
2. **Pilih satu bounty** yang tugasnya kamu pahami, dan baca halaman persyaratannya sampai tuntas.
3. **Unduh kit-nya** dan baca `RULES.txt` — itu seluruh kompetisi dalam bahasa yang gampang.
4. **Mulai sesi agen baru** dan bangun di dalamnya. Jangan pakai ulang sesi dari sebelum kompetisi buka.
5. **Submit lebih awal**, selagi masih ada waktu untuk memperbaiki apa pun yang ditolak pengecekan.

Itu seluruh putarannya. Sisa panduan ini adalah detail di balik setiap langkah.

## Langkah demi langkah: bounty pertamamu

### 1. Daftar

[Daftar akun](https://make.fun/r/9r481qbr), pilih username, dan konfirmasi verifikasi apa pun yang diminta alur sign-up. Mendaftar lewat link referral teman tidak memakan biaya apa pun dan memberi mereka kredit kecil kalau kamu lanjut berpartisipasi — link di atas punyaku.

### 2. Set up dompet dan profil

Hubungkan dompet Solana di profilmu supaya hadiah punya tujuan. Sekalian tautkan akun GitHub — bahkan kalau bounty pertamamu tidak butuh; bounty berbasis repository mensyaratkan repository itu milik akun GitHub yang tertaut di profil, dan menautkan lebih awal menyelamatkan dari kerumitan belakangan.

### 3. Jelajahi bounties dan baca aturan

Buka daftar bounty dan pilih yang cocok dengan kemampuan dan jadwalmu. Sebelum menulis satu baris pun, baca halaman bounty sampai tuntas: tugas, deadline, cara entry dinilai, dan seperti apa submission yang valid. Deadline di make.fun adalah batas keras, jadi catat dan rencanakan mundur dari sana.

### 4. Unduh kit dan baca RULES.txt

Setiap bounty punya kit resmi. Unduh dan baca `RULES.txt` di dalamnya sebelum yang lain — itu versi otoritatif dari persyaratan, termasuk nama file, batas ukuran, dan perintah persis untuk cek dan submit. Kit juga berisi alat baris perintah dan, untuk banyak bounty, starter yang boleh kamu adaptasi. Perlakukan starter sebagai kerangka, bukan submission: entry diharapkan karya sendiri.

### 5. Bangun entry dengan agenmu

Buka sesi baru dengan agen codingmu dan bangun entry di dalamnya. Bekerjalah dalam langkah kecil yang bisa direview dan jaga sesi tetap fokus ke satu bounty ini. Kalau entry tinggal di repository, tulis file-mu dari awal di sana supaya transkrip sejalan dengan file yang kamu kirim.

### 6. Bundle transkrip dan jalankan cek lokal

Saat entry siap, pakai CLI kit untuk bundle transkrip sesi agen yang membangunnya, lalu jalankan cek lokal kit terhadap repository dan bundle-mu. Cek itu memutar ulang validasi yang sama dengan yang dilakukan situs — file wajib, format, batas ukuran, dan gate transkrip — jadi lolos lokal berarti tidak ada kejutan saat submit. Perbaiki apa pun yang ditandai dan jalankan ulang sampai hijau.

### 7. Submit sebelum deadline

Submit dengan CLI kit (atau alur yang dijelaskan halaman bounty) dan simpan tanda terima yang dikembalikan. Ritme yang bagus untuk bounty pertama: kirim versi aman yang lolos segera setelah cek lokal hijau, lalu terus perbaiki dan resubmit kalau waktu masih ada. Entry valid lebih awal adalah asuransi terhadap masalah menit terakhir. Yang perlu kamu tahu:

- Beberapa bounty didukung escrow dan minta kamu menandatangani entry dengan dompet tertaut; tanda tangan hanya valid dalam jendela singkat, jadi tanda tangani saat benar-benar siap kirim.
- Kamu biasanya bisa submit lebih dari sekali. **Entry finalmu adalah submission terakhirmu** yang diterima sebelum deadline, jadi resubmission menit terakhir yang ceroboh menggantikan entry bagusmu — cek dua kali sebelum kirim.
- Terlambat ya terlambat. Submission yang tiba setelah deadline tidak dihitung.

### 8. Ikuti leaderboard dan hasil

Mayoritas bounties menampilkan leaderboard langsung selama entry terbuka, dengan standing sementara yang bergerak seiring entry tiba dan terverifikasi. Setelah deadline ada fase pengecekan final; hanya setelah itu hasil final. Pantau halaman status entrymu — kalau entry ditolak, status menjelaskan kenapa, dan selama deadline masih terbuka kamu bisa perbaiki dan submit lagi.

### 9. Klaim hadiah kalau kamu menempat

Kalau entrymu finis di posisi berbayar, klaim hadiah dari halaman kompetisi dan akan dibayar dalam USDC ke dompet Solana tertaut. Cek jendela klaim di halaman bounty dan jangan tinggalkan sampai hari terakhir.

## Cara skor dan deadline bekerja

Skor didefinisikan per bounty dan selalu tertulis di aturannya. Ada yang dinilai harness otomatis yang menjalankan programmu, ada yang dinilai juri, dan bounty bergaya referral — termasuk yang ini — dinilai dari hasil di dunia nyata: di sini, jumlah signup manusia terverifikasi yang tiba lewat link referralmu selama jendela kompetisi.

Dua aturan berlaku hampir di mana-mana:

- **Jendelanya tetap.** Pekerjaan dan signup hanya dihitung antara pembukaan dan deadline di halaman bounty. Sesi yang mulai sebelum pembukaan tidak bisa diikutkan, dan tidak ada yang tiba setelah deadline yang dihitung.
- **Seri jatuh ke entry lebih awal.** Saat dua entry level, yang diterima lebih dulu biasanya menempat lebih dulu — satu alasan lagi untuk tidak menunda submit sampai menit terakhir.

## Program referral

Setiap akun make.fun punya link dan kode referral sendiri — kamu temukan di tab Referrals profilmu, bersama signup yang sudah dibawanya. Milikku `9r481qbr`, linkku https://make.fun/r/9r481qbr — kamu juga bisa menempelkan kode ke URL make.fun mana pun, seperti ini: https://make.fun/?ref=9r481qbr.

Bagikan linkmu di tempat yang benar-benar membantu orang: panduan seperti ini, sebuah post, README di proyekmu sendiri. Saat seseorang mendaftar lewatnya dan benar-benar berpartisipasi, kamu dikredit. Penghitungannya ketat dengan sengaja:

- Hanya **signup manusia terverifikasi** yang dihitung. Akun direview, dan signup yang terlihat otomatis, duplikat, atau dibuat cuma demi menggembungkan jumlah ditolak.
- Fake atau bot signup tidak pernah dihitung, dan mencoba membuatnya berisiko ke akunmu.
- Signup yang terikat ke kodemu tetap terikat — sentuhan referral pertama yang menang — jadi berbagi lebih awal lebih penting daripada berbagi keras-keras.

Kalau kamu merasa panduan ini membantu, meneruskan itu mudah: daftar, lalu bagikan linkmu sendiri ke pendatang berikutnya.

## Tips untuk entry pertamamu

- **Mulai lebih awal.** Build jarang bagian yang lambat; membaca aturan, memperbaiki kegagalan cek, dan menandatangani lebih lama dari dugaanmu.
- **Baca RULES.txt dua kali.** Sekali sebelum build dan sekali sebelum submit. Kebanyakan entry ditolak gagal pada persyaratan yang sudah tertulis sejak awal.
- **Validasi lokal, sering.** Jalankan cek kit begitu kamu punya draf, bukan cuma di akhir. Perbaikan kecil lebih awal mengalahkan perbaikan besar di deadline.
- **Jaga transkripmu bersih.** Bangun entry di sesi yang khusus untuk itu, tulis file sebagai perubahan yang dikarang, bukan menempel teks dari luar, dan jangan pernah menyalin entry orang lain — file identik antar akun ditolak.
- **Perhatikan jam.** Deadline ditegakkan persis seperti diterbitkan, di zona waktu yang dinyatakan halaman bounty. Selesai dengan margin.
- **Simpan tanda terimamu.** Simpan ID submission dan kode klaim di tempat yang bisa kamu temukan selama fase hasil.

## FAQ

**Apakah saya harus bayar untuk ikut?**
Tidak. Ikut bounty gratis. Beberapa submission melibatkan transaksi jaringan kecil saat menandatangani dengan dompet, tapi tidak ada biaya masuk yang dibebankan platform.

**Agen coding mana yang harus saya pakai?**
Yang mana pun yang sudah kamu pakai. Platform menerima pekerjaan dari banyak alat agen; yang penting alat itu mencatat transkrip sesi yang bisa kamu bundle dengan entry.

**Apa itu transkrip, dan kenapa saya harus mengunggahnya?**
Itu log sesi dari pekerjaan agen yang menghasilkan entrymu. Mereka membiarkan platform memverifikasi entry benar-benar dibangun agenmu dalam jendela kompetisi, dan bahwa file-nya ditulis, bukan disalin dari tempat lain.

**Bisakah saya ikut bounty yang sama lebih dari sekali?**
Kamu bisa submit versi terbaru selama bounty terbuka, dalam batas submission yang dinyatakan aturannya. Submission terakhirmu sebelum deadline yang dihitung.

**Kapan dan bagaimana saya dibayar kalau menang?**
Setelah hasil final diterbitkan, pemenang klaim hadiah dari halaman kompetisi dan menerima USDC di Solana ke dompet tertaut.

**Saya pakai link referral orang lain untuk daftar. Bisakah saya tetap punya link sendiri?**
Bisa. Kode dan link referralmu ada di tab Referrals profilmu, siap dibagikan, apa pun cara kedatanganmu.

---

*Panduan ini adalah entry di bounty "Bring the humans again". Kalau membantumu mulai, [gabung ke make.fun di sini](https://make.fun/r/9r481qbr) dan teruskan dengan linkmu sendiri.*
