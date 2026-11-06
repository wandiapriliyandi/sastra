# Pustaka Keahlian Menulis Fiksi (Agent Skills)

Pusat keahlian menulis fiksi sastra berbahasa Indonesia untuk proyek kepenulisan di `/home/hatch/workspace/sastra`. Setiap subfolder memuat panduan praktis mandiri (`SKILL.md`) yang siap diacu oleh agen AI maupun penulis.

> **EMPAT PANDUAN MUTU UTAMA**:
> 1. **Sasaran Pembaca**: Bawaan (*default*) seluruh karya ditujukan untuk pembaca **Remaja (usia 13–18 tahun)** dengan tema sekolah/pesantren, persahabatan, keluarga, cita-cita, dan pencarian jati diri, kecuali ditentukan lain oleh pemilik karya.
> 2. **Posisi Karya (Universal vs Santri)**: Remaja yang nyata-nyata dijangkau adalah **anak pesantren (santri)**, TETAPI karya **TIDAK BOLEH terlihat dibuat "untuk santri"**; nilai luhur hadir secara tersirat (*subtle*), kemasan inklusif dan universal bagi seluruh remaja Indonesia tanpa berbau dakwah/sektarian.
> 3. **Rasa Manusia**: Seluruh proses penulisan dan penyuntingan naskah wajib mematuhi [Aturan Rasa Manusia di AGENTS.md](../AGENTS.md) agar karya bernapas hidup dan tidak berbau buatan mesin/AI.
> 4. **Efisiensi Token**: Seluruh skill di bawah ini wajib tunduk dan mematuhi aturan kerja hemat token pada skill [`efisiensi-token`](./efisiensi-token/SKILL.md).

---

## 📚 Indeks Kumpulan Skill Menulis Fiksi (20 Skill)

