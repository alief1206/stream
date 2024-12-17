# streams

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
3
● Jelaskan fungsi keyword yield* pada kode tersebut!
● Apa maksud isi perintah kode tersebut?
yield* adalah keyword di Dart yang digunakan untuk meneruskan seluruh elemen dari sebuah stream atau iterable ke dalam stream yang sedang dibuat. Fungsinya mirip dengan yield, tetapi alih-alih mengirimkan satu nilai, yield* mem-forward (meneruskan) semua elemen dari stream atau iterable lain.
Jelaskan perbedaan menggunakan listen dan await for!
listen digunakan untuk menangkap event dari stream secara langsung menggunakan callback. Proses ini asinkron, sehingga eksekusi kode di bawahnya tidak terblokir. Setiap event akan diproses saat diterima, tetapi tidak ada jaminan urutan tertentu dalam pemrosesan.await for digunakan untuk memproses setiap event dari stream dalam urutan yang diterima. Proses ini sinkron, sehingga loop akan menunggu hingga setiap event selesai diproses sebelum melanjutkan ke langkah berikutnya.
[![Watch Video](assets/Video%20WhatsApp%202024-12-17%20pukul%2010.44.03_968d3150.gif)]