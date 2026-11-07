# DAY 1 — BUILDING WITH AI, MANAGING CHANGE WITH GITHUB

### Identitas

**Nama Lengkap:** Fatimah Fadlun Zahira

**Kelompok:** 17 - Minecraft

**Program Studi:** Teknik Multimedia dan Jaringan (TMJ)

**Jurusan:** Teknik Informatika dan Komputer

**Institusi:** Politeknik Negeri Jakarta

---

### Deskripsi Repository

Repository ini dibuat sebagai bentuk dokumentasi kegiatan Day 1 Proyek Workshop dengan tema **"Building with AI, Managing Change with GitHub"**.
Repository ini berisi rangkuman materi, catatan pembelajaran, pengetahuan baru, serta refleksi pribadi selama mengikuti kegiatan workshop. Dokumentasi ini juga menjadi sarana untuk memahami pemanfaatan Artificial Intelligence (AI) dalam pengembangan aplikasi serta penggunaan Git dan GitHub untuk mengelola perubahan proyek.

### Tujuan Repository
1. Mendokumentasikan materi dan kegiatan selama workshop.
2. Memahami penerapan Prompt Engineering dalam penggunaan AI.
3. Mengenal Git dan GitHub sebagai tools dalam pengembangan perangkat lunak.
4. Memahami proses version control untuk mengelola perubahan proyek.
5. Meningkatkan keterampilan dalam mengembangkan aplikasi dengan bantuan AI.
6. Menjadi arsip pembelajaran yang dapat dipelajari kembali.

---

## Rangkuman Materi Workshop
Workshop Day 1 mengangkat tema *Building with AI, Managing Change with GitHub* yang membahas dua materi utama, yaitu Prompt Engineering serta Git dan GitHub.

### A. Prompt Engineering

#### 1. Pengertian

Prompt Engineering merupakan cara merancang instruksi agar AI dapat memberikan jawaban yang tepat, relevan, dan layak untuk digunakan. Prompt sendiri adalah instruksi atau masukan yang diberikan kepada model AI untuk mendapatkan hasil tertentu. Bentuknya dapat berupa pertanyaan sederhana, kata kunci, instruksi kompleks, maupun potongan kode.

#### 2. Pentingnya Context dalam Prompt

Context atau konteks merupakan informasi tambahan yang diberikan kepada AI agar dapat memahami kebutuhan, tujuan, dan kondisi dari tugas yang diberikan. Pemberian konteks yang jelas dapat membantu AI menghasilkan jawaban yang lebih relevan dan sesuai dengan kebutuhan pengguna dibandingkan instruksi yang terlalu umum.

#### 3. Struktur Prompt yang Baik

Prompt yang baik memiliki empat komponen utama:

1) **Role:** Menentukan peran atau posisi yang harus dijalankan oleh AI.
2) **Task:** Menjelaskan tugas yang harus dikerjakan oleh AI.
3) **Context:** Memberikan informasi latar belakang dan kebutuhan dari tugas tersebut.
4) **Format:** Menentukan bentuk atau format hasil yang diharapkan.

#### 4. Contoh Penerapan Prompt

Salah satu contoh yang diberikan dalam workshop adalah pembuatan aplikasi sederhana bernama *Student Task Planner*. Aplikasi tersebut ditujukan untuk membantu mahasiswa tahun pertama dalam mengelola tugas dan tenggat waktu. Beberapa kebutuhan aplikasinya meliputi:

1) Menampilkan daftar tugas.
2) Menampilkan judul dan tenggat waktu setiap tugas.
3) Menampilkan status penyelesaian tugas.
4) Memberikan fitur untuk menandai tugas yang telah selesai.
5) Menyediakan filter tugas berdasarkan status.

#### 5. Keuntungan Prompt Engineering

Beberapa keuntungan Prompt Engineering antara lain:

1) Meningkatkan performa AI model.
2) Mengurangi bias dan respons yang bersifat ofensif.
3) Meningkatkan kontrol dan prediktabilitas.
4) Memberikan pengalaman pengguna yang lebih baik.

