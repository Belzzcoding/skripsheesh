# skripsheesh

### Final Assignment or Final Me💀

Repository ini berisi dokumentasi dan berkas pendukung **Tugas Akhir/Skripsi** mengenai pengembangan sistem deteksi intrusi pada aplikasi web **SIPESTAR**.

> *One repository to document the journey. One thesis to survive the semester. 💀*

---

## 📌 Tentang Penelitian

Penelitian ini berfokus pada pengembangan **Web Intrusion Detection System (WIDS)** berbasis **Machine Learning** untuk mendeteksi dan mengklasifikasikan aktivitas mencurigakan pada sistem SIPESTAR.

Model yang digunakan dalam penelitian ini adalah **Random Forest**, dengan fokus klasifikasi terhadap tiga kategori traffic:

* 🟢 **Normal**
* 🔴 **Brute Force**
* 🟠 **SQL Injection**

SIPESTAR sendiri merupakan sistem informasi pengelolaan penginapan berbasis web yang menangani aktivitas seperti **login, booking, data pengguna, dan pengelolaan penginapan**.

### 🎯 Judul Skripsi

> **Pengembangan Web Intrusion Detection System (WIDS) Berbasis Random Forest untuk Klasifikasi Serangan Brute Force dan SQL Injection pada Sistem SIPESTAR**

---

## 🔬 Ruang Lingkup

Penelitian ini berfokus pada:

* Web Application Security
* Web Intrusion Detection System (WIDS)
* Machine Learning
* Supervised Classification
* Random Forest
* Brute Force Attack
* SQL Injection
* HTTP Traffic Analysis
* Feature Engineering
* Security Monitoring Dashboard

Penelitian **tidak berfokus pada** jenis serangan lain seperti XSS, DDoS, malware, maupun tindakan pencegahan otomatis seperti IP blocking.

---

## 🛠️ Teknologi yang Digunakan

`Python` · `Random Forest` · `Scikit-learn` · `Pandas` · `Flask/FastAPI` · `Bootstrap` · `Chart.js` · `XAMPP/Laragon`

---

## 📊 Dataset

Dataset penelitian tidak sepenuhnya menggunakan dataset publik.

Data utama diperoleh melalui **pengujian langsung terhadap SIPESTAR pada lingkungan lokal/testing**.

Skenario pengumpulan data meliputi:

### Normal Traffic

Aktivitas pengguna normal seperti:

* Login
* Booking
* Browsing
* Aktivitas penggunaan sistem lainnya

### Attack Traffic

Simulasi serangan dilakukan secara terkendali menggunakan:

* **Hydra** → Brute Force
* **SQLMap / Payload Manual** → SQL Injection

Aktivitas tersebut kemudian direkam melalui logging untuk menghasilkan data yang digunakan dalam proses feature extraction dan pelabelan.

---

## 🌲 Machine Learning

Algoritma utama yang digunakan dalam penelitian ini adalah:

**Random Forest Classifier**

Evaluasi model dilakukan menggunakan:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Feature Importance

> **Catatan:** Source code dan model Machine Learning akan dikelola pada repository terpisah agar repository skripsi tetap berfokus pada dokumentasi penelitian dan pengembangan sistem.

---

## 📁 Struktur Repository

Struktur repository akan berkembang seiring proses pengerjaan skripsi.

```text
skripsheesh/
│
├── README.md
│
├── docs/
│   ├── proposal/
│   ├── hasil/
│   ├── tutup/
│   └── references/
│
├── diagrams/
│   ├── use-case/
│   ├── activity/
│   ├── flowmap/
│   └── architecture/
```

> Struktur folder di atas dapat berubah menyesuaikan kebutuhan dokumentasi selama proses penelitian.

---

## 🔗 Repository Terkait

Repository ini merupakan bagian dari dua repository utama dalam pengerjaan skripsi:

### 📚 Skripsi & Dokumentasi

Repository ini berisi:

* Dokumen skripsi
* Proposal
* Diagram sistem
* Dokumentasi penelitian
* Berkas pendukung lainnya

### 🤖 Machine Learning Model

Repository terpisah yang berisi komponen teknis Machine Learning, seperti:

* Data preparation
* Feature engineering
* Training
* Evaluation
* Model Random Forest
* Backend inference
* Komponen terkait WIDS

> Link repository ML akan ditambahkan setelah repository tersebut tersedia.

---

## 🗺️ Roadmap

### 📑 Proposal — Bab 1–3

* [ ] Bab 1 — Pendahuluan
* [ ] Bab 2 — Tinjauan Pustaka
* [ ] Bab 3 — Metodologi Penelitian

### 🔬 Hasil Penelitian — Bab 4–5

* [ ] Bab 4 — Hasil dan Pembahasan
* [ ] Bab 5 — Kesimpulan dan Saran

### 🏁 Penutup — Bab 6

* [ ] Bab 6 — Penutup
* [ ] Finalisasi dokumen
* [ ] Sidang Skripsi 💀


---

## 📚 Metodologi

Penelitian menggunakan pendekatan **applied research/rekayasa eksperimental** dengan pendekatan **supervised machine learning**.

Tahapan penelitian secara umum:

1. Identifikasi Masalah
2. Studi Literatur
3. Perancangan Arsitektur Sistem
4. Persiapan dan Pengumpulan Data
5. Ekstraksi Fitur dan Pelabelan Data
6. Pelatihan dan Evaluasi Model
7. Implementasi Sistem
8. Pengujian Sistem dan Analisis Hasil

---

## 📈 Target Akhir

Hasil akhir yang ingin dicapai adalah sebuah **Web Intrusion Detection System (WIDS)** yang dapat:

* Mengidentifikasi traffic normal dan traffic serangan.
* Mengklasifikasikan Brute Force dan SQL Injection.
* Menggunakan model Random Forest sebagai classifier.
* Menampilkan hasil deteksi melalui dashboard monitoring.
* Menyediakan alert hasil deteksi serta laporan berkala.

Dengan demikian, penelitian tidak hanya berhenti pada pembangunan model Machine Learning, tetapi menghasilkan sebuah **end-to-end detection tool** yang terintegrasi dengan SIPESTAR.

---

## ⚠️ Disclaimer

Seluruh aktivitas simulasi serangan dalam penelitian ini dilakukan **secara terkendali pada lingkungan lokal/testing** dan ditujukan untuk kepentingan penelitian.

> *Detect attacks, not your own downfall.* 💀

---

## 👨‍💻 Author

**Belzz Urameshi**

Final Year Student — Information Systems
Bacharuddin Jusuf Habibie Institute of Technology

---

## 📝 Status

> 🚧 **Skripsi ini masih dalam tahap pengerjaan.**

Things may change.

Architecture may change.

The title may change.

The methodology may change.

And most importantly...

**the author may or may not survive. 💀**

---

<p align="center">
  <i>Built with caffeine, questionable sleep schedules, and a questionable amount of debugging.</i>
</p>
