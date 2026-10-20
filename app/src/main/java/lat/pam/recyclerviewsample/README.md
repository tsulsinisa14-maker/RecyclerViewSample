# RecyclerView Sample 📱

Aplikasi Android sederhana berbasis **Kotlin** yang menampilkan daftar item (*list*) secara efisien dan dinamis menggunakan komponen **RecyclerView**.

---

## 📱 Tampilan Aplikasi (Preview)

<p align="center">
  <img src="screenshots/img.png" alt="RecyclerView Sample Preview" width="320" />
</p>

---

## 🛠️ Fitur & Spesifikasi Utama

- **RecyclerView**: Menampilkan daftar item secara fleksibel dan efisien.
- **Custom Adapter**: Menggunakan `CustomAdapter` untuk mengikat data ke tampilan item.
- **Model-View Architecture**: Pemisahan logika data menggunakan model `ItemsViewModel`.
- **Kotlin Native**: Seluruh logika aplikasi ditulis menggunakan bahasa pemrograman Kotlin.
- **ConstraintLayout & CardView**: Antarmuka yang responsif dengan tampilan kartu (*card design*).

---

## 📂 Struktur Berkas Penting

`lat.pam.recyclerviewsample`
- `MainActivity.kt` — Activity utama tempat inisialisasi layout manager, data list, dan adapter.
- `CustomAdapter.kt` — Adapter khusus untuk mengelola ViewHolder dan menghubungkan data dengan item layout.
- `ItemsViewModel.kt` — Model data untuk mendefinisikan properti objek item list.
- `activity_main.xml` — Layout utama yang memuat komponen `RecyclerView`.
- `card_view_design.xml` — Layout khusus untuk mendefinisikan tampilan tiap kartu/item.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone Repositori Ini**:
   ```bash
   git clone [https://github.com/username-kamu/RecyclerViewSample.git](https://github.com/username-kamu/RecyclerViewSample.git)