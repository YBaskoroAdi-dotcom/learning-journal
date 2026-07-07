# Learning Journal - Entri 07
## Menghadapi Proteksi Anti-Disassembly Tingkat Lanjut

**Hari/Tanggal:** Selasa, 7 Juli 2026

### 1. Apa yang Dipelajari
Saya menganalisis biner 'mbb.exe' dari tantangan 'High cortisol' dengan tingkat kesulitan 5.0.
Saya mempelajari bagaimana pembuat tantangan mengacaukan pembacaan alat bantu disassembler.
Terdapat instruksi khusus tingkat rendah yang sengaja disisipkan untuk memecah alur kendali program.

### 2. Tantangan & Solusi
Ghidra memunculkan peringatan 'Control flow encountered bad instruction data' saat membuka file.
Hal ini membuat panel decompiler tidak dapat menerjemahkan fungsi secara utuh dan bersih.
Solusinya adalah melakukan analisis cross-reference (XREF) untuk memetakan hotspot fungsi inti.

### 3. Refleksi Diri
Menghadapi proteksi biner tingkat tinggi mengajarkan saya untuk tidak hanya bergantung pada decompiler otomatis.
Kemampuan membaca instruksi mesin secara manual di panel listing menjadi penyelamat dalam situasi ini.
Analisis ini memperluas wawasan saya mengenai teknik anti-analysis yang sering digunakan oleh malware.