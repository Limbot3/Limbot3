# 🚀 Panduan Setup GitHub Profile README (Limbot3)

File profil GitHub interaktif Anda sudah siap di folder ini! Ikuti 3 langkah mudah di bawah ini untuk menampilkannya di GitHub Anda.

---

### Langkah 1: Buat Repositori Khusus di GitHub
1. Buka browser dan pergi ke: [https://github.com/new](https://github.com/new)
2. Isi **Repository name**: `Limbot3` *(harus persis sama dengan username GitHub Anda)*.
3. Pastikan memilih **Public** (bukan Private).
4. Jangan centang "Add a README file" (karena kita sudah buat file README sendiri).
5. Klik **Create repository**.

---

### Langkah 2: Push Proyek Ini ke GitHub
Buka terminal Anda di folder ini (`/Users/limwawin/Documents/github/Limbot3`) dan jalankan:

```bash
cd /Users/limwawin/Documents/github/Limbot3
git init
git add .
git commit -m "feat: initial interactive bento grid profile"
git branch -M main
git remote add origin https://github.com/Limbot3/Limbot3.git
git push -u origin main
```

---

### Langkah 3: Aktifkan Izin GitHub Actions (Untuk Snake Animation)
Supaya animasi ular (Snake Game) bisa otomatis menggambar grafik commit Anda:

1. Masuk ke repositori `Limbot3/Limbot3` di GitHub.
2. Klik tab **Settings** -> pilih menu **Actions** di sidebar kiri -> klik **General**.
3. Scroll ke bawah sampai menemukan bagian **Workflow permissions**.
4. Pilih opsi: **"Read and write permissions"** lalu klik **Save**.
5. Pergi ke tab **Actions** di atas repositori -> klik **"Generate Snake Animation"** di daftar kiri -> klik tombol **"Run workflow"** -> klik hijau **Run workflow**.
6. Tunggu sekitar 1 menit. Setelah selesai, animasi ular akan langsung muncul di profil GitHub Anda!

---

### (Opsional) Menghubungkan Spotify Pribadi
Jika Anda ingin widget Spotify menampilkan lagu yang benar-benar sedang Anda dengarkan:
1. Gunakan service gratis seperti [spotify-github-readme](https://github.com/kittinan/spotify-github-readme) atau [novatorem](https://github.com/novatorem/novatorem).
2. Anda cukup deploy template gratisnya ke Vercel dan menautkan akun Spotify Anda.


---

### 🏆 Panduan Koleksi GitHub Achievements
- **Pull Shark 🦈**: Diperoleh dari Pull Request yang berhasil di-merge.
- **YOLO 🕶️**: Diperoleh saat melakukan merge PR tanpa menunggu code review.
- **Pair Extraordinaire 👥**: Diperoleh dengan membuat commit berkolaborasi (Co-authored-by).
- **Quickdraw ⚡**: Diperoleh saat menutup issue dalam waktu kurang dari 5 menit.
