# Analisis Usability — Tiket.com
### Evaluasi Website & Native App Berdasarkan 10 User-Interactive Guidelines (Nielsen's Heuristics + Online Documentation)

> **Objek analisis:** Tiket.com (website `tiket.com` & aplikasi mobile Android/iOS "tiket.com: Hotels & Flights")
> **Jenis produk:** Online Travel Agent (OTA) — pemesanan tiket pesawat, hotel, kereta, rental mobil, atraksi/To Do, dan konser.
> **Platform:** Web (desktop & mobile web), Native App (Android & iOS), kompatibel tablet/pad.

---

## Ringkasan Produk

Tiket.com adalah salah satu Online Travel Agent (OTA) pertama di Indonesia (berdiri 2011, berbasis di Jakarta). Produk ini mengintegrasikan banyak layanan perjalanan dalam satu aplikasi: tiket pesawat, hotel, kereta api, rental mobil, airport transfer, atraksi (To Do), dan konser. Produk tersedia dalam bentuk **website responsif** dan **native app** yang berjalan baik pada smartphone maupun tablet/pad.

Analisis berikut mengevaluasi Tiket.com berdasarkan 10 panduan interaksi pengguna (sebagian besar merujuk ke *10 Usability Heuristics* dari Jakob Nielsen, ditambah panduan "Online Documentation").

---

## Tabel Ringkasan Penilaian

| No | Guideline | Skor (1–5) | Status |
|----|-----------|:----------:|--------|
| 1 | Consistency and Standards | 4.5 | Sangat Baik |
| 2 | Visibility of System Status | 4.5 | Sangat Baik |
| 3 | Match Between System and Real World | 4.0 | Baik |
| 4 | User Control and Freedom | 3.5 | Baik |
| 5 | Error Prevention | 4.0 | Baik |
| 6 | Recognition Rather Than Recall | 4.0 | Baik |
| 7 | Flexibility and Efficiency of Use | 3.5 | Baik |
| 8 | Aesthetic and Minimalist Design | 4.0 | Baik |
| 9 | Help Users Recognise, Diagnose & Recover from Errors | 3.5 | Baik |
| 10 | Provide Online Documentation | 4.0 | Baik |
| | **Rata-rata** | **≈ 4.0** | **Baik → Sangat Baik** |

---

## 1. Consistency and Standards (Konsistensi dan Standar)

**Prinsip:** Pengguna tidak perlu menebak apakah kata, situasi, atau tindakan yang berbeda memiliki arti yang sama. Ikuti konvensi platform dan industri.

**Temuan pada Tiket.com:**
- Komponen UI (tombol, kartu produk, warna brand biru-kuning) konsisten di seluruh halaman web maupun app.
- Ikon kategori (pesawat, hotel, kereta, mobil, To Do) seragam antara web dan native app, sehingga pengguna yang berpindah platform tidak kebingungan.
- Mengikuti **standar platform**: pola Material Design di Android dan Human Interface Guidelines di iOS (bottom navigation, back gesture).
- Pola pencarian "Asal–Tujuan–Tanggal–Penumpang" mengikuti konvensi umum industri OTA (mirip Traveloka, Agoda), sehingga mudah dikenali.

**Kelemahan minor:**
- Beberapa alur promo/landing page kadang memakai gaya visual kampanye yang sedikit berbeda dari pola inti.

**Skor: 4.5/5 — Sangat Baik.**

---

## 2. Visibility of System Status (Visibilitas Status Sistem)

**Prinsip:** Sistem harus selalu memberi tahu pengguna apa yang sedang terjadi melalui umpan balik yang tepat waktu.

**Temuan pada Tiket.com:**
- **Loading indicator** jelas saat mencari penerbangan/hotel ("Mencari harga terbaik...").
- **Progress indicator / stepper** pada alur pemesanan: Pilih → Isi Data → Pembayaran → Selesai.
- Status pesanan ditampilkan real-time pada menu **My Order / Orders** (misalnya: "Menunggu Pembayaran", "E-tiket Terbit", "Selesai").
- **Countdown timer** untuk batas waktu pembayaran memberi tahu sisa waktu transaksi.
- Notifikasi push & email mengkonfirmasi setiap perubahan status.

