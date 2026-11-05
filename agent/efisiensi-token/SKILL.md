---
name: efisiensi-token
description: Pedoman dan tata kerja disiplin konsumsi token untuk proyek kepenulisan fiksi; membatasi konteks, membaca dan menulis bertahap per satuan kecil, serta menjaga anggaran memori agen tetap ramping.
---

# Skill: Efisiensi Token dalam Proyek Sastra

## Kapan Dipakai
- **Wajib dipatuhi setiap saat** oleh seluruh agen dan asisten yang bekerja di proyek sastra ini, mencakup proses perencanaan, perancangan bibel, penulisan prosa, hingga penyuntingan.

## Prinsip Pokok Disiplin Token Fiksi

1. **Pembacaan Selektif (Per Potongan / Chunking)**:
   - Baca berkas per potongan: per bab, per adegan, atau per rentang baris/judul bagian.
   - **DILARANG** memuat seluruh naskah novel (puluhan ribu kata) atau seluruh berkas bibel jika yang dibutuhkan hanya satu tokoh atau satu adegan tertentu.
   - Gunakan pencarian kata kunci atau `grep` untuk melompat langsung ke bagian yang relevan.

2. **Bibel & Kerangka Ringkas (Poin-Poin)**:
   - Tulis bibel cerita (`bibel/*.md`) dan kerangka bab (`kerangka/*.md`) dalam bentuk butir-butir poin padat (*bullet points*), bukan narasi paragraf panjang.
   - Format poin jauh lebih hemat token saat dibaca ulang berulang kali dan mempermudah pencarian fakta.

3. **Penulisan Bertahap Bersatuan Kecil (Minimal Context)**:
   - Tulis naskah secara bertahap: **satu bab atau satu adegan per giliran**.
   - Muat hanya konteks minimal yang cukup:
     - 1 paragraf sinopsis babak terkait dari `sinopsis.md`.
     - Potongan entri tokoh/latar yang relevan dari `bibel/`.
     - Berkas kerangka bab bersangkutan (`kerangka/bab-[XX].md`).
   - Jangan menyertakan bab-bab sebelumnya ke dalam jendela konteks kecuali benar-benar diperlukan untuk kontinuitas langsung kalimat pembuka.

4. **Penyuntingan Bedah Setempat (Surgical Editing)**:
   - Saat merevisi atau menyunting naskah, lakukan perbaikan bedah per adegan atau per paragraf spesifik.
   - **DILARANG** menulis ulang seluruh bab sepanjang ribuan kata hanya untuk memperbaiki dua kalimat dialog atau mengoreksi salah eja tanda baca.

5. **Keluaran Laporan Padat Tanpa Duplikasi Teks**:
   - Sajikan laporan kerja, laporan sunting, atau evaluasi pembaca secara ringkas dan padat.
   - **JANGAN** mengutip ulang paragraf teks panjang yang tidak mengalami perubahan. Cukup sebutkan nomor bab, nomor paragraf, atau kutipan frasa pendeknya saja.

6. **Ringkasan Berjalan (Running Summary) untuk Naskah Panjang**:
   - Jika proyek novel telah mencapai banyak bab, rawat berkas ringkasan berjalan di mana setiap bab dirangkum maksimal 2–3 baris fakta kunci.
   - Saat menulis bab 15, agen membaca ringkasan berjalan Bab 1–14, bukan membaca naskah penuh Bab 1–14.

## Aturan Mutu & Audit Token
- [ ] Apakah saya hanya membaca berkas yang langsung berkaitan dengan bab/tugas ini?
- [ ] Apakah bibel ditulis dalam poin-poin hemat kata?
- [ ] Apakah draf naskah dikerjakan satu satuan bab per sesi?
- [ ] Apakah revisi dilakukan secara bedah lokal tanpa mencetak ulang seluruh bab?
- [ ] Apakah tanggapan saya bebas dari kutipan teks raksasa yang mubazir?
