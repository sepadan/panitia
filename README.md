# Panitia Matematik · SK Paya Redan

Papan pemuka **Dialog Prestasi Matematik 2026**: rumusan PBD akhir tahun (8 kelas, 205 murid) dan UASA Matematik Tahun 5–6, dengan analisis mengikut kelas serta kategori murid lemah, sederhana dan cemerlang.

- `index.html` — aplikasi satu fail, tiada kebergantungan luar selain fon Google
- Navigasi: bar sisi, carian nama murid, atau kekunci ◀ ▶ · M (menu utama) · F (skrin penuh)

## Privasi dan akses

- **Seluruh halaman dilindungi kata laluan.** Semua data (agregat, nama dan data setiap murid) disulitkan dengan **AES-256-GCM**; kunci diterbitkan daripada kata laluan melalui PBKDF2-SHA256 (310 000 lelaran). Tanpa kata laluan, pelawat hanya melihat skrin masuk.
- Fail dalam repo tidak mengandungi nama murid, nombor IC atau markah dalam bentuk teks biasa.
- Kata laluan tidak disimpan dalam repo. Kongsi dengan guru yang berkenaan sahaja.
- Pilihan *Ingat pada peranti ini* menyimpan kata laluan dalam `localStorage` pelayar itu. Jangan guna pada komputer kongsi. **Log keluar** memadamnya.
- Untuk menukar kata laluan, data perlu disulitkan semula dan `index.html` diterbitkan semula.

Sumber data: senarai PBD akhir sesi akademik 2026 dan laporan UASA 2026 (Tahun 4–6).