| No | Nama Skill | Direktori | Satu Baris Fungsi |
|---|---|---|---|
| 1 | **rencana-novel** | [`agent/rencana-novel/`](./rencana-novel/SKILL.md) | Menyusun premis, logline, tema, struktur besar (babak), dan sinopsis sebuah novel baru (default: remaja, universal). |
| 2 | **kanon-cerita** | [`agent/kanon-cerita/`](./kanon-cerita/SKILL.md) | Membangun dan merawat kanon cerita per novel: dunia/latar, tokoh, relasi antartokoh, dan garis waktu kejadian. |
| 3 | **kerangka-bab** | [`agent/kerangka-bab/`](./kerangka-bab/SKILL.md) | Membuat kerangka operasional per bab: tujuan bab, konflik, urutan adegan, sudut pandang, dan pancingan ke bab berikutnya. |
| 4 | **tulis-bab** | [`agent/tulis-bab/`](./tulis-bab/SKILL.md) | Menulis draf prosa satu bab mengikuti kerangka + kanon + sinopsis secara taat asas kanon, *Show Don't Tell*, dan lolos uji rasa manusia. |
| 5 | **tulis-cerpen** | [`agent/tulis-cerpen/`](./tulis-cerpen/SKILL.md) | Menjalankan alur lengkap cerpen dari ide sampai naskah jadi (premis, struktur ringkas, draf, dan poles akhir) dalam satu berkas utuh. |
| 6 | **sunting-naskah** | [`agent/sunting-naskah/`](./sunting-naskah/SKILL.md) | Menyunting naskah (per bab novel atau cerpen) mencakup kontinuitas kanon, lintasan khusus rasa manusia, pacing, dan kebahasaan menjadi daftar temuan serta perbaikan. |
| 7 | **ide-cerita** | [`agent/ide-cerita/`](./ide-cerita/SKILL.md) | Mengelola bank ide: menangkap premis, *"bagaimana jika"*, potongan adegan, dan pengamatan menjadi catatan terstruktur (daya pikat ganda santri-umum). |
| 8 | **pembaca-beta** | [`agent/pembaca-beta/`](./pembaca-beta/SKILL.md) | Membaca naskah dari kacamata pembaca pertama: kesan umum, bagian yang membosankan/melambat, pertanyaan menggantung, dan vitalitas tokoh dalam bentuk laporan pembaca. |
| 9 | **dialog** | [`agent/dialog/`](./dialog/SKILL.md) | Menggarap percakapan: membedakan suara tiap tokoh sesuai kanon cerita, subteks, ritme, bebas ceramah/dakwah kaku, dan alami. |
| 10 | **riset-latar** | [`agent/riset-latar/`](./riset-latar/SKILL.md) | Riset cepat dan terverifikasi secukupnya untuk latar tempat, profesi, zaman, istilah, dan adat untuk diringkas dan dimasukkan ke kanon cerita karya terkait. |
| 11 | **judul-dan-sampul** | [`agent/judul-dan-sampul/`](./judul-dan-sampul/SKILL.md) | Merumuskan judul, blurb, dan sinopsis pendek/sampul untuk karya yang sudah jadi (kemasan menarik universal, bebas label eksklusif). |
| 12 | **efisiensi-token** | [`agent/efisiensi-token/`](./efisiensi-token/SKILL.md) | Aturan kerja hemat token untuk fiksi: baca berkas per potongan, kanon & kerangka poin ringkas, tulis bertahap per satuan kecil dengan konteks minimal cukup, sunting bedah setempat, laporan padat, dan ringkasan berjalan. |
| 13 | **gaya-penulis** | [`agent/gaya-penulis/`](./gaya-penulis/SKILL.md) | Menangkap ciri khas tulisan pemilik dari contoh karyanya (diksi, ritme kalimat, dialog, POV) menjadi profil gaya acuan agar draf berbunyi seperti pemilik, bukan generik. |
| 14 | **kelola-karya** | [`agent/kelola-karya/`](./kelola-karya/SKILL.md) | Manajemen koleksi project: mencatat status dan sasaran pembaca tiap karya dalam satu berkas indeks karya, menjaga kerapian folder novel/ dan cerpen/, dan merangkum kemajuan. |
| 15 | **serialisasi** | [`agent/serialisasi/`](./serialisasi/SKILL.md) | Menulis serial per episode untuk platform baca daring: ritme cliffhanger, rekap antar-episode, pengelolaan konsistensi untuk pembaca berkala, dan penyesuaian panjang episode. |
| 16 | **puisi** | [`agent/puisi/`](./puisi/SKILL.md) | Menggarap puisi: diksi, citraan, bunyi/rima, bentuk (bebas maupun terikat), dan revisi per larik (resonansi rasa remaja). |
| 17 | **adaptasi-format** | [`agent/adaptasi-format/`](./adaptasi-format/SKILL.md) | Mengalihformatkan karya: cerpen menjadi novel, novel menjadi sinopsis/naskah, dan sebaliknya, dengan menjaga inti cerita dan tokoh. |
| 18 | **penerbitan** | [`agent/penerbitan/`](./penerbitan/SKILL.md) | Alur menerbitkan karya sendiri: naskah final, penyiapan berkas terbit, keterangan/metadata karya, daftar periksa prarilis, sampai karya dirilis ke platform pilihan. |
| 19 | **sampul-dan-ilustrasi** | [`agent/sampul-dan-ilustrasi/`](./sampul-dan-ilustrasi/SKILL.md) | Brief visual untuk sampul karya dan ilustrasi tokoh/latar: merumuskan arahan gambar yang konsisten dengan isi dan kanon cerita untuk ilustrator atau generator gambar. |
| 20 | **karakter-dan-psikologi** | [`agent/karakter-dan-psikologi/`](./karakter-dan-psikologi/SKILL.md) | Merancang tokoh dengan variabel pembentukan berlapis (MBTI, golongan darah, temperamen, keluarga, lingkungan, pendidikan, pertemanan, pengalaman formatif) menjadi kartu tokoh yang hidup dan kontradiktif; metode perancangan pasangan kanon-cerita, plus uji diagnosis tokoh datar saat revisi. |

---

## 📂 Konvensi Berkas Proyek

Setiap karya fiksi wajib mengikuti konvensi penamaan dan penempatan berkas berikut:

### 1. Format Karya Novel
Disimpan dalam subdirektori per judul di bawah `novel/`:
```
novel/<nomor>-<judul-novel>/
├── sinopsis.md                 # Premis, logline, tema, struktur babak, sasaran pembaca, dan sinopsis lengkap
├── kanon/                      # Folder kanon cerita (story bible)
│   ├── tokoh.md                # Profil, watak, idiolek wicara, busur karakter
│   ├── dunia.md                # Latar geografis, iklim, budaya, detail sensorik
│   ├── relasi.md               # Dinamika kuasa & friksi antartokoh
│   └── garis-waktu.md          # Kronologi kejadian pracerita & berjalannya alur
├── kerangka/                   # Folder kerangka operasional bab
│   ├── bab-01.md
│   ├── bab-02.md
│   └── ...
└── bab/                        # Folder draf naskah prosa bab
    ├── bab-01.md
    ├── bab-02.md
    └── ...
```

### 2. Format Karya Cerpen
Disimpan dalam subdirektori per judul di bawah `cerpen/`:
```
cerpen/<nomor>-<judul-cerpen>/
├── <nomor>-<judul-cerpen>.md   # Naskah prosa cerpen utuh (metadata + draf naskah)
└── kanon-mini.md               # Catatan tokoh, latar, premis, dan tema (bila dibuat)
```
