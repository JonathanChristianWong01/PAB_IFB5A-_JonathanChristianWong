# Pemrograman Aplikasi Bergerak

## Identitas Mahasiswa
- **Nama:** Jonathan Christian Wong
- **NIM:** 2411015
- **Kelas:** IFB5A
- **Mata Kuliah:** Pemrograman Aplikasi Bergerak

## Judul Proyek
Aplikasi Tugas Praktikum Pemrograman Aplikasi Bergerak yang terdiri dari:
1. **Form Profil Mahasiswa Interaktif** — State, Events & User Interaction
2. **Profil Mahasiswa dengan Tiga Layar** — Navigation Compose + ViewModel
3. **Catatan Kuliah** — Local Persistence dengan Room Database (CRUD)

## Deskripsi
Repository ini berisi source code untuk tiga tugas praktikum mandiri mata kuliah Pemrograman Aplikasi Bergerak yang mencakup materi:
- **Materi 4:** Pengelolaan State, Event, dan User Interaction menggunakan `rememberSaveable`, `mutableStateOf`, `onValueChange`, dan `onClick`.
- **Materi 5:** Navigasi antar-layar dengan Navigation Compose dan pengelolaan state lintas layar dengan ViewModel (data bertahan saat rotasi).
- **Materi 6:** Penyimpanan data permanen lokal menggunakan Room Database (Entity, DAO, Database, Repository, ViewModel) dengan operasi CRUD lengkap (Tambah, Tampil, Ubah, Hapus).

Setiap tugas dibuat sebagai project Android Studio terpisah agar mudah dipelajari, diuji, dan dinilai.

## Teknologi / Framework
- **Bahasa Pemrograman:** Kotlin
- **UI Toolkit:** Jetpack Compose (Material 3)
- **Navigasi:** Navigation Compose
- **State Management:** `rememberSaveable`, `mutableStateOf`, ViewModel, StateFlow
- **Database Lokal:** Room Database (SQLite) dengan KSP
- **Concurrency:** `viewModelScope` untuk operasi asynchronous
- **IDE:** Android Studio
- **Version Control:** Git + GitHub

## Struktur Folder
PAB_IFB5A_JonathanChristianWong/
├── ProfilInteraktif/ # Tugas 1: Form Profil Interaktif (State & Event)
│ ├── app/src/main/java/...
│ └── app/src/main/AndroidManifest.xml
├── ProfilNavigasi2/ # Tugas 2: Navigasi 3 Layar + ViewModel
│ ├── app/src/main/java/...
│ └── app/src/main/AndroidManifest.xml
├── CatatanKuliah/ # Tugas 3: Aplikasi Catatan dengan Room CRUD
│ ├── app/src/main/java/...
│ └── app/src/main/AndroidManifest.xml
├── .gitignore
└── README.md


## Repository
- **GitHub:** `https://github.com/JonathanChristianWong01/PAB_IFB5A_JonathanChristianWong`
- **Branch Utama:** `main`
- **Branch Pengembangan:** `develop`

## Cara Menjalankan
1. Clone repository ini atau download ZIP source code.
2. Buka Android Studio, pilih **File → Open**, lalu pilih salah satu folder project (misal `ProfilInteraktif`).
3. Tunggu proses Gradle Sync selesai hingga semua indikator hijau.
4. Buat emulator (misal: Pixel 5 API 34) atau hubungkan device fisik dengan USB Debugging aktif.
5. Klik tombol **Run ▶️** hijau untuk menginstall dan menjalankan aplikasi.
6. Ulangi langkah 2-5 untuk project `ProfilNavigasi2` dan `CatatanKuliah`.
