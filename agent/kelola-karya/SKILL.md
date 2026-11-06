---
name: kelola-karya
description: Manajemen inventaris dan koleksi karya sastra: mencatat status dan sasaran pembaca tiap karya dalam indeks terpusat, menjaga kerapian folder novel/ dan cerpen/, serta merangkum kemajuan penulisan.
---

# Skill: Kelola Karya

## Kapan Dipakai
- Saat menambah proyek karya baru, memperbarui progres bab, atau mengubah status karya (dari ide ke draf/revisi/terbit).
- Untuk melakukan audit kerapian berkas dan struktur folder di repositori proyek sastra.
- Untuk mencatat dan memverifikasi sasaran pembaca tiap karya (bawaan: Remaja 13–18 tahun).

> **Aturan Sasaran & Posisi Karya (Wajib AGENTS.md)**: 
> - Pastikan setiap entri karya di `INDEKS_KARYA.md` memuat kolom sasaran pembaca (default: Remaja 13–18 tahun).
> - Posisi karya dijaga: tidak boleh ada karya yang diberi label/kategori "cerita islami" atau "khusus santri"; semua dicatat sebagai fiksi remaja umum dengan catatan latar tekstual bila relevan.

## Alur Kerja Langkah demi Langkah
1. **Pemindaian & Audit Struktur Folder**:
   - Periksa subfolder di `novel/` apakah mematuhi konvensi: `sinopsis.md`, `bibel/`, `kerangka/`, dan `bab/`.
   - Periksa berkas di `cerpen/` apakah berformat subfolder per judul: `cerpen/<nomor>-<judul>/<nomor>-<judul>.md` (nomor dua digit sesuai urutan buat).
2. **Pembaruan Indeks Koleksi Karya (`INDEKS_KARYA.md`)**:
   - Catat status dan sasaran pembaca tiap karya:
     - Sasaran Pembaca: `Remaja (13–18)` (default) atau sasaran khusus yang ditentukan pemilik.
     - Status: `Ide`, `Draf`, `Revisi`, `Jadi`, atau `Terbit`.
3. **Penyusunan Rangkuman Kemajuan (Writing Progress)**:
   - Hitung total bab/kata yang telah diselesaikan.
   - Identifikasi proyek yang macet (*stalled*) atau butuh perhatian tindak lanjut.
4. **Penyimpanan Berkas**:
   - Simpan indeks terpusat di berkas root: `INDEKS_KARYA.md`.

## Aturan Mutu
- **Data Akurat & Terkini**: Selalu perbarui status, angka progres, dan sasaran pembaca setiap kali ada perubahan.
- **Kepatuhan Konvensi Berkas**: Segera beri peringatan jika ada berkas yang diletakkan di luar struktur baku.
- **Ringkas & Murah Token**: Gunakan format tabel padat.

## Format Keluaran
Berkas disimpan di: `INDEKS_KARYA.md`

```markdown
# Indeks Koleksi Karya Sastra

## 1. Daftar Proyek Novel
| No | Judul Novel | Genre | Sasaran Pembaca | Status | Progres Terkini | Target Kata | Catatan |
|---|---|---|---|---|---|---|---|
| 1 | [Judul Novel] | [Genre] | Remaja (13–18) | [Draf/Jadi] | Bab [X] dari [Y] | [Target] | [Pembaruan] |

## 2. Daftar Naskah Cerpen
| No | Judul Cerpen | Genre / Tema | Sasaran Pembaca | Status | Target Media | Jumlah Kata |
|---|---|---|---|---|---|---|
| 1 | [Judul Cerpen] | [Tema] | Remaja (13–18) | [Draf/Jadi] | [Media] | [Kata] |

## 3. Rangkuman Kemajuan & Prioritas Kerja
- **Proyek Fokus Saat Ini**: 
- **Target Minggu Ini**: 
```