**Catatan:** Fitur "My Order 3.0" dan "Trip View" dirancang khusus agar pengguna lebih mudah memantau status semua pesanan dalam satu perjalanan.

**Skor: 4.5/5 — Sangat Baik.**

---

## 3. Match Between System and the Real World (Kesesuaian dengan Dunia Nyata)

**Prinsip:** Gunakan bahasa, istilah, dan konsep yang familiar bagi pengguna, bukan jargon sistem.

**Temuan pada Tiket.com:**
- Bahasa Indonesia sehari-hari yang akrab ("Mau liburan ke mana?", "Cari Hotel", "Pesan Sekarang").
- Istilah dunia nyata: "Pulang-Pergi", "Sekali Jalan", "Dewasa/Anak/Bayi", "Check-in / Check-out".
- Ikon metafora nyata: pesawat, ranjang hotel, kereta, mobil.
- Tersedia opsi bahasa (ID/EN) sehingga sesuai konteks pengguna lokal maupun internasional.
- Urutan informasi logis mengikuti cara orang merencanakan perjalanan (tujuan → tanggal → penumpang → harga).

**Kelemahan minor:**
- Beberapa istilah teknis maskapai (kelas fare, kode booking, "fare rules") masih muncul tanpa penjelasan sederhana.

**Skor: 4.0/5 — Baik.**

---

## 4. User Control and Freedom (Kontrol dan Kebebasan Pengguna)

**Prinsip:** Pengguna butuh "pintu darurat" — undo, redo, batal, dan kembali dengan mudah.

**Temuan pada Tiket.com:**
- Tombol **Back** dan navigasi breadcrumb memudahkan kembali ke langkah sebelumnya tanpa kehilangan data pencarian.
- Fitur **ubah/batal pesanan** dan **refund/reschedule** tersedia (tergantung kebijakan maskapai/hotel).
- Filter pencarian bisa diubah/di-reset kapan saja.
- Keranjang/wishlist memungkinkan menyimpan pilihan tanpa harus langsung membeli.

**Kelemahan (sesuai temuan studi UX pengguna):**
- Alur pemesanan **tiket konser** pernah dikeluhkan panjang — pengguna harus memilih tiket & tanggal **dua kali**, menandakan kurangnya kebebasan mundur-maju yang efisien.
- Proses **refund** disertai biaya layanan yang kadang tidak diantisipasi pengguna, memunculkan rasa "terjebak".

**Skor: 3.5/5 — Baik (ada ruang perbaikan pada alur batal/ubah).**

---

## 5. Error Prevention (Pencegahan Kesalahan)

**Prinsip:** Lebih baik mencegah error terjadi daripada menampilkan pesan error.

**Temuan pada Tiket.com:**
- **Validasi input real-time**: format email, nomor telepon, dan nama penumpang dicek sebelum lanjut.
- **Date picker** mencegah pemilihan tanggal yang tidak valid (misal tanggal pulang sebelum berangkat).
- **Konfirmasi sebelum pembayaran**: ringkasan pesanan ditampilkan agar pengguna mengecek ulang.
- **Auto-complete** kota/bandara mengurangi salah ketik.
- Peringatan sebelum aksi kritikal (misal batas waktu pembayaran, kebijakan non-refundable ditandai jelas).

**Kelemahan minor:**
- Perbedaan tarif/harga yang berubah saat lanjut ke pembayaran bisa mengejutkan pengguna jika tidak diinformasikan lebih awal.

**Skor: 4.0/5 — Baik.**

---

## 6. Recognition Rather Than Recall (Pengenalan Dibanding Mengingat)

**Prinsip:** Minimalkan beban memori pengguna — tampilkan opsi daripada memaksa mengingat.

