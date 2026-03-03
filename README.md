# Seishun wa Sankakukei no Loop

> —Karena aku lebih memperhatikannya daripada siapa pun, aku jadi tahu.Kalau dia sedang jatuh cinta sekarang.Dan orang yang dia sukai itu adalah sahabatku sendiri, teman masa kecil kami berdua.Sang protagonis, Tsubaki, memutuskan untuk mengubur perasaannya dan membantu cinta sang gadis terwujud.Berkat usahanya juga, dua teman masa kecil yang selalu bersama itu akhirnya resmi menjadi pasangan.Setelah menyaksikan momen itu, Tsubaki menjalani malam tanpa tidur sambil menahan perasaan ingin berteriak—dan ketika dia terbangun berikutnya—Dia kembali mengubur perasaannya…

---

## Info

| | |
|---|---|
| Judul | Seishun wa Sankakukei no Loop |
| Judul Alternatif | 青春は三角形のループ |
| Author | Yasuzumi Kei |
| Artist | Mito |
| Tipe | Manga (Hitam Putih) |
| Genre | Drama · Shounen · Fantasy · Comedy · Romance · School Life · Slice of Life |

## Link

- [MangaDex](https://mangadex.org/title/e6d70578-d6b2-4c60-a2f4-7ab16e515480/seishun-wa-sankakukei-no-loop)
- [Raw](https://comic-walker.com/detail/KC_006586_S)

---

## Struktur

```
SankakukeinoLoop/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)