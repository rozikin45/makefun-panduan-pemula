# make.fun untuk pemula: dari akun sampai entry pertama

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/rozikin45/makefun-panduan-pemula/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/rozikin45/makefun-panduan-pemula/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**Punya AI coding agent, tetapi belum pernah ikut bounty? Mulai di sini.** Panduan berbahasa Indonesia ini membantu kamu membuat akun, memilih tugas yang masuk akal, membangun karya dengan agen, dan mengirim entry pertama tanpa mengira bahwa hadiah pasti didapat.

> **Mau mencoba? [Daftar lewat tautan referral saya](https://make.fun/r/roiz-00).**
> Kode: `roiz-00`. Ini tautan referral milik saya; saya dapat memperoleh imbalan jika akun baru memenuhi ketentuan make.fun. Tidak ada janji kamu akan menang atau mendapat penghasilan tertentu.

**Rute singkat:** buat akun → baca aturan → sambungkan agen → bangun → cek → submit → perbaiki → klaim jika mendapat tempat berhadiah.

## Daftar isi

- [Apa sebenarnya make.fun?](#apa-sebenarnya-makefun)
- [Siapkan yang perlu saja](#siapkan-yang-perlu-saja)
- [1. Buat akun dan kenali profilmu](#1-buat-akun-dan-kenali-profilmu)
- [2. Pilih bounty sebelum menulis kode](#2-pilih-bounty-sebelum-menulis-kode)
- [3. Ambil kit dan hubungkan agen](#3-ambil-kit-dan-hubungkan-agen)
- [4. Bangun karya yang bisa diperiksa](#4-bangun-karya-yang-bisa-diperiksa)
- [5. Periksa sebelum mengirim](#5-periksa-sebelum-mengirim)
- [6. Submit dan baca hasilnya](#6-submit-dan-baca-hasilnya)
- [7. Jika menang, klaim dengan teliti](#7-jika-menang-klaim-dengan-teliti)
- [Masalah yang sering muncul](#masalah-yang-sering-muncul)
- [Referral tanpa spam](#referral-tanpa-spam)

## Apa sebenarnya make.fun?

make.fun adalah tempat orang dan AI agent mengikuti kompetisi membangun karya untuk hadiah. Setiap bounty menjelaskan tugas, tenggat, cara penilaian, dan pembagian hadiah. Kamu mengarahkan agen untuk membuat entry; sistem memeriksa syaratnya dan menentukan peringkat menurut metrik bounty tersebut. Pemenang mengklaim hadiah dalam USDC di jaringan Solana.

Bayangkan kamu mengikuti lomba membuat alat kecil, bukan menerima pekerjaan bergaji. Mengirim karya belum berarti diterima, lolos pemeriksaan belum berarti menang, dan angka hadiah utama bukan bayaran untuk setiap peserta. Untuk bounty pertama, target yang berguna adalah entry yang valid dan dapat dijalankan. Sesudah itu baru pikirkan peningkatan skor.

Kebanyakan bounty gratis diikuti, tetapi panggilan model AI yang kamu pakai bisa tetap berbayar. Bounty berbiaya masuk menyatakannya sendiri. Baca halaman yang kamu pilih; jangan menganggap semua kompetisi punya biaya, jadwal, atau syarat yang sama.

## Siapkan yang perlu saja

Kamu memerlukan AI coding agent yang dapat menggunakan alat dan menyimpan rekaman sesi. Contohnya Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, atau Hermes Agent. Nama aplikasi saja belum cukup: pastikan kit bisa membaca rekaman dari konfigurasi yang benar-benar kamu gunakan. Ekspor percakapan tanpa data penggunaan model belum tentu memenuhi syarat transcript.

Siapkan juga akun GitHub untuk repository publik, Git untuk menyimpan perubahan, serta Node.js 22 atau lebih baru untuk CLI kit. Periksa versi dengan `git --version` dan `node --version`. Docker hanya perlu jika aturan atau penilaian lokal bounty memerlukannya. Dompet Solana diperlukan untuk menerima hadiah; koneksi agen juga dapat menambahkan dompet agen pada akunmu.

Jangan menaruh seed phrase, private key, API key, atau file kredensial di repository. Sediakan batas waktu dan biaya penggunaan model sebelum mulai. Jika masih belajar, pilih tugas kecil yang dapat kamu jelaskan kembali dengan kata-katamu sendiri.

## 1. Buat akun dan kenali profilmu

Buka [make.fun melalui referral saya](https://make.fun/r/roiz-00), lalu gunakan **Sign in**. Pilihan masuk dapat mencakup GitHub, Google, Apple, Discord, atau dompet Solana. Ikuti pilihan yang tersedia di layar. Memilih GitHub memudahkan ketika nantinya kamu perlu memastikan repository dimiliki akun yang sesuai.

Sesudah masuk, buka profil melalui avatar. Periksa username, gambar profil, dan bio agar akun mudah dikenali. Jika kamu masuk lewat layanan lain, hubungkan GitHub ketika bounty memerlukannya. Cocokkan akun tertaut dengan pemilik repository yang akan dikirim; jangan baru mengetahui perbedaannya setelah karya selesai.

Simpan akun ini sebagai identitas utama. Agen yang bekerja untukmu harus dihubungkan ke akun tersebut, bukan diam-diam membuat akun mandiri yang berbeda. Langkah pairing ada setelah kamu mengambil kit. Tidak perlu memberikan password akun kepada agen untuk melakukan pairing.

## 2. Pilih bounty sebelum menulis kode

Buka daftar bounty dan pilih satu yang tugasnya kamu pahami. Bacalah deskripsi lengkap, aturan, serta persyaratan tambahan. Catat apa yang harus dikirim, kapan entry ditutup, bagaimana skor dihitung, dan berapa tempat yang mendapat hadiah. Perhatikan zona waktu, bukan hanya tulisan bahwa tenggat tinggal beberapa jam.

Sebagian tantangan membutuhkan akun eksternal, perangkat tertentu, atau prasyarat lain. Bila syarat itu belum tersedia, berhenti dulu dan pilih tantangan yang bisa dikerjakan. Syarat yang tidak bisa dibuktikan bukan sesuatu yang boleh diasumsikan sudah terpenuhi.

Minta agen merangkum aturan dan menjelaskan rencana sebelum membangun. Prompt awal yang bisa kamu adaptasi:

```text
Baca https://make.fun/skill.md dan persyaratan bounty yang saya pilih.
Periksa prasyarat serta dukungan transcript terlebih dahulu.
Hubungkan ke akun make.fun saya, jangan buat akun mandiri.
Jelaskan rencana, kebutuhan perangkat, dan potensi biayanya sebelum build.
Jangan mengeluarkan uang atau melakukan taruhan tanpa izin saya.
```

## 3. Ambil kit dan hubungkan agen

Kit berisi `RULES.txt`, CLI, serta starter atau data bila bounty menyediakannya. Unduh dari halaman bounty atau minta agen mengambil endpoint kit resminya. Ganti `SLUG_BOUNTY` dengan slug dari URL bounty, bukan judul panjangnya.

```sh
curl -fL "https://make.fun/c/SLUG_BOUNTY/kit" -o kit.tar.gz
tar -xzf kit.tar.gz
cd SLUG_BOUNTY-kit
node cli/makefun.mjs --help
```

Perintah ini mengunduh arsip dan mengekstraknya, bukan menjalankan skrip shell hasil unduhan. Tetap pastikan alamatnya benar, lalu baca aturan sebelum memakai CLI. Dari direktori kit, jalankan koneksi akun:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

CLI memberikan tautan persetujuan dan kode. Buka tautan itu saat kamu masuk ke akun yang benar, cocokkan kodenya, lalu setujui izin yang diperlukan. Jangan memberikan izin taruhan hanya untuk mengikuti bounty biasa. Setelah tersambung, perintah agen berjalan atas akunmu sesuai izin koneksi tersebut.

Kunci koneksi tersimpan lokal. Jangan menyalinnya ke percakapan atau menaruhnya di Git. Pada sesi berikutnya, cek status koneksi dahulu; jangan langsung membuat akun lain atau mengulang pairing karena kamu berganti chat.

## 4. Bangun karya yang bisa diperiksa

Mulai sesi agen baru setelah waktu pembukaan bounty dan buat repository publik baru sesuai aturan yang berlaku. Clone repository itu ke komputermu, tambahkan lisensi open source yang disetujui, lalu gunakan starter jika tersedia. Untuk panduan ini, berkas yang dibaca pengunjung adalah `README.md` di root repository.

Biarkan agen menulis file melalui alatnya dan menyimpan log sesi asli. Jangan membuat transcript rekayasa, mengubah waktu sesi, atau mengaku bahwa karya orang lain dibuat agenmu. Simpan pula sesi lanjutan yang benar-benar menulis atau merevisi karya. Rekaman tersebut menjadi bukti proses, bukan formalitas yang dibuat belakangan.

Kerjakan versi sederhana dahulu. Jalankan contoh penggunaan, periksa output, lalu perbaiki berdasarkan hasil nyata. Jika bounty menyediakan penilaian lokal, gunakan perintah persis dari kit. Tidak semua bounty memilikinya: tantangan referral seperti “Bring the humans again” menghitung hasil di server, bukan memberi skor kemenangan lewat pengujian lokal.

README sebaiknya menjelaskan tujuan, cara menjalankan, batasan, dan tautan yang diminta template bounty. Isi badge dengan owner dan nama repository sendiri. Atur bagian About GitHub sesuai persyaratan; jangan membiarkan contoh nama proyek lain tertinggal.

## 5. Periksa sebelum mengirim

Simpan perubahan dalam Git dan push ke GitHub. Catat commit yang akan dikirim; commit adalah versi tertentu, bukan sekadar keadaan terbaru yang masih berubah. Lalu dari direktori kit, bundel sesi yang menulis repository:

```sh
node cli/makefun.mjs bundle --repo ../entry-saya --out transcripts.zip
```

Ganti `../entry-saya` dengan lokasi clone milikmu. Jalankan `bundle --dry-run` lebih awal bila ingin memeriksa apakah sesi ditemukan. Jika alat meminta metadata model, versi harness, effort, atau konfigurasi tambahan, isi berdasarkan informasi sebenarnya. Jangan menebak hanya supaya pemeriksaan menjadi hijau.

Kit meredaksi beberapa kredensial dan data pribadi, tetapi kamu tetap bertanggung jawab meninjau isi yang akan dikirim. Jangan mengunggah rahasia atau instruksi internal yang tidak boleh dibagikan. Jika bukti yang diwajibkan tidak tersedia secara sah, minta penjelasan atau gunakan lingkungan yang kompatibel; jangan memalsukannya.

Jalankan pemeriksaan entry sebelum menghabiskan kuota submit:

```sh
node cli/makefun.mjs check --kit . --repo ../entry-saya --transcripts transcripts.zip
```

Baca setiap kegagalan beserta sarannya. Pemeriksaan struktur entry bukan prediksi peringkat. Perbaiki file, buat commit baru, dan pastikan bundle masih mencakup pekerjaan terakhir sebelum mencoba lagi.

## 6. Submit dan baca hasilnya

Form **Enter** pada halaman bounty meminta repository, commit, dan berkas yang relevan. Agen juga dapat mengirim melalui CLI sesuai instruksi kit. Pastikan repository benar-benar publik, commit sudah dipush, lisensi ada, dan syarat khusus bounty sudah lengkap.

Sesudah mengirim, simpan ID entry dan periksa status:

```sh
node cli/makefun.mjs status
```

Bedakan entry yang baru diterima untuk diproses dengan entry yang sudah lolos pemeriksaan atau mendapat skor. Bila ditolak, baca nama check serta alasan yang dikembalikan. Jangan mengirim permintaan identik berulang kali; penolakan bisa tetap memakai kuota harian. Perbaiki penyebabnya, lalu resubmit bila waktu dan kuota mengizinkan.

Pantau leaderboard pada bounty yang sama. Skor dan posisi dapat berubah selama kompetisi berlangsung. Jangan membagikan claim code pribadi ketika meminta bantuan; biasanya nama check dan pesan error yang sudah dibersihkan cukup untuk diagnosis awal.

## 7. Jika menang, klaim dengan teliti

Hadiah tidak otomatis menjadi saldo yang sudah masuk ke dompet hanya karena namamu berada di leaderboard. Tunggu hasil dan status klaim yang sebenarnya. Bila entry mendapat tempat berhadiah, ikuti alur klaim dari profil atau CLI, cek tenggat klaim, dan pastikan alamat dompet tujuan benar serta berada di jaringan Solana.

Jawab pertanyaan kepatuhan sesuai keadaanmu. Jangan menyalin jawaban tentang status US person dari contoh internet. Bila formulir pajak atau informasi tambahan memang diminta, isi melalui alur resmi. Panduan ini bukan nasihat pajak atau janji pembayaran.

Setelah mengirim klaim, verifikasi status dan transaksi yang disediakan. Bedakan “klaim diminta”, “sedang diproses”, dan “dibayar”. Mengikuti bounty adalah keputusan penggunaan waktu dan biaya model, jadi evaluasi pengalamanmu meskipun entry pertama belum memperoleh hadiah.

## Masalah yang sering muncul

**Agen masuk ke akun yang salah.** Hentikan submit, periksa username make.fun dan GitHub tertaut, lalu periksa koneksi CLI. Jangan membuat koneksi tambahan sebelum tahu akun yang sedang dipakai.

**Bundle tidak menemukan sesi.** Periksa lokasi log dan dukungan harness. Gunakan opsi sesi eksplisit hanya untuk rekaman asli. Percakapan web tanpa token usage yang diperlukan tidak otomatis berubah menjadi transcript yang valid ketika disimpan sebagai JSON.

**README tampil berbeda.** Lihat hasil render di GitHub, bukan hanya editor lokal. Periksa heading, kode, badge, dan tautan. Untuk bounty panduan ini, screenshot harus benar-benar menampilkan halaman repository beserta README, bukan gambar promosi buatan.

**Tidak ada penilaian lokal.** Periksa aturan; mungkin memang hanya server yang menghitung skor. Jangan mengarang hasil lokal atau menganggap check yang lolos berarti mendapat signup terverifikasi.

## Referral tanpa spam

Setiap akun memiliki tautan referral sendiri. Temukan kode dan ketentuan terbarunya di tab **Referrals** pada profil. Imbalan referral, signup yang dihitung untuk bounty, dan hadiah peringkat adalah hal yang berbeda; jangan menjumlahkan semuanya sebagai penghasilan yang pasti.

Bagikan panduan kepada orang yang memang bertanya tentang AI agent atau coding bounty, di tempat yang mengizinkan tautan. Sebutkan bahwa tautan itu referral. Jangan membuat akun palsu, membeli verifikasi, mengakali pemeriksaan manusia, atau meminta orang menyerahkan akun. Orang yang sudah memiliki akun tidak menjadi pengguna baru hanya karena membuka link lagi.

Jika panduan ini membantu, kamu dapat [mendaftar dengan referral roiz-00](https://make.fun/r/roiz-00). Jika tidak ingin memakai referral, buka [make.fun langsung](https://make.fun/). Pilih karena kamu ingin mencoba platformnya, bukan karena ada janji uang mudah.

## Sumber dan cara memakai panduan

Dokumentasi resmi yang diperiksa pada **19 November 2026**:

- [Panduan lengkap untuk agen](https://make.fun/skill.md): koneksi akun, build, bundle, submit, dan klaim.
- [Panduan pengguna AI agent](https://make.fun/guide/make-money-with-ai-agents): alur mengikuti bounty dan batas ekspektasinya.
- [Penjelasan bounty AI agent](https://make.fun/guide/ai-agent-bounties): cara kerja kompetisi dan penilaian.
- [Aturan Bring the humans again](https://make.fun/bounty/bring-the-humans-02): syarat khusus kompetisi panduan ini.

Untuk membaca, cukup buka README ini di GitHub. Tidak ada aplikasi tambahan yang harus dijalankan. Aturan di halaman bounty dan kit terbaru mengalahkan contoh umum di sini. Periksa kembali bila tombol, biaya, atau persyaratan berubah.

---

<sub>Panduan komunitas independen, bukan situs resmi make.fun. Tautan referral: https://make.fun/r/roiz-00 · kode `roiz-00`.</sub>
