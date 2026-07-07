# Learning Journal - Entri 05
## Analisis Statis & Obfuscation Dasar

**Hari/Tanggal:** Selasa, 7 Juli 2026

### 1. Apa yang Dipelajari
Pada entri kali ini, saya fokus mempelajari dasar-dasar analisis statis menggunakan Ghidra.
Saya belajar bagaimana menavigasi fungsi-fungsi yang terkompilasi tanpa simbol debug.
Langkah awal ini sangat penting untuk memahami dasar pemetaan struktur sebuah biner.

### 2. Tantangan & Solusi
Tantangannya adalah mengenali fungsi utama ketika namanya diubah menjadi generik oleh compiler.
Solusinya adalah mencari referensi string teks seperti petunjuk input pengguna untuk menemukan fungsi utama.
Dengan melacak string tersebut, letak fungsi pemeriksaan awal dapat diisolasi dengan cepat.

### 3. Refleksi Diri
Teknik dasar seperti mengganti nama variabel (renaming) sangat membantu merapikan workspace.
Ini membuat alur pembacaan kode decompiler menjadi jauh lebih manusiawi dan terstruktur.
Pemahaman dasar ini menjadi modal penting sebelum menghadapi biner dengan proteksi lebih ketat.