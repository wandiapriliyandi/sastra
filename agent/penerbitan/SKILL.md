---
name: penerbitan
description: Mengelola alur penerbitan mandiri (self-publishing) atau pra-rilis karya fiksi: penyiapan berkas akhir siap cetak/digital, metadata penerbitan, daftar periksa kualitas pra-rilis, hingga perilisan ke platform tujuan.
---

# Skill: Penerbitan (Self-Publishing & Distribution)

## Kapan Dipakai
- Saat sebuah naskah novel atau cerpen telah berstatus `Jadi` dan selesai melalui seluruh tahapan swa-sunting dan uji pembaca beta.
- Untuk menyiapkan paket berkas terbit (format cetak PDF/POD atau format digital EPUB/PDF) dan merilisnya ke platform pilihan (Google Play Books, KaryaKarsa, Gramedia Digital, atau penerbit indie).

## Alur Kerja Langkah demi Langkah
1. **Verifikasi Status Naskah Final**:
   - Pastikan naskah sudah bersih dari catatan editor, penanda komentar (*to-do*), dan telah lolos pemeriksaan aksara akhir (*proofreading*).
2. **Penyusunan Metadata & Kolofon**:
   - Judul utama dan sub-judul.
   - Nama penulis, hak cipta (copyright), tahun rilis, dan pernyataan hak cipta.
   - Sinopsis belakang buku (blurb), kategori/genre, dan kata kunci penelusuran (*keywords / tags*).
   - Penentuan batas usia pembaca (*age rating / content warning* jika memuat kekerasan/isu sensitif).
3. **Penataan Anatomi Buku Utuh**:
   - **Halaman Depan (Front Matter)**: Halaman judul, hak cipta, persembahan/dedikasi, epigraf, daftar isi.
   - **Isi Utama (Body Matter)**: Teks babak dan bab yang telah tersusun rapi.
   - **Halaman Belakang (Back Matter)**: Catatan penulis, ucapan terima kasih (*acknowledgments*), biodata naratif penulis, dan cuplikan karya berikutnya.
4. **Daftar Periksa Pra-Rilis (Pre-Release Checklist)**:
   - Periksa tata letak margin, nomor halaman, konsistensi jenis huruf (*font typography*), dan sampul beresolusi tinggi.
5. **Pencatatan Status Rilis**:
   - Perbarui entri karya di `INDEKS_KARYA.md` menjadi berstatus `Terbit`.

## Aturan Mutu
- **Nol Kesalahan Tata Huruf**: Teks akhir tidak boleh memuat salah ketik yang mencolok atau format paragraf yang berantakan.
- **Kelengkapan Hak Cipta**: Kolofon dan atribusi penulis harus tercantum jelas untuk perlindungan hak cipta karya.
- **Ramping & Praktis**: Jangan membuat panduan teknis platform yang berubah-ubah; fokus pada standar kesiapan berkas naskah.

## Format Keluaran
Disimpan di folder karya terkait: `novel/<judul-novel>/metadata-terbit.md`

```markdown
# Paket Metadata Penerbitan: [Judul Karya]

## 1. Identitas & Legalitas
- **Judul Utama**: 
- **Penulis**: 
- **Tahun Terbit / Edisi**: 
- **Hak Cipta**: © [Tahun] [Nama Penulis]. Hak cipta dilindungi undang-undang.
- **Klasifikasi Usia / Rating**: [Semua Umur / Remaja 13+ / Dewasa 18+]
- **Kategori / Rak Buku**: [Fiksi / Sastra Indonesia / Misteri]

## 2. Deskripsi & Pemasaran
- **Blurb Sampul Belakang**: [Teks blurb pemikat]
- **Kata Kunci Penelusuran (Tags)**: [kata-kunci-1, kata-kunci-2, ...]

## 3. Daftar Periksa Pra-Rilis
- [ ] Teks bab 1 hingga tamat lengkap tanpa jeda hilang
- [ ] Halaman hak cipta & persembahan terpasang
- [ ] Sampul depan beresolusi tinggi (minimal 300 DPI) siap
- [ ] Berkas naskah lolos uji tampilan di pembaca digital
```
