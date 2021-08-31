# Matrix-Calculator-GUI

Matrix Calculator GUI adalah aplikasi desktop untuk menghitung penjumlahan, pengurangan, perkalian, perkalian skalar dan determinan sebuah matriks. Aplikasi ini dibuat dengan menggunakan Bahasa Pemrograman Python.

## Pratinjau Aplikasi

![](/images/image.png)

## Instalasi

Gunakan pengelola paket [pip](https://pip.pypa.io/en/stable/) untuk menginstal numpy.

```bash
pip install numpy
```

## Pemakaian NumPy

```python
import numpy as np

matrix_a = np.array([1, 2, 3, 4]).reshape(2, 2)
matrix_b = np.array([5, 6, 7, 8]).reshape(2, 2)

matrix_multiplication = np.dot(matrix_a, matrix_b)
matrix_determinant = np.linalg.det(matrix_a)
```

## Libraries
- [Tkinter](https://docs.python.org/3/library/tkinter.html) adalah Python yang mengikat toolkit Tk GUI. Ini adalah antarmuka Python standar ke toolkit Tk GUI, dan GUI standar de facto Python. Tkinter disertakan dengan instalasi Python standar Linux, Microsoft Windows dan Mac OS X. Nama Tkinter berasal dari antarmuka Tk.
- [NumPy](https://numpy.org/) adalah pustaka python yang digunakan untuk bekerja dengan array. Ia juga memiliki fungsi untuk bekerja dalam domain aljabar linier, transformasi fourier, dan matriks. NumPy dibuat pada tahun 2005 oleh Travis Oliphant. Ini adalah proyek open source dan Anda dapat menggunakannya dengan bebas. NumPy adalah singkatan dari Numerical Python.
- [Time](https://docs.python.org/3/library/time.html), Modul waktu Python menyediakan banyak cara untuk merepresentasikan waktu dalam kode, seperti objek, angka, dan string. Ini juga menyediakan fungsionalitas selain mewakili waktu, seperti menunggu selama eksekusi kode dan mengukur efisiensi kode Anda.

## Video Penjelasan 

Video penjelasan tentang Matrix Calculator GUI (Operasi Matriks) dan Demo Programnya dapat dilihat [disini](https://youtu.be/DQyrIqbD0L0).

## Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LISENSI` untuk informasi lebih lanjut.

## Kontak

Mochammad Arya Salsabila - Aryasalsabila789@gmail.com
