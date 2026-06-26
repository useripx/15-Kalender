<div align="center">

# 📅 Kalender GUI

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-blue?style=for-the-badge&logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Repo Size](https://img.shields.io/github/repo-size/useripx/15-Kalender?style=for-the-badge&color=blue)
![License](https://img.shields.io/badge/License-Free-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Selesai-brightgreen?style=for-the-badge)
![Semester](https://img.shields.io/badge/Semester-1-blueviolet?style=for-the-badge)

**Aplikasi widget Kalender interaktif berbasis Graphical User Interface (GUI) menggunakan Tkinter dan tkcalendar.**

*Dibuat oleh Yogi Ario — Proyek Semester 1*

---

</div>

## 📖 Deskripsi

**Kalender GUI** adalah proyek Python sederhana yang mendemonstrasikan pembuatan antarmuka pengguna interaktif (GUI) berupa Widget Kalender. Dengan menggunakan kombinasi modul standar `tkinter` dan library eksternal `tkcalendar`, aplikasi ini memungkinkan pengguna untuk melihat kalender bulanan, memilih hari, dan menampilkan tanggal yang dipilih pada layar.

Proyek ini sangat berguna sebagai dasar untuk aplikasi yang lebih kompleks, seperti aplikasi pemesanan tiket, daftar tugas (To-Do List), atau manajemen jadwal.

## ✨ Fitur Utama

- 📆 **Interactive Calendar** — Menampilkan kalender visual yang bisa di-klik.
- 👆 **Date Picker** — Memilih tanggal tertentu (hari, bulan, tahun).
- 🏷️ **Display Selection** — Menampilkan tanggal yang telah dipilih pada teks label di bawah kalender.
- 🖥️ **Tampilan GUI Minimalis** — Antarmuka yang bersih dan fokus pada fungsionalitas inti.

## 📁 Struktur Proyek

```
15 Kalender/
├── cal.py          # Script utama aplikasi Kalender GUI
└── cale.py         # Script alternatif (versi serupa dengan label teks sedikit berbeda)
```

## 🚀 Cara Menjalankan

### Prasyarat Instalasi

Aplikasi ini menggunakan modul `tkcalendar` yang bukan merupakan library bawaan Python. Anda harus menginstalnya terlebih dahulu menggunakan PIP:

```bash
pip install tkcalendar
```
*(Catatan: modul `tkinter` sudah terpasang secara default pada instalasi Python standar).*

### Menjalankan Program

Jalankan salah satu dari dua file Python berikut di terminal:

```bash
python cal.py
```
atau
```bash
python cale.py
```

Setelah dijalankan, sebuah jendela GUI akan muncul menampilkan kalender. 
1. Klik pada hari/tanggal yang Anda inginkan.
2. Klik tombol **"Show Date"**.
3. Tanggal yang Anda pilih akan muncul di bawah tombol.

## 📸 Ilustrasi Antarmuka GUI

```text
┌──────────────────────────────────────┐
│             Kalender GUI             │
│                                      │
│      <         Mei 2024         >    │
│   Sen Sel Rab Kam Jum Sab Min        │
│    29  30   1   2   3   4   5        │
│     6   7   8   9  10  11  12        │
│    13  14  15  16  17  18  19        │
│    20  21  22 [23] 24  25  26        │
│    27  28  29  30  31   1   2        │
│                                      │
│           [ Show Date ]              │
│                                      │
│      Selected Date: 5/23/24          │
│                                      │
│             Yogi Ario                │
└──────────────────────────────────────┘
```

## 🛠️ Teknologi

| Komponen | Detail |
|----------|--------|
| Bahasa | Python 3.x |
| GUI Framework | `tkinter` (Built-in) |
| Widget Extension | `tkcalendar` |
| Komponen UI | `Label`, `Button`, `Calendar` |

## 👤 Author & Kontak

**Yogi Ario Pratama**

Jika Anda memiliki pertanyaan seputar kode ini atau ingin berdiskusi, silakan hubungi saya melalui WhatsApp:
📱 **[Chat via WhatsApp (wa.me/6281358113087)](https://wa.me/6281358113087)**

---

### 💖 Donasi
Dukungan Anda sangat berarti agar saya dapat terus semangat belajar dan mengembangkan proyek-proyek open-source lainnya. Jika berkenan memberikan donasi/apresiasi, Anda dapat menyalurkannya melalui:

💳 **Bank Seabank**
- No Rekening: **901497113744**
- Atas Nama: **Yogi Ario Pratama**

<div align="center">
  <br>
  <em>Terima kasih atas kunjungannya. Proyek Mata Kuliah — Semester 1 — Teknik Informatika UNP</em>
</div>

