# Panitia Matematik · SK Paya Redan

Papan pemuka **Dialog Prestasi Matematik 2026**: rumusan PBD akhir tahun (8 kelas, 205 murid) dan UASA Matematik Tahun 5–6, dengan analisis mengikut kelas serta kategori murid lemah, sederhana dan cemerlang.

- `index.html` — aplikasi satu fail, tiada kebergantungan luar selain fon Google
- Navigasi: bar sisi, atau kekunci ◀ ▶ · M (menu utama) · F (skrin penuh)

## Privasi dan mod guru

- **Mod awam** (lalai): angka agregat sahaja. Purata bagi kumpulan kurang 3 murid disembunyikan.
- **Mod guru**: nama dan data setiap murid (TP semua subjek, markah UASA Matematik, kategori, profil, carian). Data ini **disulitkan dengan AES-256-GCM** (kunci daripada kata laluan melalui PBKDF2-SHA256, 310 000 lelaran) dan hanya dinyahsulit dalam pelayar selepas kata laluan panitia dimasukkan. Fail dalam repo tidak mengandungi nama atau nombor IC dalam bentuk teks biasa.
- Kata laluan tidak disimpan dalam repo. Kongsi dengan guru panitia sahaja; jangan tayang mod guru di skrin awam.
- Pilihan *Ingat pada peranti ini* menyimpan kata laluan dalam `localStorage` pelayar itu. Jangan guna pada komputer kongsi. Tekan **Kunci semula** untuk memadamnya.
- Untuk menukar kata laluan, data perlu disulitkan semula dan `index.html` diterbitkan semula.

Sumber data: senarai PBD akhir sesi akademik 2026 dan laporan UASA 2026 (Tahun 4–6).
