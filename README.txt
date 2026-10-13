# Petualangan Jejak Kebaikan — Game PAI SMP

Game website edukasi PAI untuk SMP, berisi 5 level dan 25 soal contoh:
1. Gerbang Iman — Akidah
2. Taman Ibadah — Ibadah
3. Hutan Akhlak — Akhlak
4. Perpustakaan Qur'an — Al-Qur'an dan Hadis
5. Kota Peradaban — Sejarah Islam

## Cara menjalankan di komputer
1. Ekstrak ZIP ini.
2. Buka folder `petualangan_jejak_kebaikan`.
3. Klik dua kali `index.html`. Game terbuka di browser seperti Chrome atau Edge.
4. Tidak perlu instalasi dan tidak memerlukan internet untuk memainkan versi ini.

## Cara menerbitkan gratis dengan GitHub Pages
1. Masuk ke GitHub dan buat repository baru, misalnya `game-pai-smp`.
2. Unggah file `index.html` ke bagian utama (root) repository.
3. Buka Settings → Pages.
4. Pada bagian Build and deployment, pilih Deploy from a branch.
5. Pilih branch `main` dan folder `/(root)`, lalu Save.
6. Tunggu proses publikasi. URL biasanya berbentuk `https://nama-akun.github.io/game-pai-smp/`.

## Cara bermain
- Klik Mulai Petualangan.
- Pilih Mode Individu atau Mode Kelompok.
- Pilih level yang terbuka.
- Jawab 5 soal. Jawaban benar mendapat 100 poin, dengan bonus streak.
- Baca pembahasan, lalu lanjutkan hingga hasil muncul.
- Di mode kelompok, dua tim bergantian menjawab.

## Catatan teknis
- Progres disimpan menggunakan localStorage pada browser/perangkat yang sama.
- Versi awal tidak memakai akun, server, atau database.
- Mode kelompok dirancang untuk satu perangkat bersama. Untuk kompetisi daring antarperangkat dengan papan peringkat bersama, diperlukan backend/database.
- Soal adalah contoh latihan umum. Guru sebaiknya meninjau dan menyesuaikan isi dengan buku PAI dan Budi Pekerti yang dipakai sekolah.