---

### B. Git dan GitHub

#### 1. Pengertian Git

Git merupakan *Version Control System* (VCS) yang digunakan untuk melacak siapa, kapan, dan perubahan apa saja yang dilakukan pada suatu file. Git diciptakan oleh Linus Torvalds pada tahun 2005. Git membantu pengguna mencatat dan mengelola setiap perubahan yang terjadi pada file dalam suatu proyek.

#### 2. Pengertian GitHub

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online serta mendukung kolaborasi dalam pengembangan proyek.

#### 3. Perbedaan Git dan GitHub

| Git | GitHub |
|---|---|
| Sistem version control terdistribusi. | Platform berbasis web. |
| Digunakan untuk melacak dan mengelola perubahan kode secara lokal. | Digunakan untuk menyimpan repository Git secara online. |
| Dijalankan melalui terminal atau aplikasi pendukung. | Diakses melalui website atau aplikasi. |

#### 4. Git Workflow

Dalam Git terdapat tiga bagian utama yang menjadi bagian dari alur kerja pengelolaan proyek:

1) **Working Directory** : salinan proyek yang sedang dikerjakan. File di dalamnya dapat dibuka, digunakan, dan dimodifikasi oleh pengguna.
2) **Staging Area** : tempat untuk menyimpan informasi mengenai perubahan file yang akan dimasukkan ke dalam commit berikutnya. Dalam istilah teknis Git, staging area disebut sebagai index.
3) **Git Directory** : tempat Git menyimpan metadata dan object database dari sebuah proyek. Bagian ini menyimpan informasi yang dibutuhkan Git untuk mengelola proyek.

#### 5. Essential Git Commands

Berikut beberapa perintah dasar Git yang dipelajari selama workshop:

| Perintah | Fungsi |
|---|---|
| `git init` | Memulai repository Git baru. |
| `git add .` | Memasukkan file dan perubahan ke staging area. |
| `git add --all` | Menambahkan seluruh perubahan ke staging area. |
| `git add -A` | Memiliki fungsi yang sama dengan `git add --all`. |
| `git add *` | Menambahkan file baru dan file yang dimodifikasi, tetapi tidak termasuk file yang dihapus. |
| `git commit -m "message"` | Menyimpan perubahan ke dalam repository. |
| `git clone URL` | Menyalin repository ke komputer lokal. |
| `git remote add origin URL` | Menambahkan alamat repository remote. |
| `git push origin main` | Mengirim perubahan dari branch lokal ke GitHub. |
| `git pull origin main` | Mengambil dan menggabungkan perubahan dari repository remote. |

#### 6. Git Setup

Sebelum menggunakan Git, pengguna perlu menginstalnya sesuai dengan sistem operasi perangkat.

Setelah instalasi, pengguna dapat memeriksa apakah Git telah terpasang menggunakan perintah:

```bash
git --version
```

Selanjutnya, dilakukan konfigurasi identitas pengguna.

**Mengatur username:**

```bash
git config --global user.name "Your Name"
```

**Mengatur email:**

```bash
git config --global user.email "your-email@example.com"
```

**Memeriksa konfigurasi:**

```bash
git config --global --list
```

Konfigurasi tersebut digunakan untuk mengidentifikasi pengguna yang melakukan perubahan dan commit pada repository.

#### 7. Visual Studio Code Setup

Visual Studio Code merupakan editor kode yang digunakan untuk membantu proses pengembangan proyek.

Materi workshop menjelaskan instalasi VS Code dan penggunaan Command Palette melalui kombinasi tombol:

- `Ctrl + Shift + P` pada Windows.
- `Command + Shift + P` pada macOS.

Salah satu perintah yang diperkenalkan adalah `Shell Command: Install 'code' command in PATH`.

Untuk memeriksa instalasi melalui terminal, digunakan perintah:

```bash
code --version
```

#### 8. Menambahkan Repository ke Git

