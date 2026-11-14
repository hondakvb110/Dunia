# Dunia — Kisah Perintis

Game browser berbasis teks yang ringan. Buka `index.html` di browser; tidak ada framework, server, gambar berat, atau aset eksternal.

## Cara bermain

- Pilih tindakan di tab **Dunia** untuk membangun ladang, bengkel, dan pasar; menjelajah; atau mengatur panen.
- Tekan **Akhiri pekan** untuk menjalankan simulasi: kebutuhan pangan, produksi, pertumbuhan warga, perubahan harga, dan kejadian tak terduga.
- Kembangkan keluarga melalui tab **Keluarga** dengan mendidik penerus, menghadiri dewan, dan membentuk persekutuan.
- Jual atau beli persediaan di tab **Pasar**.
- Lihat jumlah tiap ras di `populasi.html`.
- Kelola pet, ternak, dan tanaman hidup di `pets.html`; beri makan, air, perhatian, dan tempat tinggal sesuai kebutuhan.
- Atur jam serta kalender Gregorian di `waktu.html`.
- Kemajuan tersimpan otomatis di `localStorage` browser dengan kunci dunia yang sama.

## Pemain sebagai dewa

Pemain berperan sebagai dewa yang bisa merasuk ke makhluk hidup untuk menjalani kehidupan dari dalam tubuh mereka. Saat bersemayam di jasad, pemain dapat merasakan kebutuhan, naluri, dan keputusan makhluk yang dipilih, lalu kembali ke wujud ilahi kapan pun mereka mau. Dewa dapat berpindah di antara makhluk untuk mengamati kehidupan dan pengaruh keputusan mereka terhadap dunia.

## Waktu dan kalender

Halaman `waktu.html` menyediakan jam dunia dan kalender Masehi/Gregorian yang persisten.

- Tanggal menampilkan nama hari, tanggal, bulan, dan tahun Masehi; waktu memakai format 24 jam.
- Kalender memiliki 12 bulan dan mengikuti aturan tahun kabisat Gregorian, termasuk pengecualian tahun abad kecuali habis dibagi 400.
- Pemain dapat menjalankan atau menjeda jam serta memajukan waktu satu jam, satu hari, atau satu pekan.
- Kalender dimulai pada 1 Januari tahun 1 Masehi (kalender Gregorian proleptik).

## Populasi

Halaman `populasi.html` membaca save dunia di browser dan menampilkan jumlah manusia, elf, goblin, mermaid, centaur, Lamia, serta hybrid secara terpisah. Data dapat diperbarui manual, otomatis berkala, atau saat save berubah di tab lain. Halaman ini hanya membaca data dan tidak mengubah save.

## Pet, ternak, dan tanaman hidup

Halaman `pets.html` menyediakan koleksi makhluk yang dirawat sebagai anggota dunia, bukan sekadar sumber daya.

- **Pet:** anjing, kucing, burung, dan kelinci. Pemain dapat memberi makan, mengajak berinteraksi, dan merawat tempat tinggal; ikatan serta kebahagiaan meningkat lewat perhatian.
- **Ternak:** sapi dan ayam. Mereka memiliki kebutuhan pakan, air, kandang, dan perawatan yang baik.
- **Tanaman hidup sebagai pet:** pohon hidup, bunga hidup, dan sulur hidup adalah teman yang dirawat sebagai makhluk. Mereka membutuhkan air, cahaya matahari, tanah subur, dan ruang tumbuh.
- Setiap makhluk memiliki usia, kesehatan, kebutuhan, kebahagiaan/kesuburan, serta ikatan; waktu harian memperbarui kondisinya dan pengabaian dapat mengurangi kesehatan.
- Mengadopsi atau merekrut menggunakan persediaan dunia seperti makanan, kayu, dan kain. Semua data pet disimpan di properti `pets` pada save `dunia-pioneers-save-v1`, bersama persediaan dan kalender.

Sistem dan teks permainan dibuat khusus untuk proyek ini; tidak menyalin kode, aset, nama faksi, atau konten dari game lain.
