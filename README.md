# Dialog Prestasi 2026 · SK Paya Redan

Papan pemuka **Dialog Prestasi 2026** bagi **semua subjek** (12 subjek): rumusan PBD akhir tahun (8 kelas, 205 murid) dan UASA (Tahun 4–6), dengan analisis mengikut subjek, kelas dan murid serta kategori lemah, sederhana dan cemerlang. Menu utama memaparkan kad setiap subjek; pilih subjek untuk ringkasan, rumusan PBD, keputusan UASA, jurang PBD–UASA, kategori murid, cadangan, ringkasan kelas dan profil murid. Halaman *Perbandingan subjek* memaparkan purata TP setiap kelas × subjek dan purata UASA setiap subjek.

**Prasekolah** dipaparkan sebagai bahagian berasingan (tidak dicampur dengan murid Tahun 1–6): tahap 8 bidang pembelajaran bagi setiap murid, kategori, perbandingan umur dan jantina, serta profil dengan ulasan penuh guru. Laporan prasekolah tidak memberi TP; tahap rendah/sederhana/tinggi ditafsir daripada tiga pernyataan ulasan standard bagi setiap bidang.

- `index.html` — aplikasi satu fail, tiada kebergantungan luar selain fon Google
- **Murid berisiko**: murid Tahun 1–6 yang lemah dalam 3 subjek atau lebih
- **Jurang PBD–UASA**: carta TP lawan markah UASA (setiap titik seorang murid)
- **Cetak**: susun atur A4 bagi halaman semasa
- **Persembahan**: skrin penuh tanpa bar sisi; ◀ ▶ untuk beralih, P untuk buka/tutup
- Navigasi: bar sisi, carian nama murid, atau kekunci ◀ ▶ · M (menu utama)

## Privasi dan akses

- **Seluruh halaman dilindungi kata laluan.** Semua data (agregat, nama dan data setiap murid) disulitkan dengan **AES-256-GCM**; kunci diterbitkan daripada kata laluan melalui PBKDF2-SHA256 (310 000 lelaran). Tanpa kata laluan, pelawat hanya melihat skrin masuk.
- Fail dalam repo tidak mengandungi nama murid, nombor IC atau markah dalam bentuk teks biasa.
- Kata laluan tidak disimpan dalam repo. Kongsi dengan guru yang berkenaan sahaja.
- Pilihan *Ingat pada peranti ini* menyimpan kata laluan dalam `localStorage` pelayar itu. Jangan guna pada komputer kongsi. **Log keluar** memadamnya.
- Untuk menukar kata laluan, data perlu disulitkan semula dan `index.html` diterbitkan semula.

Sumber data: senarai PBD akhir sesi akademik 2026 dan laporan UASA 2026 (Tahun 4–6).
