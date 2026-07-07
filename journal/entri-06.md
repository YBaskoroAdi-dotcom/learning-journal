# Learning Journal - Entri 06
## Teknik Reverse Engineering & Pembuatan Keygen

**Hari/Tanggal:** Selasa, 7 Juli 2026

### 1. Apa yang Dipelajari
Saya melakukan rekayasa balik pada biner 'Untitled3.exe' yang memiliki tingkat kesulitan 2.2.
Di sini saya membedah algoritma loop validasi password berbasis perhitungan nilai ASCII.
Setiap karakter username dikalikan dengan 4 dan diakumulasikan sebagai checksum password.

### 2. Tantangan & Solusi
Tantangannya adalah memahami representasi bitwise shift left di assembly yang bermakna perkalian.
Solusinya adalah mencocokkannya dengan panel decompiler Ghidra yang menampilkan operasi perkalian secara eksplisit.
Saya berhasil membuktikannya secara nyata dengan kombinasi input 'abcd' dan password '1576'.

### 3. Refleksi Diri
Berhasil membuat script keygen berbasis Python memberikan pemahaman baru tentang matematika biner.
Proses dekonstruksi logika loop C++ ini melatih ketelitian saya dalam membaca manipulasi buffer memori.
Sekarang saya lebih percaya diri dalam melakukan reverse engineering pada skema lisensi sederhana.