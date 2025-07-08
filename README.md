
# 🚿 Dispenser Sabun Otomatis dengan Arduino

Proyek ini adalah dispenser sabun otomatis yang dirancang menggunakan **Arduino UNO**, dua buah **sensor ultrasonik**, **LCD I2C**, **LED indikator**, dan **pompa DC**. Sistem ini mampu mendeteksi tangan pengguna dan mengeluarkan sabun secara otomatis, sekaligus memantau level sabun yang tersisa.

## 🛠️ Fitur Utama
- ✋ Deteksi tangan otomatis menggunakan sensor HC-SR04
- 🧼 Pemberian sabun otomatis melalui pompa DC
- 📊 Monitoring level sabun secara real-time
- 📟 Tampilan status dan indikator bar di LCD I2C 16x2
- 🔴 LED merah untuk sabun habis, 🟢 LED hijau untuk sabun tersedia
- ⏱️ Sistem cooldown untuk mencegah pemberian sabun berulang dalam waktu dekat

## 💡 Komponen yang Digunakan
- Arduino UNO
- 2x Sensor Ultrasonik HC-SR04
- LCD I2C 16x2
- Pompa DC mini (disarankan dengan relay atau MOSFET)
- LED merah dan hijau
- Breadboard, kabel jumper, resistor

## 📐 Kalibrasi Level Sabun
Level sabun diukur dari jarak 5.0 cm (kosong) hingga 14.5 cm (penuh). Nilai ini bisa disesuaikan dengan ukuran botol atau wadah sabun yang digunakan.

## 🚀 Cara Menggunakan
1. Hubungkan semua komponen sesuai dengan pin yang didefinisikan dalam kode.
2. Upload file `dispenser_sabun_otomatis_fixed.ino` ke Arduino IDE.
3. Nyalakan sistem, pastikan LCD menyala dan sensor bekerja.
4. Sistem akan otomatis mendeteksi tangan dan memberikan sabun jika tersedia.

## 📁 File
- `dispenser_sabun_otomatis_fixed.ino`: kode lengkap Arduino
- `README.md`: dokumentasi proyek ini

## 🧠 Catatan
Proyek ini cocok sebagai demonstrasi sistem otomatis berbasis sensor dan kontrol mikrokontroler sederhana. Cocok untuk mahasiswa yang tertarik di bidang **IoT**, **embedded systems**, dan **otomatisasi rumah tangga**.

---

Created by **Abil Fidaa Ismail**  
For educational and demonstration purposes.
