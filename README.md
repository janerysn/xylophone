## Xylophone 🎹

Aplikasi membunyikan suara dari TextButton warna-warni
Uji Aplikasi<br>
1.	Jalankan aplikasi (flutter run).<br>
 <img src ="https://github.com/user-attachments/assets/61966467-968c-407f-8a87-016fa692356e" width= "400px"><br>
2.	Penjelasan.<br>
Aplikasi Xylophone App dibuat menggunakan Flutter. Aplikasi ini menampilkan tujuh tombol warna-warni yang masing-masing akan memainkan suara berbeda saat ditekan, menyerupai alat musik xylophone.
Komponen utama aplikasi:
- XylophoneApp adalah root widget aplikasi.
- Fungsi playSound(int soundNumber) digunakan untuk memutar file audio lokal yang disimpan di folder asset, dengan format nama noteX.wav sesuai nomor tombol.
- Fungsi buildKey() digunakan untuk membangun setiap tombol berwarna. Tombol-tombol ini diletakkan dalam Column yang memenuhi layar secara vertikal.
- Ketika pengguna menekan tombol, playSound() akan dipanggil dan memainkan suara sesuai dengan soundNumber yang dipilih.
Aplikasi ini menggunakan package audioplayers untuk memutar file audio.
