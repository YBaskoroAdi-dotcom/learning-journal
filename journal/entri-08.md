# Learning Journal - Entri 08
## Eksploitasi, Tracing, dan Dekripsi Flag

**Hari/Tanggal:** Selasa, 7 Juli 2026

### 1. Apa yang Dipelajari
Melanjutkan analisis biner level Hard, fokus kali ini adalah ekstraksi kunci dan flag.
Saya menganalisis instruksi khusus assembly seperti 'INSB' dan 'SCASB' di fungsi utama.
Instruksi tersebut digunakan untuk memanipulasi buffer memori dan mendekripsi string secara dinamis.

### 2. Tantangan & Solusi
Tantangannya adalah menemukan visualisasi dan kecocokan algoritma enkripsi biner yang rumit.
Dengan melakukan dekonstruksi fungsi, ditemukan kunci valid yaitu 'xQ9_vP4_tK2_mZ8'.
Ketika dieksekusi di Command Prompt, kunci tersebut sukses memunculkan decrypted flag asli.

### 3. Refleksi Diri
Menyelesaikan target level 5.0 ini memberikan lompatan besar dalam pemahaman reverse engineering saya.
Saya menyadari bahwa dokumentasi error dan alur runtime biner sangat krusial untuk validasi hasil.
Jurnal ini menutup rangkaian tugas dengan pemahaman komprehensif dari tingkat dasar hingga mahir.