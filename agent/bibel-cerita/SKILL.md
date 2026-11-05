---
name: bibel-cerita
description: Membangun dan merawat bibel cerita (story bible) per novel yang memuat dunia/latar, profil & psikologi tokoh, relasi antartokoh, serta garis waktu kejadian.
---

# Skill: Bibel Cerita

## Kapan Dipakai
- Segera setelah `rencana-novel` selesai sebelum menulis bab apa pun.
- Selama proses penulisan untuk merawat kontinuitas, memperbarui perkembangan tokoh, dan menambahkan fakta baru yang muncul di naskah.

## Alur Kerja Langkah demi Langkah
1. **Pemetaan Tokoh (`bibel/tokoh.md`)**:
   - Rinci profil tokoh utama dan pendukung penting:
     - Profil dasar: nama, umur, fisik khas, kebiasaan.
     - Watak batin: *Want* (keinginan luar), *Need* (kebutuhan batin), *The Lie* (kebohongan diri), *The Wound* (trauma masa lalu).
     - Sidik suara dialog (idiolek): kosakata khas, tempo bicara, register bahasa.
     - Busur perubahan (*arc*): kondisi awal vs kondisi akhir.
2. **Pembangunan Dunia & Latar (`bibel/dunia.md`)**:
   - Geografi fisik, kondisi iklim/musim, aturan sosial, norma/tabu adat, dan suasana sensorik khas (aroma, bebunyian, lanskap).
3. **Peta Relasi Antartokoh (`bibel/relasi.md`)**:
   - Sumber tegangan/friksi, aliansi, rahasia bersama, dan dinamika kuasa antartokoh.
4. **Garis Waktu Kejadian (`bibel/garis-waktu.md`)**:
   - Kronologi peristiwa kunci sebelum cerita dimulai (masa lalu) dan peristiwa selama rentang waktu novel berlangsung.
5. **Perawatan Berjalan**:
   - Jika saat menulis bab ditemukan fakta baru (misal: warna mobil paman, tanggal lahir tokoh), catat segera ke bibel.

## Aturan Mutu
- **Format Poin Ringkas (Bullet Points)**: Hindari narasi paragraf panjang di bibel. Gunakan format poin-poin terstruktur agar hemat token saat dibaca ulang per kebutuhan.
- **Bebas Kontradiksi**: Fakta dalam bibel adalah hukum kanon cerita. Jangan ada pertentangan antara satu berkas bibel dengan berkas lainnya.
- **Karakterisasi Fungsional**: Cantumkan detail yang memiliki pengaruh pada pilihan dan tindakan tokoh di cerita, bukan ensiklopedia hampa.

## Format Keluaran
Subfolder berkas di: `novel/<judul-novel>/bibel/`

### 1. `novel/<judul-novel>/bibel/tokoh.md`
```markdown
# Bibel Tokoh: [Judul Novel]

## [Nama Tokoh Utama]
- **Peran**: Protagonis
- **Usia & Ciri Fisik**: 
- **The Want (Tujuan Sadar)**: 
- **The Need (Kebutuhan Batin)**: 
- **The Lie & The Wound**: 
- **Gaya Bicara / Suara Dialog**: 
- **Busur Perubahan**: Dari [X] menjadi [Y].
```

### 2. `novel/<judul-novel>/bibel/dunia.md`
```markdown
# Bibel Dunia & Latar: [Judul Novel]

## Lokasi Utama
- **Nama Tempat**: 
- **Karakteristik Fisik**: 
- **Atmosfer Indrawi**: 
- **Aturan Sosial / Larangan**: 
```

### 3. `novel/<judul-novel>/bibel/garis-waktu.md`
```markdown
# Garis Waktu: [Judul Novel]

- **Masa Lalu (Pramula)**: 
- **Hari 1**: 
- **Hari 2**: 
```
