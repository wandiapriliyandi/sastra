---
name: tulis-bab
description: Menulis draf prosa satu bab novel secara bertahap mengikuti kerangka bab, bibel cerita, dan sinopsis; patuh pada kanon bibel, gaya bahasa konsisten, berorientasi Show Don't Tell, dan lolos uji rasa manusia.
---

# Skill: Tulis Bab

## Kapan Dipakai
- Saat menulis draf isi bab novel tertentu (dikerjakan bab per bab, bukan maraton seluruh novel sekaligus).
- Prasyarat: `novel/<judul-novel>/sinopsis.md`, berkas relevan di `bibel/`, dan `kerangka/bab-[XX].md` sudah siap.

> **Aturan Sasaran & Posisi Karya (Wajib AGENTS.md)**: 
> - Sasaran: **Remaja umum (13–18 tahun)**.
> - Posisi Karya: Di permukaan tampil sebagai fiksi remaja umum tanpa label "fiksi islami/santri"; dunia pesantren hadir sebagai tekstur hidup tanpa ceramah, nilai muncul dari pilihan tokoh (remaja umum terhanyut, santri mengenali dunianya sendiri secara diam-diam).

## Alur Kerja Langkah demi Langkah
1. **Pemuatan Konteks Minimal (Hemat Token)**:
   - Baca ringkasan `sinopsis.md` (hanya bagian babak yang relevan dan konfirmasi sasaran pembaca).
   - Baca berkas `kerangka/bab-[XX].md` untuk bab yang akan ditulis.
   - Buka entri tokoh dan latar di `bibel/` HANYA untuk tokoh dan latar yang muncul di bab tersebut.
   - Baca preferensi suara di `agent/profil-gaya.md` jika tersedia.
2. **Eksekusi Penulisan Prosa**:
   - Mulai dengan *hook* kalimat pembuka sesuai kerangka.
   - Kembangkan urutan adegan dengan aksi nyata, dialog hidup, dan suasana indrawi konkret.
   - Terapkan *Show Don't Tell*: perlihatkan kegelisahan batin lewat gestur fisik dan pilihan tindakan tokoh.
3. **Penyelarasan Fakta & Posisi Karya**:
   - Pastikan fakta 100% konsisten dengan `bibel/`.
   - Hindari kesalehan performatif; biarkan tokoh santri atau remaja memiliki kerapuhan, keraguan, dan perjuangan batin manusiawi.
4. **Pemeriksaan Rasa Manusia (Langkah Wajib Akhir)**:
   - Periksa ritme kalimat: variasikan panjang-pendek; hilangkan irama monoton mesin.
   - Hadirkan detail sensorik spesifik latar Nusantara (suasana asrama, aroma hujan di lapangan, derit pintu).
   - Pastikan dialog wajar dengan selaan dan partikel alami (*kok, sih, lah, dong*), tanpa terkesan kaku seperti khotbah.
   - Bersihkan metafora klise AI dan pastikan cerita tetap terbuka bagi pembaca luar pesantren.
   - **Pindai terukur (AGENTS.md §4.7, proporsional per bab)**: hitung penanda simile & penguat sebelum menyatakan lolos — per bab: satu penanda simile yang sama ≤ 3, total penanda simile ≤ 8, "mendadak" ≤ 3, "luar biasa" ≤ 2; pemeriksa adalah agen/sesi berbeda dari penulis bab, dan angka hitungan dilaporkan. Bab dari novel yang akan dirilis juga tunduk pada Gerbang Nilai Rilis §4.8 (≥ 85/100 per bab dinilai beta independen).
5. **Penyimpanan Berkas**:
   - Simpan naskah draf di: `novel/<judul-novel>/bab/bab-[XX].md` (contoh: `bab-01.md`).

## Aturan Mutu
- **Kepatuhan Kanon & Posisi Karya**: Selaras dengan bibel, aman bagi remaja, dan bernilai universal.
- **Konsistensi Sudut Pandang**: Jaga sudut pandang tetap di kepala tokoh POV yang ditentukan di kerangka; dilarang *head-hopping*.
- **Rasa Manusia Hidup**: Draf berdegup emosi organik, bebas dari kekakuan bahasa mesin atau ceramah moral.

## Format Keluaran
Berkas disimpan di: `novel/<judul-novel>/bab/bab-[XX].md`

```markdown
# Bab [Nomor Bab]: [Judul Bab Jika Ada]

[Teks prosa bab lengkap, ditulis dalam paragraf-paragraf mengalir, memuat aksi, dialog ber-subteks, detail indrawi bernyawa, lolos uji rasa manusia, dan memegang teguh posisi karya universal.]
```
