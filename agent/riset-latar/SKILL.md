---
name: riset-latar
description: Menjalankan riset cepat, presisi, dan terverifikasi secukupnya mengenai latar geografi, profesi, era/zaman, istilah teknis, dan adat istiadat; meringkas hasil temuan untuk diintegrasikan ke kanon cerita karya terkait.
---

# Skill: Riset Latar

## Kapan Dipakai
- Sebelum atau saat menulis cerita yang membutuhkan akurasi teknis (profesi kedokteran, pelaut, forensik, jurnalis), fiksi berlatar sejarah (*historical fiction*), atau daerah dengan kekhasan kultural spesifik.
- Digunakan saat penulis membutuhkan detail autentik tanpa tergelincir ke dalam lubang riset berlebihan (*research rabbit hole*).

## Alur Kerja Langkah demi Langkah
1. **Identifikasi Kebutuhan Spesifik Cerita**:
   - Tentukan lingkup yang benar-benar dibutuhkan adegan: istilah teknis, rutinitas pekerjaan harian, perabotan khas era tertentu, bau/suhu lingkungan, atau pantangan adat.
2. **Pengumpulan & Verifikasi Fakta Singkat**:
   - Prioritaskan fakta yang dapat diserap oleh indera (apa yang dilihat, disentuh, didengar tokoh).
   - Verifikasi keakuratan istilah atau kronologi sejarah.
3. **Penyaringan & Ekstraksi Inti**:
   - Buang 80% materi ensiklopedis teoritis.
   - Ambil 20% fakta konkret yang langsung bersentuhan dengan emosi atau tindakan fisik tokoh.
4. **Integrasi ke Kanon Cerita**:
   - Catat intisari ke dalam berkas `novel/<judul-novel>/kanon/dunia.md` atau `kanon/riset-[topik].md`.

## Aturan Mutu
- **Riset secukupnya (Just-Enough Research)**: Berhenti meneliti segera setelah detail yang dibutuhkan untuk membangun adegan yang meyakinkan terkumpul. Penulis fiksi bukan sedang menulis tesis ilmiah.
- **Fokus Detail Sensorik**: Cari detail kecil yang meyakinkan (misal: sensasi bau formalin pada jas dokter forensik, bunyi jentikan tuas mesin tik era 1970-an, atau tata cara penyajian teh di ranah Minang).
- **Format Poin Padat**: Seluruh hasil riset wajib disusun dalam poin-poin ringkas agar tidak membebani jendela konteks token saat dibaca ulang.

## Format Keluaran
Disimpan di: `novel/<judul-novel>/kanon/dunia.md` atau sub-bagian riset karya terkait.

```markdown
## Catatan Riset: [Topik / Profesi / Lokasi / Era]

### 1. Terminologi & Kosakata Otentik
- **[Istilah 1]**: [Makna praktis dalam percakapan sehari-hari]
- **[Istilah 2]**: [Konteks pemakaian]

### 2. Rutinitas & Detail Sensorik
- **Aroma Khas Lingkungan**: 
- **Peralatan / Objek Fisik Nyata**: 
- **Tekanan Mental & Kebiasaan Khusus Pelaku**: 

### 3. Tabu & Kesalahan Fatal Pemula (Anakronisme)
- [Hindari penggunaan istilah/alat X karena belum ada pada masa itu atau tidak lazim dalam profesi ini.]
```