Terdapat dua cara yang diperkenalkan dalam materi workshop:

**Cara pertama: Membuat repository lokal**

Memulai repository baru melalui terminal dengan perintah:

```bash
git init
```

**Cara kedua: Menggunakan repository GitHub**

1) Membuka GitHub.
2) Membuat repository baru.
3) Membuka tombol Code.
4) Menyalin URL repository.
5) Membuka terminal pada komputer lokal.
6) Menjalankan perintah:

```bash
git clone URL
```

#### 9. Working Area ke Staging Area

Untuk memindahkan perubahan dari working directory ke staging area, terdapat beberapa perintah yang dapat digunakan:

```bash
git add --all
```

```bash
git add -A
```

```bash
git add .
```

Ketiga perintah tersebut digunakan untuk menambahkan perubahan ke staging area, sedangkan `git add *` memiliki perilaku yang berbeda karena tidak menambahkan file yang dihapus.

---

### C. Praktik Proyek: Student Task Planner

Pada akhir materi, peserta diarahkan untuk membuat proyek sederhana bernama **Student Task Planner**. Proyek ini merupakan aplikasi yang dirancang untuk membantu mahasiswa mengelola daftar tugas dan tenggat waktu. Tahapan pengerjaan yang dijelaskan dalam workshop:

1. Menginstal platform AI-assisted seperti Claude, Antigravity, atau ChatGPT.
2. Menulis prompt untuk membuat aplikasi atau website.
3. Menambahkan proyek ke Git menggunakan `git init`.
4. Melakukan commit dan push ke GitHub.
5. Melakukan perubahan atau pengembangan pada proyek.
6. Melakukan commit dan push kembali ke GitHub.

---

## Poin-Poin Penting dan Pengetahuan Baru

Berdasarkan seluruh materi yang disampaikan, terdapat beberapa hal penting yang saya pelajari:

1. **Pemanfaatan AI:** AI dapat membantu proses pengembangan aplikasi, tetapi membutuhkan instruksi yang jelas agar hasilnya sesuai kebutuhan.
2. **Prompt Engineering:** Struktur Role, Task, Context, dan Format dapat membantu menghasilkan prompt yang lebih efektif.
3. **Git dan GitHub:** Keduanya memiliki fungsi berbeda, tetapi dapat digunakan secara bersamaan dalam pengelolaan proyek.
4. **Version Control:** Perubahan pada file proyek dapat dilacak dan dikelola menggunakan Git.
5. **Git Workflow:** Working Directory, Staging Area, dan Git Directory memiliki peran masing-masing dalam proses pengelolaan perubahan.
6. **Git Commands:** Perintah seperti git init, git add, git commit, git push, dan git pull merupakan dasar yang perlu dipahami.
7. **Repository Management:** Repository GitHub dapat digunakan sebagai tempat penyimpanan proyek secara online.

## Pendapat Pribadi tentang Day 1 Proyek Workshop

Menurut saya, Day 1 Proyek Workshop sangat menarik dan bermanfaat karena memberikan pengetahuan baru mengenai Prompt Engineering serta penggunaan Git dan GitHub. Saya menjadi lebih memahami cara memanfaatkan AI untuk membantu pengembangan aplikasi dan mengelola perubahan proyek. Materi ini juga memotivasi saya untuk terus belajar dan mengembangkan keterampilan di bidang teknologi.

## Kesimpulan
Kegiatan Day 1 Proyek Workshop memberikan pemahaman mengenai dua aspek penting dalam pengembangan aplikasi, yaitu pemanfaatan AI melalui Prompt Engineering dan pengelolaan perubahan proyek menggunakan Git serta GitHub. Melalui materi dan praktik yang diberikan, peserta diperkenalkan pada proses penyusunan prompt, penggunaan perintah Git, pengelolaan repository, hingga pengembangan aplikasi sederhana. Pengetahuan tersebut menjadi bekal awal untuk menghadapi proses pengembangan proyek pada kegiatan workshop selanjutnya.
