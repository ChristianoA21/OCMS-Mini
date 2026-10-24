# 🚀 OCMS-Mini

**OCMS-Mini** adalah proyek perangkat lunak sederhana yang dibangun menggunakan **100% Java**. Proyek ini dibuat sebagai landasan fundamental untuk tugas mata kuliah **Pemrograman Berorientasi Objek (PBO) Semester 1**.

Tujuan utama dari proyek ini adalah untuk mengimplementasikan dasar-dasar logika pemrograman serta konsep inti dari paradigma *Object-Oriented Programming* (OOP) dalam bahasa Java.

---

## 📚 Konsep PBO yang Diterapkan
Karena proyek ini ditujukan untuk pembelajaran semester 1, pengembangan kode berfokus pada implementasi:
1. **Class & Object:** Pembuatan kerangka kerja (*blueprint*) dan instansiasi entitas.
2. **Encapsulation:** Mengamankan data menggunakan *access modifier* (`private`, `protected`, `public`) dan memanfaatkan metode *getter/setter*.
3. **Inheritance:** Pewarisan atribut dan metode dari kelas induk (*superclass*) ke kelas anak (*subclass*).
4. **Polymorphism:** Menerapkan *overloading* dan *overriding* untuk fleksibilitas perilaku objek.

---

## 📂 Struktur Proyek
Repositori ini dikembangkan menggunakan **Apache NetBeans** dan dibangun dengan **Ant**. Berikut adalah struktur utama dari proyek ini[cite: 1]:

- `src/ocms/mini/` : Direktori utama tempat semua *source code* (kode sumber) Java disimpan[cite: 1].
- `nbproject/` : Folder berisi konfigurasi bawaan dari IDE NetBeans agar proyek mudah dibuka kembali[cite: 1].
- `build.xml` : File konfigurasi *build* bawaan Apache Ant untuk mengompilasi program[cite: 1].
- `manifest.mf` : File metadata standar Java untuk keperluan *packaging* (*build*) ke format JAR[cite: 1].
- `.gitignore` : Berfungsi untuk mencegah file *build* atau konfigurasi lokal yang tidak perlu agar tidak masuk ke dalam repositori Git[cite: 1].

---

## 🛠️ Persyaratan Sistem (*Prerequisites*)
Untuk menjalankan proyek ini di komputer lokal, pastikan Anda telah menginstal:
- **Java Development Kit (JDK)** (disarankan JDK 8 ke atas)
- **Apache NetBeans IDE** (Sangat direkomendasikan karena proyek ini sudah memuat konfigurasi `nbproject` dan