**Temuan pada Tiket.com:**
- **Riwayat pencarian terakhir** ditampilkan di halaman utama (pengguna tak perlu mengetik ulang).
- **Autofill data penumpang** dari profil tersimpan.
- **Daftar kota/tujuan populer** muncul sebagai saran.
- Metode pembayaran yang pernah dipakai disimpan untuk dipilih ulang.
- Ikon + label (bukan ikon saja) membantu pengenalan fungsi.

**Kelemahan minor:**
- Pada fitur loyalty (TIX Point), studi UX menemukan sebagian pengguna sulit menemukan/mengenali cara menggunakan poin — informasi masih perlu "diingat/dicari".

**Skor: 4.0/5 — Baik.**

---

## 7. Flexibility and Efficiency of Use (Fleksibilitas dan Efisiensi)

**Prinsip:** Akselerator untuk pengguna ahli, tanpa membebani pengguna baru.

**Temuan pada Tiket.com:**
- **Satu aplikasi untuk banyak layanan** (flight, hotel, kereta, mobil, To Do) → efisien, tak perlu banyak app.
- **Filter & sorting** canggih (harga, bintang, fasilitas, waktu berangkat) mempercepat pengguna ahli.
- **Pencarian cepat** dengan data tersimpan untuk repeat user.
- **Promo code & TIX Point** mempercepat checkout bagi pengguna loyal.
- Login via Google/Apple/sosial mempercepat onboarding.

**Kelemahan (temuan studi UX):**
- Beberapa alur (mis. booking konser, booking hotel versi lama) dinilai **kurang efisien** dan terlalu banyak langkah; penelitian usability menemukan sejumlah skor efisiensi masih di bawah 70%.

**Skor: 3.5/5 — Baik.**

---

## 8. Aesthetic and Minimalist Design (Desain Estetis dan Minimalis)

**Prinsip:** Antarmuka tidak boleh memuat informasi yang tidak relevan/jarang dibutuhkan.

**Temuan pada Tiket.com:**
- Tampilan **bersih dan modern**, hierarki visual jelas (judul, kartu, CTA menonjol).
- Penggunaan **whitespace** dan **kartu (card)** membuat informasi mudah dipindai.
- Warna brand konsisten; CTA utama ("Cari", "Pesan") kontras & menonjol.
- Fokus pada tugas utama di halaman depan (search bar besar di tengah).

**Kelemahan minor:**
- Halaman depan kadang **padat dengan banner promo**, pop-up, dan rekomendasi, sehingga mengurangi kesan minimalis dan dapat mengalihkan fokus pengguna.

**Skor: 4.0/5 — Baik.**

---

## 9. Help Users Recognise, Diagnose, and Recover from Errors (Bantu Mengenali, Mendiagnosis & Memulihkan Error)

**Prinsip:** Pesan error dalam bahasa jelas, menunjukkan masalah, dan menawarkan solusi.

**Temuan pada Tiket.com:**
- Pesan error ditulis dalam bahasa manusiawi ("Pembayaran gagal, silakan coba metode lain").
- Field yang salah ditandai merah dengan penjelasan ("Nomor telepon tidak valid").
- Jika pembayaran gagal, sistem menawarkan **coba lagi** atau metode alternatif.
- Status pesanan "gagal/kadaluarsa" disertai arahan langkah berikutnya.

**Kelemahan:**
- Beberapa error server/koneksi masih memunculkan pesan generik tanpa langkah pemulihan spesifik.
- Pada kasus refund, pengguna mengeluh kurangnya kejelasan diagnosis mengapa dikenai biaya (lihat review App Store), menandakan recovery dari "error ekspektasi" belum optimal.

**Skor: 3.5/5 — Baik.**

---

## 10. Provide Online Documentation (Sediakan Dokumentasi Online)

**Prinsip:** Sediakan bantuan & dokumentasi yang mudah dicari, fokus pada tugas pengguna, dan ringkas langkah-langkahnya.

