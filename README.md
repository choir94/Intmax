# Intmax mining-cli  

**Alat CLI untuk penambangan otomatis token ITX.**  

## Persyaratan Minimum  
- **Memori:** 8GB atau lebih  
- **CPU:** 4 inti atau lebih, dengan kecepatan clock 2 GHz atau lebih tinggi.  

---

## Panduan Untuk Base Sepolia Testnet  

Panduan ini menjelaskan cara memulai penambangan di jaringan Intmax menggunakan CLI penambangan `intmax2`. Instruksi di bawah ini menjelaskan proses untuk **Base Sepolia testnet**.  

---

### Prasyarat  

Sebelum memulai, pastikan Anda memiliki hal-hal berikut:  

1. **Ethereum Base Sepolia (ETH):**  
   - Minimal **0.5 ETH** untuk testnet.  
   - ETH tambahan untuk biaya gas.  

2. **Alchemy API Key:**  
   - Dapatkan kunci API dari [Alchemy](https://www.alchemy.com).  

3. **Private Key Penarikan:**  
   - Private key dari alamat yang akan Anda gunakan untuk:  
     - Menarik ETH.  
     - Menerima token ITX.  
   - Wajib gunakan wallet baru dan tidak ada transaksi.  

---
### Task Testnet di Intmax
Tugas Testnet:
Anda dapat mengerjakan berbagai tugas testnet seperti:

Bridge: Menggunakan jembatan untuk memindahkan aset antar jaringan.
Swap: Melakukan swap aset antara token yang berbeda.
Mining: Melakukan penambangan token ITX pada jaringan testnet

Kunjungi platform testnet di 
https://testnet.app.intmax.io/ 

Penting:

Gunakan wallet yang berbeda dari wallet yang digunakan dalam mining CLI untuk melakukan tugas testnet.
Pastikan Anda tidak menggunakan alamat penarikan dari mining CLI untuk tugas lain di platform testnet ini.

### Instalasi dan Menjalankan Node  

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan node:  

1. Unduh skrip Auto instalasi:  
   ```bash
   klik star di atas dulu
   ```
### Alur Pengaturan Mining-CLI
1. Pilih Jaringan:

Pilih Base-Sepolia (testnet) sebagai jaringan.
Pilih File Konfigurasi:

Jika ini adalah pengaturan pertama kali:
Pilih Buat Konfigurasi Baru untuk memulai proses pengaturan akun penambangan.

2. Masukkan API Key:

Masukkan kunci API Alchemy Anda untuk melanjutkan.
Konfigurasi Pengaturan Penambangan:

Tetapkan:
Max Gas Price
Mining Unit
Mining Times
Pilihan:
Gunakan nilai default dengan menekan Enter atau memilih y.
Masukkan nilai kustom dengan menekan n.

3. Masukkan Kunci Pribadi Penarikan:

Masukkan kunci pribadi dari dompet kosong yang akan Anda gunakan untuk menarik ETH dan menerima token ITX.
Catatan Penting:
Gunakan dompet kosong sebagai alamat penarikan.
Jangan menyetor langsung ke alamat ini dari alamat setoran yang dibuat selama proses penambangan.

4. Cara Kerja Penambangan
Pilih Mode Operasi:

Saat menjalankan CLI, pilih mode menggunakan tombol panah:
Mining: Untuk memulai proses penambangan.
Claim: Untuk klaim token yang telah ditambang.
Exit: Untuk keluar dari aplikasi.
Export: Untuk mengekspor data konfigurasi.
Untuk saat ini, pilih mode Mining

Pembuatan Alamat Deposit:

CLI akan membuat alamat deposit dan menampilkannya di layar.
Kirimkan jumlah ETH yang diminta ke alamat deposit yang diberikan oleh CLI.
Pastikan jumlah yang dikirim mencukupi sesuai dengan perhitungan.

### Catatan Penting dalam Proses Penambangan
Hindari Transfer Langsung atau Tidak Langsung:

Jangan melakukan transfer langsung antara alamat penyetoran dan alamat penarikan.
Transfer dari alamat penyetoran ke alamat penarikan, baik langsung maupun melalui pihak ketiga, akan mendiskualifikasi alamat penarikan dari menerima hadiah penambangan.
Penyetoran di Alamat Penarikan Dilarang:

Jangan gunakan alamat penarikan untuk menyetor ETH.
Alamat penarikan harus tetap kosong kecuali untuk menerima hasil penambangan

Panduan Lebih Lanjut:

Untuk detail tambahan tentang aturan dan konfigurasi, silakan merujuk ke dokumen official

### Informasi Klaim Token ITX
Penyetoran yang Memenuhi Syarat:

Pada testnet, setoran yang memenuhi syarat untuk token ITX akan dikonfirmasi setiap hari pada pukul 3 pagi UTC.
Proses Klaim:

Setelah setoran dikonfirmasi, Anda dapat mengklaim token ITX yang telah diperoleh.
Waktu Klaim:

Klaim token hanya bisa dilakukan setelah konfirmasi setoran pada pukul 3 pagi UTC setiap hari.

### Untuk Menjalankan Ulang Mining-CLI
Masuk ke Direktori Intmax-Mining:

```bash
cd intmax-mining
```
Jalankan Mining-CLI
```bash
./mining-cli
```

### Support Airdrop Node

For more updates and discussions, join the [Telegram Airdrop Node](https://t.me/airdrop_node).

[Traktir Kopi ](https://trakteer.id/AirdropNode/tip).

### DONE
