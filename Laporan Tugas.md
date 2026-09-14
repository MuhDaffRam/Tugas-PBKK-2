# Tugas-PBKK-Pertemuan-Ke-2

|    Identity |           Notes            |
| :-------------- |       :-----------------       |
| Nama | Muhammad Daffa Ramadhan    |
| NRP | 5025241216 | 
| Mata Kuliah |     Pemrograman Berbasis Kerangka Kerja        | 
| Kelas | D | 

## 1. Hello World

```cs

Console.WriteLine("Hello, World!");

```

karena versi .net 6 ke atas, Microsoft memperkenalkan fitur yang dinamakan Top-Level Statements.

Dengan fitur ini, saya bisa langsung menuliskan logika utama program secara ringkas tanpa perlu menggunakan static/using system seperti ini:

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
### Source Code

```cs

Console.WriteLine("Hello, World!");

```

### Output yang dihasilkan adalah

<img width="599" height="74" alt="image" src="https://github.com/user-attachments/assets/b07e2765-3e28-42e0-abbb-667a6398bd54" />

untuk run code-nya kita harus gunakan `dotnet run`




