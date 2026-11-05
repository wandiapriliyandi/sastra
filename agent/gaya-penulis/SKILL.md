---
name: gaya-penulis
description: Menangkap dan menyarikan ciri khas tulisan pemilik karya dari sampel teks (diksi, ritme kalimat, kebiasaan dialog, sudut pandang) menjadi profil gaya acuan agar draf terdengar autentik, bernyawa, dan tidak generik.
---

# Skill: Gaya Penulis (Voice Profiling)

## Kapan Dipakai
- Saat agen baru pertama kali menulis untuk proyek sastra ini atau saat pemilik memberikan contoh draf tulisan pribadinya.
- Untuk membangun dan memperbarui profil gaya penulisan acuan di `agent/profil-gaya.md`.
- Digunakan sebagai rujukan wajib sebelum menjalankan skill menulis draf (`tulis-bab`, `tulis-cerpen`, `serialisasi`, `dialog`, `puisi`).

> **Konteks Sasaran Pembaca**: Pemetaan gaya pemilik harus mempertimbangkan sasaran pembaca bawaan proyek, yaitu **Remaja (13–18 tahun)**: mengutamakan kelincahan bahasa yang akrab, lugas, dan hidup tanpa merendahkan kecerdasan pembaca muda.

## Alur Kerja Langkah demi Langkah
1. **Analisis Sampel Teks Pemilik**:
   - Ambil 2–3 contoh kutipan adegan atau naskah asli dari pemilik.
   - Bedah aspek linguistik:
     - **Struktur & Ritme Kalimat**: Rasio kalimat pendek tajam vs kalimat panjang bertingkat; kecenderungan jeda koma; pemenggalan paragraf.
     - **Ciri Khas Diksi**: Kosakata dominan (puitis, arkais, bersahaja, lugas, atau berbau kearifan lokal tertentu).
     - **Perilaku Dialog**: Penggunaan partikel lisan Indonesia (*sih, kok, kan, dong, toh*), tingkat kepanjangan tuturan, dan frekuensi selaan aksi.
     - **Jarak Psikis & Narasi**: Kedekatan emosional *Deep POV* vs narator pengamat.
2. **Penyusunan Profil Gaya (Style Guide)**:
   - Rangkum parameter gaya ke dalam butir-butir poin acuan yang aplikatif.
   - Daftarkan kata-kata atau konstruksi kalimat yang disukai dan yang wajib dihindari.
3. **Penyimpanan Profil Acuan**:
   - Simpan hasil pemetaan ke berkas: `agent/profil-gaya.md`.
4. **Penerapan pada Draf**:
   - Agen penulis membaca `agent/profil-gaya.md` sebelum menyusun draf agar suara tulisan konsisten dengan nada pemilik.

## Aturan Mutu
- **Autentik & Bukan AI Slop**: Hindari membuat profil yang generik. Tangkap keunikan gaya pemilik yang menyatu dengan dunia pembaca remaja.
- **Poin Ringkas Operasional**: Rumuskan dalam aturan praktis yang langsung bisa diperiksa saat menulis.
- **Dinamis & Terus Diasah**: Profil dapat disempurnakan seiring bertambahnya bab atau cerpen yang disetujui pemilik.

## Format Keluaran
Berkas disimpan di: `agent/profil-gaya.md`

```markdown
# Profil Gaya Penulis: [Nama / Label Gaya]

> **Konteks Audiens**: Pembaca Remaja (13–18 tahun) / Umum

## 1. Ritme Kalimat & Panjang Paragraf
- **Kombinasi Ritme**: [Misal: 2 kalimat pendek menghentak disusul 1 kalimat mengalir]
- **Kerapatan Paragraf**: [Maksimal 3–4 baris per paragraf]

## 2. Karakteristik Diksi & Kosakata
- **Kosakata Khas**: [Daftar kata-kata beraroma lokal/sastra yang sering dipakai]
- **Kata yang Diharamkan**: [Klise AI dan kata mubazir yang dilarang]

## 3. Gaya Tutur Dialog
- **Partikel Alami**: [Penggunaan kata percakapan wajar anak muda/remaja santun]
- **Keseimbangan Beat**: [Rasio aksi fisik terhadap ucapan]

## 4. Jarak Psikis (POV)
- [Derajat keintiman batin narator]
```
