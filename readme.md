# Git & Github Full Course

![Alt Text](./images/BasicGuideGitHub.jpg)

<hr>

## Learn Command Github


### 1. git init

- Fungsi: Menginisialisasi repository Git di direktori lokal.

- Contoh: git init

- Penjelasan: Digunakan untuk membuat repository Git baru di direktori saat ini.

- git add nama file / git add . (untuk semua file)

### 2. git clone

- Fungsi: Mengunduh repository dari remote (misalnya dari GitHub).

- Contoh: `git clone https://github.com/username/repo.git`

- Penjelasan: Membuat salinan dari repository yang ada dari remote ke lokal.

### 3. git add

- Fungsi: Menambahkan perubahan pada staging area sebelum melakukan commit.

- Contoh: git add .

- Penjelasan: Menambahkan semua file yang berubah untuk siap di-commit. Bisa juga menggunakan git add <file> untuk file tertentu.

### 4. git commit -m "<pesan>"

- Fungsi: Menyimpan snapshot perubahan yang ada di staging area ke repository.

- Contoh: git commit -m "Initial commit"

- Penjelasan: Commit dengan pesan untuk mendokumentasikan perubahan yang dilakukan.

### 5. git status

- Fungsi: Menampilkan status dari repository, termasuk file yang diubah, staged, atau belum di-track.

- Contoh: git status

- Penjelasan: Memberi gambaran tentang perubahan yang ada dan tindakan yang perlu dilakukan.

### 6. git push

- Fungsi: Mengirim perubahan lokal ke repository remote.

- Contoh: git push origin main

- Penjelasan: Mengirim commit yang ada di branch lokal ke branch yang sesuai di remote (misalnya GitHub).

### 7. git pull

- Fungsi: Mengambil dan menggabungkan perubahan dari repository remote ke lokal.

- Contoh: git pull origin main

- Penjelasan: Memperbarui branch lokal dengan perubahan terbaru dari remote.

### 8. git branch

- Fungsi: Menampilkan daftar branch atau membuat branch baru.

- Contoh: git branch (untuk melihat daftar branch), git branch new-feature (untuk membuat branch baru)

- Penjelasan: Memungkinkan pengelolaan branch, baik untuk melihat atau membuat cabang baru.

### 9. git checkout

- Fungsi: Beralih antara branch atau commit tertentu.

- Contoh: git checkout main (untuk pindah ke branch main), git checkout <commit> (untuk berpindah ke commit tertentu)

- Penjelasan: Digunakan untuk navigasi antara branch atau snapshot repository yang berbeda.

### 10. git merge

- Fungsi: Menggabungkan branch lain ke dalam branch saat ini.

- Contoh: git merge new-feature

- Penjelasan: Menggabungkan perubahan dari branch new-feature ke branch yang sedang aktif.

### 11. git log

- Fungsi: Menampilkan riwayat commit.

- Contoh: git log

- Penjelasan: Menampilkan daftar commit yang telah dilakukan, termasuk pesan commit, hash, dan waktu commit.

### 12. git revert <commit>

- Fungsi: Membatalkan perubahan yang dilakukan di commit tertentu.

- Contoh: git revert <hash_commit>

- Penjelasan: Membuat commit baru yang membalikkan perubahan dari commit yang ditentukan, tanpa mengubah riwayat commit sebelumnya.

### 13. git reset

- Fungsi: Mengembalikan perubahan pada commit tertentu.

- Contoh: git reset --hard <commit> (untuk mengembalikan sepenuhnya ke commit tertentu)

- Penjelasan: Mengatur ulang branch saat ini ke status yang lebih lama, dengan pilihan untuk tetap mempertahankan atau membuang perubahan.

### 14. git stash

- Fungsi: Menyimpan perubahan yang belum di-commit sementara, sehingga Anda dapat bekerja di branch lain tanpa kehilangan perubahan.

- Contoh: git stash

- Penjelasan: Menyimpan sementara perubahan kerja saat ini tanpa melakukan commit, dan bisa diambil kembali dengan git stash pop.

<hr>

## For More Details Check Below
![Images]()
<br>
[SuperSimpleDev](https://youtu.be/hrTQipWp6co?si=UJqNOZmhaJGj8FIZ)
<br>
![Images]()
<br>
[JavaScript Mastery](https://youtu.be/S7XpTAnSDL4?si=-TDNw2Z1BHW7Yn52)

## Credits
- SuperSimpleDev
- JavaScript Mastery
