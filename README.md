# Sagara Heat — Isle of Vice

Game open-world crime 3D bergaya GTA untuk bounty make.fun **gta6-01**.
Satu file HTML (`index.html`) memakai three.js via CDN — tidak ada build step.

## Cara main

Buka `index.html` lewat server lokal (module script butuh http, bukan file://):

```bash
cd sagara-heat
python3 -m http.server 8080
# buka http://localhost:8080
```

Klik **▶ MULAI MESIN**, lalu ikuti penanda kuning.

## Kontrol

| Tombol | Fungsi |
|---|---|
| W A S D | Mengemudi / jalan kaki |
| F | Masuk / keluar mobil |
| SPACE | Rem tangan (drift) |
| SHIFT | Lari / nitro ringan |
| R | Balikkan mobil |

## Isi game

- **Pulau tropis low-poly**: kota grid 5×5 dengan ±125 gedung ber-neon & jendela menyala, jalan lingkar pantai, ±136 pohon palem, pantai, laut beranimasi, air mancur plaza, matahari senja.
- **3 distrik beridentitas**: Pelabuhan Sagara (kontainer + crane), Vice Strip (klub malam neon pink), Bukit Palma (safehouse kru di bukit) — masing-masing dengan **standing 5 bintang** yang naik dari misi.
- **Mobil bisa dikendarai** keliling pulau dengan kamera kejar dari belakang, drift rem tangan, nitro, tabrakan merusak + memicu kejahatan.
- **Polisi AI mengejar** lengkap dengan lampu rotator merah-biru, **bintang buronan 1–5**, meteran *busted*, dan bintang yang turun bila berhasil menghilang dari kejaran.
- **HUD ala GTA**: uang, health, armour, **Rank + RP** (6 tingkat: Anak Pantai → Legenda Sagara), speedometer, dan **minimap bundar** live (penanda misi kuning, polisi berkedip merah-biru, target ungu, panah pemain).
- **5 misi bertahap**: ambil paket di pelabuhan → antar ke klub dalam 90 detik → balapan pantai 9 checkpoint melawan Ratu Strip → hajar kurir rival sampai mobilnya hancur → kabur berbintang 3 ke safehouse.
- **Free roam tanpa akhir** setelah misi utama tamat: antar paket kilat & balapan mini bergiliran dengan bayaran + RP.
- **Kru Sagara**: Dodo, Sinta, dan Bang Jaka bergabung seiring total standing distrik naik.
- **Pay 'n Spray**: perbaiki mobil, isi armour, dan hapus bintang buronan seharga $150.
- Lalu lintas 10 mobil AI + mobil parkir yang bisa ditabrak, layar **BUSTED / WASTED** dengan biaya $200 untuk kembali ke jalanan.
