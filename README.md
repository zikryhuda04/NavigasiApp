

---

 🧭 NavigasiApp

**NavigasiApp** adalah aplikasi Android sederhana berbasis **Kotlin** yang digunakan untuk mempelajari cara **navigasi antar Activity** menggunakan **Intent**.
Aplikasi ini terdiri dari beberapa halaman yang saling terhubung melalui tombol navigasi.

---

 🎯 Tujuan

* Memahami konsep **Activity** di Android.
* Mempelajari penggunaan **Intent** untuk berpindah antar halaman.
* Mengenal cara kerja navigasi antar layar dalam aplikasi.

---

 🧩 Fitur

* Halaman utama dengan tombol untuk berpindah ke halaman lain.
* Halaman kedua yang menerima data dari halaman pertama.
* Tombol kembali untuk kembali ke halaman utama.
* Navigasi dua arah (maju dan kembali).

---

 🛠️ Teknologi

* **Bahasa:** Kotlin
* **IDE:** Android Studio
* **UI:** XML Layout
* **Minimum SDK:** 24
* **Target SDK:** 34

---

 💡 Alur Kerja

1. Pengguna berada di **MainActivity**.
2. Tekan tombol “Pindah Halaman” untuk menuju **SecondActivity** menggunakan `Intent`.
3. Di **SecondActivity**, pengguna dapat melihat pesan dan menekan tombol kembali ke **MainActivity**.

Contoh kode:

```kotlin
// MainActivity.kt
val intent = Intent(this, SecondActivity::class.java)
startActivity(intent)
```

```kotlin
// SecondActivity.kt
val intent = Intent(this, MainActivity::class.java)
startActivity(intent)
```

---

 🚀 Cara Menjalankan

1. Buka **Android Studio**
2. Pilih **Open an Existing Project** dan buka folder `NavigasiApp`
3. Tunggu proses Gradle selesai
4. Jalankan aplikasi dengan menekan **Run ▶️**

---

 📚 Kesimpulan

**NavigasiApp** membantu memahami dasar navigasi antar Activity di Android menggunakan **Intent**.
Aplikasi ini menjadi dasar untuk pengembangan navigasi yang lebih kompleks seperti **Fragment** atau **Navigation Component**.


