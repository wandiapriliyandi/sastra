# Direktori Novel

Direktori ini diperuntukkan sebagai tempat penyimpanan dan pengerjaan proyek novel sastra.

---

## 📂 Konvensi Berkas Novel

Setiap proyek novel disimpan dalam folder tersendiri: `novel/<nomor>-<judul-novel>/` (nomor dua digit sesuai urutan buat) dengan struktur baku:

```
novel/<nomor>-<judul-novel>/
├── sinopsis.md                 # Premis, logline, tema, struktur babak, dan sinopsis lengkap
├── kanon/                      # Kanon cerita per karya
│   ├── tokoh.md                # Profil watak, want/need, idiolek dialog
│   ├── dunia.md                # Latar tempat, budaya, aturan sosial, riset
│   ├── relasi.md               # Peta hubungan antartokoh
│   └── garis-waktu.md          # Urutan kronologis kejadian
├── kerangka/                   # Kerangka per bab
│   ├── bab-01.md
│   ├── bab-02.md
│   └── ...
└── bab/                        # Draf prosa bab naskah
    ├── bab-01.md
    ├── bab-02.md
    └── ...
```

---

## ⚡ Aturan Pengerjaan Novel
- Rujuk pedoman kerja di [`/home/hatch/workspace/sastra/AGENTS.md`](file:///home/hatch/workspace/sastra/AGENTS.md).
- Gunakan kumpulan keahlian di direktori [`agent/`](file:///home/hatch/workspace/sastra/agent/README.md) (`rencana-novel`, `kanon-cerita`, `kerangka-bab`, `tulis-bab`, `sunting-naskah`, `dialog`, `pembaca-beta`, dll.).
- Terapkan disiplin [`agent/efisiensi-token`](file:///home/hatch/workspace/sastra/agent/efisiensi-token/SKILL.md): tulis bertahap bab per bab dengan konteks minimal yang cukup.
