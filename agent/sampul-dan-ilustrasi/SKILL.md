---
name: sampul-dan-ilustrasi
description: Merumuskan brief visual terstruktur untuk perancangan sampul buku (cover art) dan ilustrasi tokoh/adegan/latar; memastikan konsistensi kanon fisik dengan isi naskah dan bibel cerita untuk panduan ilustrator atau generator gambar.
---

# Skill: Sampul dan Ilustrasi (Visual Brief)

## Kapan Dipakai
- Saat menyiapkan arahan desain sampul depan (*cover design*) untuk naskah novel atau cerpen.
- Saat membutuhkan ilustrasi adegan kunci, sketsa peta dunia, atau potret tokoh untuk disertakan dalam buku atau materi promosi.

## Alur Kerja Langkah demi Langkah
1. **Penyelarasan dengan Kanon Bibel**:
   - Buka `bibel/tokoh.md` untuk rincian fisik tokoh (bentuk wajah, warna kulit, pakaian khas, bekas luka).
   - Buka `bibel/dunia.md` untuk arsitektur, lanskap alam, kondisi cuaca, dan nuansa pencahayaan.
2. **Pemilihan Momen / Simbol Sentral**:
   - Tentukan apakah ilustrasi bersifat:
     - **Figuratif / Karakter**: Menampilkan tokoh sentral dalam gestur emosi kuat.
     - **Simbolis / Tipografis**: Menyorot satu objek metaforis dengan olahan tipografi sastra yang kuat.
     - **Lanskap / Adegan (Scenic)**: Menangkap lanskap ruang dan atmosfer fajar/senja/malam yang mencekam.
3. **Penyusunan Parameter Brief Visual**:
   - **Komposisi & Tata Letak**: Penempatan judul, nama penulis, dan area fokus gambar (*focal point*).
   - **Palet Warna & Pencahayaan**: Gradasi nada (hangat/dingin), rasio kontras, dan mood emosi visual.
   - **Gaya Seni (Art Style)**: Realisme klasik, lukisan cat minyak bernuansa lokal, sketsa pensil, atau minimalisme sastra modern.
4. **Penyusunan Teks Prompt / Brief Eksekusi**:
   - Rangkum brief deskriptif berbahasa Indonesia untuk ilustrator manusia, disertai prompt terjemahan terstruktur jika menggunakan generator gambar.

## Aturan Mutu
- **Ketaatan Fisik Kanon**: Ilustrasi dilarang menggambarkan detail yang bertolak belakang dengan fakta naskah (misal: tokoh berambut lurus di naskah tetapi digambar keriting).
- **Nuansa Sastra Bernyawa**: Hindari gambaran klise fantasi generik barat jika naskah berlatar lokal Nusantara; utamakan keaslian tekstur lokal (kain batik, rumah panggung, kabut hutan tropis, perahu cadik).
- **Ramping & Berorientasi Aksi**: Format brief harus ringkas dan langsung bisa diterjemahkan oleh perancang visual.

## Format Keluaran
Disimpan di folder karya: `novel/<judul-novel>/brief-sampul.md` atau `cerpen/brief-[judul].md`

```markdown
# Brief Visual Sampul / Ilustrasi: [Judul Karya]

## 1. Konsep & Mood Visual
- **Tipe Visual**: [Sampul Buku / Potret Tokoh / Adegan Kunci]
- **Suasana Emosional (Mood)**: [Sunyi, Mencekam, Nostalgik, Megah]
- **Palet Warna Utama**: [Misal: Cokelat tanah, hijau lumut basah, aksen jingga fajar]
- **Gaya Artistik**: [Realisme sastra / Ilustrasi cat minyak / Sketsa liris]

## 2. Rincian Elemen Gambar
- **Fokus Utama (Focal Point)**: [Deskripsi objek/tokoh sentral dan gestur fisiknya]
- **Latar Belakang (Background)**: [Lanskap tempat, cuaca, dan pencahayaan]
- **Detail Tekstur Penting**: [Pakaian adat/lokal, debu jalanan, asap tembakau]

## 3. Tata Letak Tipografi (Khusus Sampul)
- **Posisi Judul**: [Atas / Tengah / Bawah]
- **Penempatan Nama Penulis**: 
- **Area Kosong (Negative Space)**: [Area yang harus bersih untuk teks]

## 4. Prompt Generator Gambar (Bila Diperlukan)
`[Prompt deskriptif terstruktur dalam bahasa Inggris teknis untuk generator visual]`
```
