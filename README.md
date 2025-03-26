# **Software Quality Assurance (SQA) Project**  
**Penggunaan GitHub dalam Pengujian dan Pengukuran Kualitas Perangkat Lunak**  

## 📌 **Deskripsi Proyek**  
Proyek ini bertujuan untuk memastikan kualitas perangkat lunak melalui pengujian yang sistematis dan terstruktur.  
Repository ini berisi berbagai dokumen penting yang digunakan dalam proses *Software Quality Assurance (SQA)*, termasuk:  

- 📌 **Rencana Pengujian (*Test Plan*)** – Strategi dan cakupan pengujian dalam proyek.  
- 📌 **Kasus Uji (*Test Cases*)** – Daftar skenario pengujian untuk memastikan perangkat lunak bekerja sesuai harapan.  
- 📌 **Laporan Bug (*Bug Report*)** – Dokumentasi kesalahan atau masalah yang ditemukan selama pengujian.  

---

## 📂 **Struktur Repository**  
```
📁 SQA-Project
│── 📁 Documents  
│   │── 📝 Test_Plan.md       # Rencana pengujian proyek  
│   │── 📝 Test_Cases.xlsx    # Daftar skenario uji dalam format spreadsheet  
│   │── 📝 Bug_Report.md      # Laporan bug yang ditemukan selama pengujian  
│
│── 📁 Scripts  
│   │── 🖥️ automation_test.py  # Skrip otomatisasi pengujian  
│   │── 🖥️ performance_test.sh # Skrip pengujian performa  
│
│── 📁 Reports  
│   │── 📊 test_results.md    # Laporan hasil pengujian  
│   │── 📊 bug_tracking.md    # Daftar bug yang telah diatasi  
│
│── 📁 .github  
│   │── 📁 ISSUE_TEMPLATE  
│   │   │── 📝 bug_report.md  # Template laporan bug untuk GitHub Issues  
│   │── 📁 workflows  
│   │   │── ⚙️ test.yml       # Workflow otomatisasi pengujian dengan GitHub Actions  
│
│── 📄 README.md             # Dokumentasi proyek  
│── 📄 CONTRIBUTING.md       # Panduan kontribusi untuk tim  
│── 📄 LICENSE              # Lisensi proyek  
```

---

## 🚀 **Cara Menggunakan Repository Ini**  

1️⃣ **Fork repository ini ke akun GitHub.**  
2️⃣ **Clone repository ke komputer lokal:**  
   ```sh
   git clone https://github.com/tiarapld/Tubes-SQ.git
   ```  
3️⃣ **Buat branch baru untuk pekerjaan:**  
   ```sh
   git checkout -b feature/uji-fitur
   ```  
4️⃣ **Lakukan perubahan dan commit dengan pesan yang jelas:**  
   ```sh
   git add .
   git commit -m "Menambahkan test case untuk fitur login"
   ```  
5️⃣ **Push branch ke repository:**  
   ```sh
   git push origin feature/uji-fitur
   ```  
6️⃣ **Buat Pull Request (PR) untuk ditinjau oleh tim.**  
7️⃣ **Setelah direview, merge ke `main` dan hapus branch jika tidak diperlukan lagi.**  

---

## 📌 **Disclaimer**  
Repositori ini adalah versi terjemahan dan adaptasi dari proyek **TUBES SQ** yang direferensikan dari [https://github.com/tiarapld/Tubes-SQ](https://github.com/tiarapld/Tubes-SQ).  
Semua kontribusi harus melalui akun GitHub ini.  
Terima kasih kepada semua kontributor dari proyek referensi. 🙌  

