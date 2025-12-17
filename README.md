# 🍎 Kaloriku - Aplikasi Kalkulator Kalori Makanan

**Kaloriku** adalah aplikasi desktop berbasis Python yang dirancang untuk membantu pengguna menghitung total kalori dari sebuah resep atau menu makanan. Aplikasi ini memiliki antarmuka grafis (GUI) yang user-friendly, visualisasi data gizi, serta fitur laporan ke Excel.

---

## 👤 Informasi Pengembang
* **Nama:** brawidya

---

## ✨ Fitur Utama

1.  **🔐 Sistem Login Sederhana**
    * Keamanan akses awal sebelum masuk ke menu utama.
2.  **📝 Input Bahan Makanan Baru**
    * Menambahkan database bahan makanan secara dinamis (Nama, Kategori, Kalori per 100g).
3.  **🍳 Kalkulator Resep & Kalori**
    * Memilih bahan dari database.
    * Mengatur berat (gram) menggunakan slider.
    * Menghitung total kalori secara otomatis.
4.  **📊 Visualisasi Data (Chart)**
    * **Pie Chart:** Persentase komposisi kategori makanan (Karbohidrat, Protein, Sayur, dll).
    * **Bar Chart:** Perbandingan jumlah kalori per kategori.
5.  **💾 Export Laporan ke Excel**
    * Menyimpan tabel resep ke file `.xlsx`.
    * Secara otomatis menyertakan grafik visualisasi ke dalam file Excel.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan **Python** dengan pustaka berikut:

* **Tkinter:** Untuk membangun antarmuka pengguna (GUI).
* **Pandas:** Untuk manipulasi data dan ekspor ke Excel.
* **Matplotlib:** Untuk membuat grafik visualisasi data.
* **OpenPyXL:** Engine untuk menulis file Excel.

---

## ⚙️ Cara Instalasi dan Menjalankan

### 1. Prasyarat
Pastikan Python sudah terinstal di komputer Anda. Kemudian, instal library eksternal yang dibutuhkan melalui terminal/CMD:

```bash
pip install pandas matplotlib openpyxl
