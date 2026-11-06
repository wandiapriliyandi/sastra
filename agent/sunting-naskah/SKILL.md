---
name: sunting-naskah
description: Melakukan penyuntingan naskah (novel per bab atau cerpen) mencakup kesinambungan bibel, konsistensi tokoh, lintasan khusus rasa manusia (anti-AI slop), pacing, dan kebahasaan, dengan keluaran daftar temuan serta perbaikan bedah.
---

# Skill: Sunting Naskah

## Kapan Dipakai
- Setelah draf suatu bab novel (`novel/<judul-novel>/bab/bab-[XX].md`) atau naskah cerpen (`cerpen/<judul-cerpen>.md`) selesai ditulis.
- Dijalankan per satuan kecil (per bab atau per cerpen), bukan seluruh buku sekaligus.

## Alur Kerja Langkah demi Langkah
1. **Pemeriksaan Kontinuitas & Kepatuhan Bibel**:
   - Bandingkan naskah dengan berkas di `bibel/` (tokoh, dunia, garis waktu).
   - Catat jika ada diskrepansi fisik, umur, atau lini masa.
2. **Lintasan Khusus: Pemeriksaan Rasa Manusia (Human Touch Pass)**:
   - **Pindai terukur dulu (wajib, lihat AGENTS.md §4.7)**: hitung penanda simile per kata ("laksana"/"layaknya" ≤ 5 untuk kata yang sama; total `laksana+layaknya+bagai+seolah-olah` ≤ 12) dan kata penguat ("mendadak" ≤ 4, "luar biasa" ≤ 3) per cerpen 3.000–4.500 kata. Pengulangan berpola adalah tanda mesin nomor satu dan TIDAK terlihat tanpa menghitung. Cantumkan angka hitungan di laporan sunting.
   - Pindai dan tandai bagian naskah yang berbau buatan mesin (*AI slop*):
     - Pola ritme kalimat yang seragam dan monoton.
     - Diksi klise AI (*senyum tipis terukir, bagai embun pagi, tatapan dingin menusuk*).
     - Kalimat yang terus menamai emosi tokoh (*"ia merasa sangat cemas"* bukan memperlihatkan reaksi tubuh).
     - Paragraf penutup babak yang mendadak menceramahi pembaca dengan pesan moral.
   - Perbaiki bagian bermasalah tersebut agar mengalir dinamis, memasukkan detail sensorik lokal yang tajam, dan merujuk `agent/profil-gaya.md`.
3. **Penyuntingan Tempo Narasi & Dialog (Pacing & Subtext)**:
   - Pangkas adegan basa-basi atau perdebatan yang berbelit tanpa tegangan.
   - Pastikan dialog memiliki subteks dan didukung action beats nonverbal.
4. **Pemeriksaan Kaidah Bahasa & Aksara (Copyediting)**:
   - Periksa tata letak tanda baca dialog dan ejaan baku KBBI/EYD V (*napas, mengubah, antre, risiko*).
5. **Penerapan Perbaikan Bedah**:
   - Terapkan perbaikan langsung secara bedah ke dalam berkas naskah.
   - Sajikan laporan ringkas berisi daftar temuan utama dan solusinya.
   - **Loop lolos ambang**: bila pindai terukur masih di atas ambang (AGENTS.md §4.7), perbaiki lalu HITUNG ULANG, ulangi sampai di bawah ambang — dilarang menutup suntingan dengan status "lolos" di atas ambang. Tabel temuan wajib menyertakan angka hitungan SEBELUM dan SESUDAH untuk tiap penanda yang dilanggar.

## Aturan Mutu
- **Penyuntingan Bedah (Surgical Editing)**: Dilarang menulis ulang seluruh naskah dari nol bila hanya beberapa paragraf yang bermasalah. Pertahankan suara asli naskah.
- **Pembersihan Bau Mesin**: Jangan meloloskan naskah yang masih memiliki kalimat-kalimat klise atau dialog steril buatan AI.
- **Laporan Padat & Terukur**: Jangan mengutip ulang teks panjang yang tidak diubah; sajikan daftar temuan dalam bentuk poin-poin ringkas.

## Format Keluaran
Hasil penyuntingan berupa naskah yang telah diperbarui serta laporan temuan ringkas:

```markdown
# Laporan Sunting: [Nama Berkas Naskah]

## 1. Ringkasan Eksekutif Mutu
- **Status Naskah**: [Layak / Perlu Revisi Minor / Perlu Revisi Mayor]
- **Kepatuhan Bibel**: [Konsisten / Ada Diskrepansi]
- **Uji Rasa Manusia**: [Lolos / Terdapat Perbaikan Anti-Slop]

## 2. Daftar Temuan Kunci & Solusi
| No | Kategori | Temuan di Naskah | Perbaikan yang Diterapkan |
|---|---|---|---|
| 1 | Rasa Manusia | Diksi klise AI ("senyum tipis terukir di bibirnya"). | Diganti gestur konkret ("ia mengetuk-ngetukkan jari ke meja kayu"). |
| 2 | Kontinuitas | Umur tokoh di bab tertulis 28 thn, padahal di bibel 32 thn. | Disesuaikan menjadi 32 tahun sesuai bibel/tokoh.md. |
| 3 | Ejaan / EYD | Kata "merubah" dan "nafas". | Diubah menjadi "mengubah" dan "napas". |

## 3. Catatan Tindak Lanjut untuk Bab Berikutnya
- [Catatan jika ada fakta baru yang perlu diperbarui ke bibel cerita]
```
