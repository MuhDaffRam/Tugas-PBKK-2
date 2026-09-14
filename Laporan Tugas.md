# Tugas-PBKK-Pertemuan-Ke-2

|    Identity |           Notes            |
| :--------------: |       :-----------------:       |
| Nama | Muhammad Daffa Ramadhan    |
| NRP | 5025241216 | 
| Mata Kuliah |     Pemrograman Berbasis Kerangka Kerja        | 
| Kelas | D | 

## 1. Hello World

```cs

Console.WriteLine("Hello, World!");

```

karena versi .net 6 ke atas, Microsoft memperkenalkan fitur yang dinamakan Top-Level Statements.

Dengan fitur ini, kamu bisa langsung menuliskan logika utama program secara ringkas tanpa perlu lagi membuat pembungkus dasar seperti:

```cs

// Kode gaya LAMA (sebelum .NET 6)
using System;

namespace contohAja
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}

```
