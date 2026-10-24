# Logika & Himpunan (TIF322103) · Teknik Informatika UMS

Diktat perkuliahan komprehensif dan portal evaluasi logika formal untuk matakuliah **Logika dan Himpunan (TIF322103)**, Program Studi Teknik Informatika, Universitas Muhammadiyah Surakarta.

**Live demo:** [voltakyy.github.io/materi-lohim](https://voltakyy.github.io/materi-lohim/)

Pengampu: **Reinal Ariyuda, B.Eng., M.Eng.** • 3 SKS (Kelas B / C) • Ruang G0301 Kampus 2 UMS.

---

## Fitur Utama

- **Rangkuman Kuliah Lengkap Pertemuan 1 s.d. 5**:
  - **Kontrak Kuliah & Silabus**: Penilaian, presensi, aturan baku penulisan logika.
  - **Pertemuan 1 (Pengenalan Logika)**: Proposisi atomik, nilai kebenaran, negasi (¬).
  - **Pertemuan 2 (Logika Proposisional)**: Konjungsi (∧), Disjungsi (∨), tabel kebenaran dasar.
  - **Pertemuan 3 (Proposisi Bersyarat)**: Implikasi (→), Biimplikasi (↔), variasi implikasi (Konvers, Invers, Kontraposisi), dan Pohon Sintaksis (*Parse Tree*).
  - **Pertemuan 4 (Karakteristik Kalimat)**: Tautologi, Kontradiksi, Kontingensi, Ekuivalensi Logis, dan Hukum De Morgan.
  - **Pertemuan 5 (Inferensi Logika)**: Kaidah penarikan kesimpulan (*Modus Ponens, Modus Tollens, Silogisme Hipotetis, Silogisme Disjungtif*).
- **Standar Baku T-First ($T \to F$)**:
  - Seluruh tabel kebenaran disusun baku dimulai dari nilai $T$ di baris atas kemudian $F$ di baris bawah sesuai silabus pengampu kuliah.
- **Desain Editorial Midnight Navy & Warm Cream**:
  - Estetika tema gelap premium (*Deep Navy* `#0C1830`, aksen emas hangat `#E5A144`, kertas krem `#F7F0E1` untuk kartu contoh soal).
  - Bebas *AI slop*, sudut tegas (*crisp radius* 3px–4px), tipografi editorial (*Georgia* + *Segoe UI* + *Monospace*), tanpa pop-up mengganggu.
- **Evaluator Logika Cepat**:
  - Alat evaluasi kebenaran proposisi instan yang tersemat pada sidebar (*sticky widget*).
- **Bank Kuis Interaktif (38 Soal)**:
  - Mencakup Pertemuan 1 s.d. 5 dengan filter tingkat kesulitan (*Semua, Mudah, Sedang, Sukar*).
  - Termasuk 19 soal *review* resmi Pertemuan 4 lengkap dengan pembahasan langkah demi langkah per opsi.
- **Simulasi Ujian Tengah Semester (UTS)**:
  - 15 soal ujian komprehensif acak dari P1–P5.
  - Timer hitung mundur 30:00 menit.
  - Penilaian otomatis skala 0–100, konversi indeks mutu huruf (A, AB, B, BC, C, D/E), dan kartu diagnostik penguasaan per topik.

---

## Menjalankan Secara Lokal

Situs ini dibuat 100% *standalone* dalam satu file tanpa *build step*, tanpa *framework*, dan tanpa server:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

---

## Push ke GitHub & Deploy GitHub Pages

Repo ini sudah disiapkan untuk langsung di-*push* ke GitHub milikmu (`voltakyy`):

```bash
cd C:\Users\Asus\materi-lohim

git init
git add .
git commit -m "feat: Diktat & Portal Kuis Logika dan Himpunan (TIF322103) UMS"
git branch -M main
git remote add origin https://github.com/voltakyy/materi-lohim.git
git push -u origin main
```

### Mengaktifkan GitHub Pages

1. Buka repo di GitHub: `https://github.com/voltakyy/materi-lohim`
2. Buka **Settings** → **Pages**.
3. Di bawah **Build and deployment** → Source pilih: **Deploy from a branch**.
4. Pilih Branch: **main**, Folder: **/ (root)** → **Save**.
5. Tunggu 1–2 menit, situs akan langsung aktif di:
   👉 **https://voltakyy.github.io/materi-lohim/**

---

## Struktur File

```
materi-lohim/
├── index.html       # Seluruh aplikasi: UI, materi P1-P5, kuis 38 soal, UTS engine
├── README.md        # Dokumentasi lengkap & panduan deployment
└── .gitignore       # Konfigurasi ignore file
```

---

## Lisensi & Atribusi

- **Materi Kuliah**: Berdasarkan silabus resmi Program Studi Teknik Informatika, Fakultas Komunikasi dan Informatika, Universitas Muhammadiyah Surakarta (Dosen Pengampu: Reinal Ariyuda, B.Eng., M.Eng.).
- **Kode & Desain**: Dibuat untuk keperluan belajar mandiri. Bebas digunakan dan dimodifikasi untuk tujuan akademik.
