# Navio App - Praktikum Mobile Programming #4

Aplikasi ini dikembangkan sebagai bagian dari tugas **Praktikum Mobile Programming 20251**. Fokus utama dari proyek ini adalah implementasi sistem navigasi modern pada Android menggunakan **Jetpack Compose Navigation**, pengelolaan **Back Stack**, serta penggunaan **Intent**.

## 👤 Identitas Pengembang
- **Nama:** Mahmudah
- **NIM:** 230104040220
- **Mata Kuliah:** Mobile Programming

## 🚀 Fitur Utama
Aplikasi ini mencakup berbagai skenario navigasi, antara lain:
1. **Explicit Intent:** Berpindah antar Activity (Activity A & B) secara eksplisit.
2. **Send Data (Intent Extras):** Mengirim dan menampilkan data (Name & Student ID) antar halaman.
3. **Back Stack Management:** Demonstrasi bagaimana Android mengelola tumpukan Activity (Step 1, 2, dan 3).
4. **Hub Navigation (Activity + Fragment):** Implementasi Bottom Navigation yang mengombinasikan Activity dengan Fragment menggunakan struktur modular.
5. **Jetpack Compose Navigation:** Menggunakan `NavHost`, `NavController`, dan `Composable` routes untuk alur navigasi yang efisien.

## 🛠️ Teknologi yang Digunakan
- **Bahasa:** Kotlin
- **Toolkit UI:** Jetpack Compose
- **Navigasi:** Jetpack Navigation Component
- **Design System:** Material Design 3 (MD3)
- **Tools:** Android Studio

## 📁 Struktur Folder Utama
- `nav/`: Berisi file navigasi utama seperti `NavGraph.kt` dan `Routes.kt`.
- `screens/`: Berisi UI Composable untuk setiap layar aplikasi (Home, Activity screens, Step screens).
- `MainActivity.kt`: Entry point utama aplikasi yang memanggil `NavGraph`.

## 📸 Cuplikan Layar
*(Anda bisa menambahkan screenshot aplikasi "Navio" di sini sesuai hasil praktikum)*
- **Homescreen:** Menampilkan menu navigasi utama.
- **Send Data:** Form pengiriman data menggunakan Intent.
- **Step Screens:** Demonstrasi alur Back Stack.

---
*Dibuat untuk memenuhi tugas Modul Praktikum #4 - Menggunakan Navigasi Aplikasi.*