**Temuan pada Tiket.com:**
- **Help Center / Pusat Bantuan** tersedia di web & app, dengan FAQ terstruktur per kategori produk.
- **Customer Care 24 jam** via email (cs@tiket.com), live chat, dan telepon.
- Panduan langkah-demi-langkah untuk refund, reschedule, dan perubahan data.
- Petunjuk mengganti bahasa, mengelola pesanan, dan menggunakan poin tersedia di dokumentasi.
- Asisten/chat ("t-man") membantu pengguna menemukan jawaban cepat.

**Kelemahan minor:**
- Sebagian artikel bantuan cukup umum; kasus spesifik tetap harus menghubungi agen, menambah waktu penyelesaian.

**Skor: 4.0/5 — Baik.**

---

## Kesimpulan

Secara keseluruhan, **Tiket.com menunjukkan kualitas usability yang Baik hingga Sangat Baik (rata-rata ≈ 4.0/5)** berdasarkan 10 panduan interaksi pengguna. Kekuatan utamanya terletak pada:

- **Konsistensi** desain lintas platform (web, Android, iOS, tablet).
- **Visibilitas status sistem** yang kuat (tracking pesanan, timer pembayaran, My Order 3.0).
- **Kesesuaian dengan dunia nyata** melalui bahasa & ikon yang familiar bagi pengguna Indonesia.

Area yang masih perlu ditingkatkan:

1. **Efisiensi alur tertentu** — khususnya pemesanan konser dan beberapa alur lama yang terlalu panjang.
2. **User control pada refund/pembatalan** — transparansi biaya & kemudahan membatalkan.
3. **Desain minimalis** — mengurangi kepadatan banner promo di halaman depan.
4. **Recovery dari error** — pesan error yang lebih spesifik dan solutif.

### Rekomendasi Perbaikan
- Pangkas langkah pada alur booking konser (hilangkan pemilihan ganda tiket & tanggal).
- Tampilkan rincian biaya refund **di awal** sebelum pengguna commit.
- Sederhanakan homepage agar fokus ke tugas utama (search), promo di bagian sekunder.
- Perkaya pesan error dengan diagnosis + langkah pemulihan yang jelas.

---

## Referensi
- [UI/UX Case Study for Travel App (tiket.com) — Medium](https://medium.com/@dans.idam/ui-ux-case-study-for-travel-app-tiket-com-c1db26671a3f)
- [Improving Tiket.com's Flow of Booking Concert Tickets: A UX Case Study — Medium](https://medium.com/@jeannyanggr/improving-tiket-coms-flow-of-booking-concert-tickets-a-ux-case-study-d18b130b9d07)
- [The long and winding road to My Order 3.0 — tiket.com Medium](https://medium.com/tiket-com/the-long-and-winding-road-to-my-order-3-0-49f9e027fee1)
- [Case Study: Redesign Review Hotel — Medium](https://medium.com/@rahmatulhusna/case-study-redesign-review-hotel-da234072ef65)
- [Improving TIX Point at Tiket.com Apps — Medium](https://medium.com/@alfianiman17/improving-tix-point-at-tiket-com-apps-my-first-ux-case-study-264fe1bdc196)
- [tiket.com: Hotels & Flights — Google Play](https://play.google.com/store/apps/details?id=com.tiket.gits)
- [tiket.com: Hotels & Flights — App Store](https://apps.apple.com/id/app/tiket-com-hotels-flights/id890405921)
- [Studi Usability Tiket.com — Repositori Binus](http://library.binus.ac.id/eColls/eThesisdoc/Abstrak/RS1_2019_2_1715_2001608351_Abstrak.pdf)
- [Nielsen Norman Group — 10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/)

> *Catatan: Beberapa isi dirangkum/diparafrase ulang dari sumber untuk kepatuhan lisensi. Analisis bersifat evaluatif berdasarkan sumber publik dan prinsip heuristik usability.*
