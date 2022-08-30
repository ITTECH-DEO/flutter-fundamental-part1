# 6. Praktikum 1: Membuat Project Flutter Baru

Selesaikan langkah-langkah praktikum berikut ini menggunakan editor Visual Studio Code (VS Code) atau Android Studio atau code editor lain kesukaan Anda.

**Langkah 1:**

Buka VS Code, lalu tekan tombol **Ctrl + Shift + P** maka akan tampil *Command Palette*, lalu ketik **Flutter**. Pilih **New Application Project**.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.001.png)
## **Langkah 2:**
Kemudian buat folder **TSA** di mana pun yang Anda suka. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang tidak terlalu dalam atau panjang. Lalu pilih **Select a folder to create the project in**.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.002.png)
## **Langkah 3:**
Buat nama project flutter **hello\_world** seperti berikut, lalu tekan **Enter**. Tunggu hingga proses pembuatan project baru selesai.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.003.png)
## **Langkah 4:**
Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "**Your Flutter Project is ready!**" artinya Anda telah berhasil membuat project Flutter baru.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.004.png)

















## 7. Praktikum 2: Membuat Repository GitHub dan Laporan Praktikum
## **Langkah 1:**
Login ke akun [GitHub](https://github.com/new) Anda, lalu buat repository baru dengan nama "**flutter-fundamental-part1**"

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.005.png)
## **Langkah 2:**
Lalu klik tombol "**Create repository**" lalu akan tampil seperti gambar berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.006.png)
## **Langkah 3:**
Kembali ke VS code, project flutter hello\_world, buka terminal pada menu **Terminal > New Terminal**. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.007.png)
## **Langkah 4:**
Pilih menu **Source Control** di bagian kiri, lalu lakukan **stages** (+) pada file **.gitignore** untuk mengunggah file pertama ke repository GitHub.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.008.png)
## **Langkah 5:**
Beri pesan commit "**tambah gitignore**" lalu klik **Commit** (✔)

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.009.png)
## **Langkah 6:**
Lakukan push dengan klik bagian menu titik tiga > **Push**

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.010.png)
## **Langkah 7:**
Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "**Add Remote**"

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.011.png)
## **Langkah 8:**
Salin tautan repository Anda dari browser ke bagian ini, lalu klik **Add remote**

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.012.png)

Setelah berhasil, tulis remote name dengan "**origin**"

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.013.png)
## **Langkah 9:**
Lakukan hal yang sama pada file **README.md** mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.014.png)
## **Langkah 10:**
Lakukan push juga untuk semua file lainnya dengan pilih **Stage All Changes**. Beri pesan commit "**project hello\_world**". Maka akan tampil di repository GitHub Anda seperti berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.015.png)
## **Langkah 11:**
Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project **hello\_world** dengan tekan **F5** atau **Run > Start Debugging**. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.016.png)
## **Langkah 12:**
Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama **01.png** pada folder **images** (buat folder baru jika belum ada) di project hello\_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.017.png)
















## 8. Praktikum 3: Menerapkan Widget Dasar
Selesaikan langkah-langkah praktikum berikut ini dengan melanjutkan dari praktikum sebelumnya.
## **Langkah 1: Text Widget**
Buat folder baru **basic\_widgets** di dalam folder **lib**. Kemudian buat file baru di dalam basic\_widgets dengan nama text\_widget.dart. Ketik atau salin kode program berikut ke project hello\_world Anda pada file text\_widget.dart.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.018.png)

Lakukan import file text\_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.019.png)
## **Langkah 2: Image Widget**
Buat sebuah file image\_widget.dart di dalam folder basic\_widgets dengan isi kode berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.020.png)

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello\_world.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.021.png)

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.022.png)

## 9. Praktikum 4: Menerapkan Widget Material Design dan iOS Cupertino
Selesaikan langkah-langkah praktikum berikut ini dengan melanjutkan project hello\_world Anda. Lakukan langkah yang sama seperti pada Praktikum 3, yaitu setiap widget dibuat file sendiri lalu import ke main.dart dan screenshot hasilnya.
## **Langkah 1: Cupertino Button dan Loading Bar**
Buat file di basic\_widgets > loading\_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.023.png)
## **Langkah 2: Floating Action Button (FAB)**
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.

Buat file di basic\_widgets > fab\_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.024.png)
## **Langkah 3: Scaffold Widget**
Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.

Ubah isi kode main.dart seperti berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.025.png)
## **Langkah 4: Dialog Widget**
Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.

Ubah isi kode main.dart seperti berikut.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.026.png)
## **Langkah 5: Input dan Selection Widget**
Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

Contoh penggunaan TextField widget adalah sebagai berikut:

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.027.png)
## **Langkah 6: Date and Time Pickers**
Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

![](Aspose.Words.992a36f7-07c2-4716-90bc-084a626bc3ed.028.png)

# Tugas Praktikum
1. Selesaikan Praktikum 1 sampai 4, lalu dokumentasikan dan push ke repository Anda berupa screenshot setiap hasil pekerjaan beserta penjelasannya di file README.md!
![](images/Tugas1.png)


2. Pada praktikum 4 mulai dari Langkah 3 sampai 6, buatlah file widget tersendiri di folder basic_widgets, kemudian pada file main.dart cukup melakukan import widget sesuai masing-masing langkah tersebut!
![](images/Tugas2.png)

3. Kumpulkan berupa link repository GitHub Anda ke LMS yang telah dibuat berdasarkan pada Praktikum 2!





