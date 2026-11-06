# Ekosistem Penulisan Sastra Fiksi

Ruang kerja terstruktur untuk kepenulisan sastra fiksi berbahasa Indonesia di `/home/hatch/workspace/sastra`.

---

## 🏛 Struktur Repositori

```
/home/hatch/workspace/sastra/
├── AGENTS.md                          # Aturan wajib: sasaran pembaca, posisi karya universal, efisiensi token, & rasa manusia
├── README.md                          # Panduan induk ekosistem
├── INDEKS_KARYA.md                    # Indeks pelacakan karya (dikelola oleh skill kelola-karya)
├── agent/                             # Pustaka Keahlian Menulis Fiksi (Agent Skills)
│   ├── README.md                      # Indeks 19 skill & konvensi berkas
│   ├── rencana-novel/SKILL.md         # Premis, logline, tema, struktur babak, sinopsis
│   ├── kanon-cerita/SKILL.md          # Kanon cerita: dunia, tokoh, relasi, garis waktu
│   ├── kerangka-bab/SKILL.md          # Kerangka per bab: tujuan, konflik, adegan, pancingan
│   ├── tulis-bab/SKILL.md             # Draf prosa bab patuh kanon & uji rasa manusia
│   ├── tulis-cerpen/SKILL.md          # Alur lengkap cerpen dari ide sampai draf jadi
│   ├── sunting-naskah/SKILL.md        # Penyuntingan kontinuitas, rasa manusia, pacing, EYD
│   ├── ide-cerita/SKILL.md            # Bank ide, what-if, potongan adegan, panen ide
│   ├── pembaca-beta/SKILL.md          # Evaluasi kacamata pembaca pertama (laporan pembaca)
│   ├── dialog/SKILL.md                # Percakapan berbobot, subteks, idiolek wicara
│   ├── riset-latar/SKILL.md           # Riset cepat secukupnya untuk latar/profesi/zaman
│   ├── judul-dan-sampul/SKILL.md      # Opsi judul + rasionalisasi, blurb sampul belakang
│   ├── efisiensi-token/SKILL.md       # Disiplin hemat token (per potongan, minimal konteks)
│   ├── gaya-penulis/SKILL.md          # Pemetaan profil gaya tulisan pemilik karya
│   ├── kelola-karya/SKILL.md          # Manajemen koleksi & indeks status karya
│   ├── serialisasi/SKILL.md           # Serial daring per episode & retensi cliffhanger
│   ├── puisi/SKILL.md                 # Penulisan & revisi larik puisi (citraan, rima, bunyi)
│   ├── adaptasi-format/SKILL.md       # Alih format lintas bentuk (cerpen <-> novel <-> naskah)
│   ├── penerbitan/SKILL.md            # Alur swaterbit, metadata, daftar periksa pra-rilis
│   └── sampul-dan-ilustrasi/SKILL.md  # Brief visual sampul & ilustrasi tokoh/latar
│
├── novel/                             # Kumpulan & Manajemen Proyek Novel
│   └── README.md                      # Panduan konvensi naskah novel (novel/<judul>/...)
│
└── cerpen/                            # Kumpulan & Manajemen Naskah Cerpen
    ├── README.md                      # Panduan konvensi naskah cerpen
    └── <nomor>-<judul-cerpen>/        # Subfolder per judul cerpen, bernomor urut buat (<nomor>-<judul>.md + kanon-mini.md)
```

---

## 🎯 Empat Pilar Mutu Utama
Semua agen wajib mematuhi pedoman di [`AGENTS.md`](file:///home/hatch/workspace/sastra/AGENTS.md):
1. **Sasaran Pembaca Bawaan (Remaja 13–18 Tahun)**: Berakar pada dinamika sekolah/madrasah/pesantren, persahabatan, keluarga, cita-cita, dan pencarian jati diri.
2. **Posisi Karya (Universalitas vs Santri)**: Menjangkau anak pesantren secara nyata, tetapi **tidak boleh terlihat dibuat "untuk santri"**. Nilai-nilai adab dan ketulusan dihadirkan secara tersirat (*subtle*), kemasan terbuka dan memikat bagi seluruh remaja umum tanpa berbau dakwah atau eksklusif sektarian.
3. **Disiplin Efisiensi Token**: Membaca naskah per potongan, menulis bertahap dengan konteks minimal yang cukup, merawat kanon dalam butir-butir poin, dan menyunting bedah setempat.
4. **Aturan Rasa Manusia**: Ritme kalimat dinamis bervariasi, detail inderawi spesifik lokal Nusantara, dialog wajar berperilaku manusia, membasmi klise AI, serta menyisakan ruang tafsir bagi pembaca.
