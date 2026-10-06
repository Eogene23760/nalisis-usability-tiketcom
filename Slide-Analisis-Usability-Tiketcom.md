---
marp: true
theme: default
paginate: true
backgroundColor: #ffffff
color: #1a2b4a
style: |
  section {
    font-family: 'Segoe UI', Arial, sans-serif;
    padding: 60px;
  }
  h1 { color: #0064d2; }
  h2 { color: #0064d2; border-bottom: 3px solid #ffd400; padding-bottom: 8px; }
  table { font-size: 0.8em; }
  th { background: #0064d2; color: #fff; }
  tr:nth-child(even) { background: #eef4fc; }
  .lead h1 { font-size: 2.4em; }
  strong { color: #0064d2; }
  footer { color: #8a94a6; font-size: 0.6em; }
  blockquote { border-left: 5px solid #ffd400; color: #46556b; }
footer: 'Analisis Usability Tiket.com — 10 User-Interactive Guidelines'
---

<!-- _class: lead -->
<!-- _paginate: false -->

# Analisis Usability **Tiket.com**

### Evaluasi Website & Native App
### Berdasarkan 10 User-Interactive Guidelines
#### (Nielsen's Heuristics + Online Documentation)

<br>

🌐 Website · 📱 Native App (Android/iOS) · 📟 Tablet/Pad

---

## Tentang Produk

- **Tiket.com** — salah satu **Online Travel Agent (OTA)** pertama di Indonesia (berdiri **2011**, Jakarta).
- Satu aplikasi untuk banyak layanan:
  - ✈️ Tiket Pesawat  🏨 Hotel  🚆 Kereta Api
  - 🚗 Rental Mobil  🎢 Atraksi (To Do)  🎵 Konser
- **Platform:** Website responsif, Native App (Android & iOS), kompatibel tablet/pad.

> Tujuan analisis: mengevaluasi Tiket.com terhadap **10 panduan interaksi pengguna**.

---

## Metodologi

- **Kerangka:** 10 Usability Heuristics (Jakob Nielsen) + "Provide Online Documentation".
- **Sumber data:**
  - Website & aplikasi Tiket.com
  - Case study UX publik (Medium)
  - Review Google Play & App Store
  - Repositori penelitian usability (Binus, UKWMS)
- **Skala penilaian:** 1 (buruk) – 5 (sangat baik).

---

## 📊 Ringkasan Skor

| No | Guideline | Skor | Status |
|----|-----------|:----:|--------|
| 1 | Consistency & Standards | 4.5 | Sangat Baik |
| 2 | Visibility of System Status | 4.5 | Sangat Baik |
| 3 | Match System & Real World | 4.0 | Baik |
| 4 | User Control & Freedom | 3.5 | Baik |
| 5 | Error Prevention | 4.0 | Baik |
| 6 | Recognition vs Recall | 4.0 | Baik |
| 7 | Flexibility & Efficiency | 3.5 | Baik |
| 8 | Aesthetic & Minimalist | 4.0 | Baik |
| 9 | Recover from Errors | 3.5 | Baik |
| 10 | Online Documentation | 4.0 | Baik |
| | **Rata-rata** | **≈ 4.0** | **Baik → Sangat Baik** |

---

## 1️⃣ Consistency and Standards

**Prinsip:** Elemen & istilah yang sama berarti sama; ikuti konvensi platform.

✅ **Kekuatan**
- Komponen UI (tombol, kartu, warna brand) konsisten di web & app.
- Ikon kategori seragam lintas platform.
- Mengikuti Material Design (Android) & HIG (iOS).
- Pola pencarian "Asal–Tujuan–Tanggal–Penumpang" sesuai standar OTA.

⚠️ **Kelemahan**
- Gaya visual landing page promo kadang berbeda dari pola inti.

**Skor: 4.5 / 5 — Sangat Baik**

---

## 2️⃣ Visibility of System Status

**Prinsip:** Sistem selalu memberi tahu apa yang sedang terjadi.

✅ **Kekuatan**
- Loading indicator jelas ("Mencari harga terbaik...").
- Stepper alur: Pilih → Isi Data → Bayar → Selesai.
- Status pesanan real-time di **My Order 3.0** & **Trip View**.
- Countdown timer batas pembayaran.
- Notifikasi push & email tiap perubahan status.

**Skor: 4.5 / 5 — Sangat Baik**

---

## 3️⃣ Match Between System & Real World

**Prinsip:** Gunakan bahasa & konsep yang familiar bagi pengguna.

✅ **Kekuatan**
- Bahasa Indonesia sehari-hari ("Mau liburan ke mana?").
- Istilah nyata: Pulang-Pergi, Dewasa/Anak/Bayi, Check-in/out.
- Ikon metafora nyata (pesawat, ranjang, kereta).
- Pilihan bahasa ID/EN.

⚠️ **Kelemahan**
- Jargon maskapai (kelas fare, "fare rules") kurang dijelaskan.

**Skor: 4.0 / 5 — Baik**

---

## 4️⃣ User Control and Freedom

**Prinsip:** Sediakan "pintu darurat" — back, batal, undo.

✅ **Kekuatan**
- Tombol Back & breadcrumb tanpa kehilangan data pencarian.
- Fitur ubah/batal, refund & reschedule tersedia.
- Filter bisa di-reset; wishlist menyimpan pilihan.

⚠️ **Kelemahan**
- Alur booking **konser** panjang — pilih tiket & tanggal **2x**.
- Biaya refund kadang tak terduga → pengguna merasa "terjebak".

**Skor: 3.5 / 5 — Baik**

---

## 5️⃣ Error Prevention

**Prinsip:** Cegah error sebelum terjadi.

✅ **Kekuatan**
- Validasi input real-time (email, telepon, nama).
- Date picker cegah tanggal tidak valid.
- Ringkasan pesanan sebelum pembayaran.
- Auto-complete kota/bandara kurangi salah ketik.
- Kebijakan non-refundable ditandai jelas.

⚠️ **Kelemahan**
- Perubahan harga saat lanjut ke pembayaran bisa mengejutkan.

**Skor: 4.0 / 5 — Baik**

---

## 6️⃣ Recognition Rather Than Recall

**Prinsip:** Tampilkan opsi, jangan paksa pengguna mengingat.

✅ **Kekuatan**
- Riwayat pencarian terakhir di homepage.
- Autofill data penumpang dari profil.
- Saran kota/tujuan populer.
- Metode pembayaran tersimpan.
- Ikon + label (bukan ikon saja).

⚠️ **Kelemahan**
- Cara pakai poin (TIX Point) sulit dikenali sebagian pengguna.

**Skor: 4.0 / 5 — Baik**

---

## 7️⃣ Flexibility and Efficiency of Use

**Prinsip:** Akselerator untuk ahli, tetap mudah untuk pemula.

✅ **Kekuatan**
- Satu app untuk banyak layanan → efisien.
- Filter & sorting canggih (harga, bintang, waktu).
- Data tersimpan untuk repeat user.
- Promo code, TIX Point, login sosial.

⚠️ **Kelemahan**
- Beberapa alur (konser, hotel versi lama) terlalu banyak langkah.
- Skor efisiensi penelitian usability sebagian **< 70%**.

**Skor: 3.5 / 5 — Baik**

---

## 8️⃣ Aesthetic and Minimalist Design

**Prinsip:** Hindari informasi yang tak relevan.

✅ **Kekuatan**
- Tampilan bersih & modern, hierarki visual jelas.
- Whitespace & card memudahkan scanning.
- CTA utama ("Cari", "Pesan") kontras & menonjol.
- Fokus tugas utama: search bar besar di tengah.

⚠️ **Kelemahan**
- Homepage padat banner promo & pop-up → kurang minimalis.

**Skor: 4.0 / 5 — Baik**

---

## 9️⃣ Recognise, Diagnose & Recover from Errors

**Prinsip:** Pesan error jelas, tunjukkan masalah + solusi.

✅ **Kekuatan**
- Pesan manusiawi ("Pembayaran gagal, coba metode lain").
- Field salah ditandai merah + penjelasan.
- Opsi "coba lagi" / metode alternatif saat gagal bayar.

⚠️ **Kelemahan**
- Error server/koneksi kadang generik tanpa solusi.
- Diagnosis biaya refund kurang jelas (keluhan review).

**Skor: 3.5 / 5 — Baik**

---

## 🔟 Provide Online Documentation

**Prinsip:** Bantuan mudah dicari, fokus tugas, ringkas.

✅ **Kekuatan**
- **Help Center / Pusat Bantuan** di web & app, FAQ per kategori.
- **Customer Care 24 jam** (email, live chat, telepon).
- Panduan langkah refund, reschedule, ubah data.
- Asisten chat **"t-man"** untuk jawaban cepat.

⚠️ **Kelemahan**
- Sebagian artikel umum; kasus spesifik tetap hubungi agen.

**Skor: 4.0 / 5 — Baik**

---

## ✅ Kesimpulan

**Rata-rata ≈ 4.0 / 5 — Baik hingga Sangat Baik**

**Kekuatan utama:**
- 🔵 Konsistensi desain lintas platform.
- 🔵 Visibilitas status sistem (My Order 3.0, timer, tracking).
- 🔵 Kesesuaian bahasa & ikon dengan pengguna Indonesia.

**Perlu ditingkatkan:**
- 🟡 Efisiensi alur (konser & alur lama terlalu panjang).
- 🟡 Transparansi & kontrol pada refund/pembatalan.
- 🟡 Kepadatan banner di homepage.
- 🟡 Pesan error yang lebih spesifik & solutif.

---

## 💡 Rekomendasi Perbaikan

1. **Pangkas langkah** alur booking konser (hapus pemilihan ganda).
2. **Tampilkan rincian biaya refund di awal** sebelum pengguna commit.
3. **Sederhanakan homepage** — fokus ke search, promo di area sekunder.
4. **Perkaya pesan error** dengan diagnosis + langkah pemulihan jelas.

---

## 📚 Referensi

- UI/UX Case Study for Travel App (tiket.com) — Medium
- Improving Tiket.com's Flow of Booking Concert Tickets — Medium
- The long and winding road to My Order 3.0 — tiket.com Medium
- Improving TIX Point at Tiket.com Apps — Medium
- tiket.com — Google Play & App Store
- Studi Usability Tiket.com — Repositori Binus & UKWMS
- Nielsen Norman Group — 10 Usability Heuristics

> *Isi dirangkum/diparafrase ulang dari sumber publik untuk kepatuhan lisensi.*

---

<!-- _class: lead -->
<!-- _paginate: false -->

# Terima Kasih 🙏

### Analisis Usability Tiket.com
**10 User-Interactive Guidelines**
