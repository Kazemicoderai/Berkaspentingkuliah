# Berkaspentingkuliah
# Portfolio – Amogus

Selamat datang di portofolio sederhana saya! Portfolio ini dibuat sebagai bagian dari pendaftaran **Divisi Research and Development (R&D) HIMTIKA**. Saya masih dalam tahap belajar, terutama dalam web development dan pemrograman dasar, namun saya terus berusaha mengembangkan kemampuan melalui project sederhana.

---

## 👨‍💻 Tentang Saya
- **Nama:** Amogus
- **Prodi:** Informatika
- **Ketertarikan:** Web Development, Sistem Informasi sederhana, dan automation untuk pencatatan/progress.
- **Skill Saat Ini:**
  - HTML & CSS dasar
  - JavaScript dasar
  - C++ dasar
  - Paham alur program (dibantu AI untuk generasi awal, tapi saya memahami logikanya)

---

## 🚀 Tujuan Saya Bergabung R&D
- Mendapat pengalaman baru di dunia programming.
- Meningkatkan kemampuan web development.
- Belajar bekerja dalam tim dan mengerjakan project nyata.
- Membiasakan diri dengan workflow developer (GitHub, dokumentasi, debugging).

---

## 📂 Project Sederhana
Berikut merupakan beberapa project sederhana yang relevan dengan Divisi RnD.

---

### 1. **Simple Web – Sistem Pencatatan Progress**
Project web HTML/CSS sederhana untuk mencatat progress kegiatan. Cocok untuk internal divisi atau pencatatan tugas.

**Fitur:**
- Input nama kegiatan
- Input persentase progress
- Tabel daftar progress

**Demo Code (HTML/CSS/JS):**
```
<!DOCTYPE html>
<html>
<head>
    <title>Progress Tracker</title>
    <style>
        body { font-family: Arial; padding: 20px; }
        input, button { padding: 8px; margin: 5px; }
        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { border: 1px solid #ccc; padding: 10px; }
    </style>
</head>
<body>
    <h2>Progress Tracker</h2>
    <input type="text" id="task" placeholder="Nama kegiatan">
    <input type="number" id="progress" placeholder="Progress (%)">
    <button onclick="addData()">Tambah</button>

    <table>
        <thead>
            <tr>
                <th>Kegiatan</th>
                <th>Progress</th>
            </tr>
        </thead>
        <tbody id="tableBody"></tbody>
    </table>

    <script>
        function addData(){
            let task = document.getElementById('task').value;
            let progress = document.getElementById('progress').value;
            
            let row = `<tr><td>${task}</td><td>${progress}%</td></tr>`;
            document.getElementById('tableBody').innerHTML += row;
        }
    </script>
</body>
</html>
```

---

### 2. **C++ Program – Sistem Kasir Sederhana**
Program dasar untuk mencatat transaksi.
```
#include <iostream>
using namespace std;

int main(){
    int harga, jumlah;
    string nama;

    cout << "Nama barang: "; cin >> nama;
    cout << "Harga: "; cin >> harga;
    cout << "Jumlah: "; cin >> jumlah;

    cout << "Total: " << harga * jumlah;
}
```
---
## 🔗 Link GitHub
Semua file, project, dan kode saya upload ke GitHub:

👉 **https://github.com/your-username/portfolio-rnd**

*(Ganti dengan link GitHub kamu)*

---

## 📌 Penutup
Portofolio ini masih sederhana, namun saya berkomitmen untuk terus belajar dan tumbuh bersama Divisi R&D. Terima kasih telah melihat portofolio saya.
