# Tugas-Pertemuan-1-Bigdata

Ivan Syarifuddin - 5027241045

---

## 1. Identifikasi Sumber Data Big Data
Dalam ekosistem pariwisata modern, data tidak lagi hanya berasal dari buku tamu hotel, melainkan dari berbagai sumber digital yang masif:

1.  **User-Generated Content (UGC):** Data tidak terstruktur yang berasal dari media sosial (Instagram, TikTok), ulasan di platform seperti TripAdvisor/Google Maps, serta blog perjalanan. Ini mencakup teks, foto, dan video.
2.  **Data Transaksional Digital:** Data dari *Online Travel Agencies* (OTA) seperti Traveloka atau Airbnb, sistem reservasi maskapai (GDS), dan log transaksi kartu kredit wisatawan.
3.  **Data Sensor & Perangkat Bergerak (IoT):** Data log dari penyedia layanan telekomunikasi (roaming), koordinat GPS dari aplikasi peta, serta sensor *crowd counting* di area publik atau objek wisata.

---

## 2. Implementasi Konsep 5V
Karakteristik data dalam industri pariwisata memenuhi lima pilar utama Big Data:

* **Volume:** Jutaan pencarian tiket dan unggahan foto setiap jam menghasilkan data berukuran Terabyte hingga Petabyte yang memerlukan penyimpanan skala besar.
* **Velocity:** Data mengalir secara *real-time*. Misalnya, perubahan harga tiket pesawat yang berfluktuasi tiap detik berdasarkan permintaan atau arus pergerakan orang di bandara.
* **Variety:** Data hadir dalam format yang sangat beragam: **Terstruktur** (data identitas paspor/tiket), **Semi-terstruktur** (log file web), dan **Tidak terstruktur** (ulasan teks dan video promosi).
* **Veracity:** Tantangan dalam memastikan keaslian ulasan (menghindari *fake reviews*) serta akurasi data lokasi agar keputusan yang diambil tidak bias.
* **Value:** Data hanya akan bernilai jika mampu memberikan wawasan untuk meningkatkan jumlah kunjungan atau efisiensi operasional destinasi wisata.

---

## 3. Potensi Value yang Dihasilkan
Pemanfaatan Big Data melalui arsitektur seperti **Data Lakehouse** memungkinkan industri pariwisata menghasilkan nilai strategis berikut:

* **Hyper-Personalization:** Memberikan rekomendasi destinasi dan promo hotel yang sangat personal berdasarkan perilaku digital dan preferensi unik setiap wisatawan.
* **Dynamic Pricing:** Maskapai dan pengelola hotel dapat menyesuaikan harga secara otomatis berdasarkan tren pasar, cuaca, dan acara besar (event) yang terdeteksi dari data eksternal.
* **Smart Destination Management:** Pemerintah dapat memprediksi lonjakan wisatawan (peak season) untuk mengatur lalu lintas, ketersediaan energi, dan manajemen sampah guna mencegah kerusakan lingkungan akibat *overtourism*.

---

## 4. Tantangan dalam Pengelolaan Data
Meskipun potensinya besar, terdapat beberapa hambatan utama:

* **Privasi dan Keamanan:** Melindungi data sensitif (PII - *Personally Identifiable Information*) seperti data paspor dan kartu kredit dari ancaman siber.
* **Integrasi Data (Data Silos):** Data tersebar di berbagai organisasi (maskapai, imigrasi, hotel). Menyatukan data tersebut ke dalam satu platform tunggal (seperti Lakehouse) memerlukan koordinasi teknis dan hukum yang rumit.
* **Kualitas Data:** Mengolah data yang "kotor" atau tidak lengkap dari berbagai sumber agar tetap bisa digunakan untuk model analisis prediktif yang akurat.

---

## Kesimpulan
Industri pariwisata adalah kandidat utama untuk implementasi **Data Lakehouse**. Dengan kemampuan menyimpan data tidak terstruktur (foto/ulasan) sekaligus mendukung analisis data terstruktur (transaksi) secara cepat, teknologi ini memungkinkan pelaku industri untuk lebih adaptif terhadap perubahan perilaku wisatawan di era digital.
