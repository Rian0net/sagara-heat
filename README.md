# Sagara Heat — Isle of Vice

Game open-world crime 3D bergaya GTA untuk bounty make.fun **gta6-01**.
Satu file HTML (`index.html`) memakai three.js via CDN — tidak ada build step, tidak ada aset eksternal selain CDN three.js.

## Cara main

Buka `index.html` lewat server lokal (module script butuh http, bukan file://):

```bash
cd sagara-heat-rec
python3 -m http.server 8080
# buka http://localhost:8080
```

Klik **▶ MULAI MESIN**, lalu ikuti penanda kuning di dunia / minimap.

## Kontrol

| Tombol | Fungsi |
|---|---|
| W A S D / panah | Mengemudi / jalan kaki |
| F | Masuk / keluar mobil |
| SPACE | Rem tangan (drift) |
| SHIFT | Lari / nitro ringan |
| R | Balikkan mobil |
| M | Nyala / matikan suara |

## Isi game

- **Pulau tropis low-poly**: kota grid 5×5 dengan gedung ber-neon & jendela menyala, jalan lingkar pantai, ±150 pohon palem, pantai + laut beranimasi, air mancur plaza, bukit, matahari senja.
- **3 distrik beridentitas**: Pelabuhan Sagara (kontainer + crane), Vice Strip (klub malam neon pink), Bukit Palma (safehouse kru di puncak bukit) — masing-masing dengan **standing 5 bintang** yang naik dari misi.
- **Mobil bisa dikendarai** keliling pulau dengan kamera kejar dari belakang, drift rem tangan, nitro, tabrakan yang merusak mobil + menaikkan kejahatan. Bisa **turun dan jalan kaki** (tombol F), lalu naik lagi.
- **Polisi AI mengejar** dengan lampu rotator merah-biru dan sirene, **bintang buronan 1–5**, meteran *busted*, bintang yang turun bila berhasil menghilang dari kejaran.
- **HUD ala GTA**: uang, health, armour, **Rank + RP** (6 tingkat: Anak Pantai → Legenda Sagara), speedometer, dan **minimap bundar** live (penanda misi kuning/ungu, polisi berkedip merah-biru, permata cyan, panah pemain, kompas).
- **5 misi bertahap**: (1) ambil paket di pelabuhan → (2) antar ke klub Vice Strip dalam 90 detik → (3) balapan pantai 9 checkpoint melawan Sinta si Ratu Strip → (4) hajar kurir rival sampai mobilnya hancur → (5) kabur berbintang 3 ke safehouse Bukit Palma.
- **Free roam tanpa akhir** setelah cerita utama tamat: pekerjaan kilat & balapan mini bergiliran dengan bayaran + RP.
- **15 Permata Sagara** tersembunyi di seluruh pulau — masing-masing +$75 dan +20 RP.
- **Kru Sagara**: Dodo, Sinta, dan Bang Jaka bergabung seiring total standing distrik naik.
- **Pay 'n Spray**: perbaiki mobil, isi armour, dan hapus bintang buronan seharga $150.
- Lalu lintas 10 mobil AI, 14 pejalan kaki NPC, layar **BUSTED / WASTED** dengan biaya $200 untuk kembali ke jalanan.
- **Suara prosedural WebAudio**: dengung mesin mengikuti kecepatan, sirene polisi, dan bunyi penanda misi/permata (tombol M untuk bisu).
