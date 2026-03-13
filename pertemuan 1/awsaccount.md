Pada pertemuan pertama dosen menjabarkan perihal kontrak belajar dan tugas-tugas yang akan dikerjakan selama 1 semester kedepan, dan mengarahkan apa output dari matakuliah ini. lalu dosen mempraktikan perihal rekap setiap pertemuan yang ditujukan sebagai tugas mandiri. dosen juga memberi arahan untuk pembuatan amazon web service account.

buka AWS https://aws.amazon.com/![alt text](image.png)

📋 Persiapan Sebelum Mendaftar
Sebelum memulai, pastikan Anda telah menyiapkan hal-hal berikut:

Alamat Email Aktif: Belum pernah digunakan untuk mendaftar AWS sebelumnya.
Kartu Kredit/Debit: Kartu yang mendukung transaksi internasional (Visa/Mastercard/Amex). Pastikan ada saldo minimal (sekitar Rp 15.000 - Rp 20.000) untuk verifikasi.
Nomor Telepon Aktif: Untuk verifikasi identitas melalui SMS atau panggilan.
Alamat Lengkap: Sesuai dengan data penagihan kartu Anda.
🚀 Langkah-langkah Pendaftaran
1. Kunjungi Halaman Pendaftaran
Buka browser dan akses portal.aws.amazon.com. Klik tombol "Create a new AWS account".

2. Informasi Login & Verifikasi Email
Masukkan Email Address dan AWS Account Name (nama akun bebas).
Klik Verify email address. Masukkan kode verifikasi yang dikirim ke email Anda.
Buat Root User Password yang kuat (minimal 8 karakter, kombinasi huruf besar, kecil, angka, dan simbol).
3. Informasi Kontak
Pilih Account Type:
Personal: Untuk belajar, proyek pribadi, atau portofolio.
Business: Untuk keperluan perusahaan/kantor.
Isi Nama Lengkap, Nomor Telepon, dan Alamat sesuai identitas.
Centang persetujuan AWS Customer Agreement.
4. Informasi Pembayaran (Billing)
Masukkan detail kartu kredit atau debit Anda.

Catatan Penting: AWS akan melakukan penahanan dana sementara (temporary hold) sekitar $1 USD (sekitar Rp 15.000) untuk memverifikasi validitas kartu. Saldo ini biasanya akan dikembalikan dalam beberapa hari.

5. Verifikasi Identitas
Masukkan nomor ponsel Anda.
Pilih metode verifikasi: SMS atau Voice Call.
Masukkan kode PIN yang Anda terima ke dalam kolom yang tersedia di layar.
6. Memilih Support Plan (Klaim Free Tier)
Pada tahap ini, Anda akan diberikan pilihan paket dukungan.

Pilih Basic Support – Free.
Jangan pilih Developer atau Business Support kecuali Anda siap membayar biaya bulanan mulai dari $29/bulan.
7. Aktivasi Akun
Klik Complete Sign Up. AWS akan memproses aktivasi akun Anda. Biasanya memakan waktu beberapa menit, namun dalam beberapa kasus bisa hingga 24 jam. Anda akan menerima email konfirmasi jika akun sudah aktif.

💡 Apa Saja yang Didapat di Free Tier?
AWS Free Tier terdiri dari tiga jenis penawaran:

Always Free: Gratis selamanya selama tidak melebihi batas (contoh: Lambda 1 juta request/bulan).
12 Months Free: Gratis selama satu tahun sejak pendaftaran (contoh: EC2 750 jam/bulan).
Trials: Uji coba gratis jangka pendek untuk layanan tertentu (contoh: SageMaker 2 bulan).
Layanan Utama	Kuota Free Tier
Amazon EC2	750 jam/bulan (Tipe instance t2.micro atau t3.micro)
Amazon S3	5 GB Storage (Standard Storage)
Amazon RDS	750 jam/bulan (Database seperti MySQL/PostgreSQL)
AWS Lambda	1 Juta Request per bulan
Amazon DynamoDB	25 GB Storage
⚠️ Tips Menghindari Tagihan Tak Terduga
Setelah akun aktif, sangat disarankan untuk melakukan hal berikut:

Set Up Billing Alarms: Gunakan CloudWatch atau AWS Budgets untuk mengirim email jika penggunaan Anda mendekati batas gratis atau jika biaya mencapai $1.
Gunakan Region yang Tepat: Beberapa region mungkin memiliki harga berbeda, namun Free Tier umumnya berlaku global.
Hapus Resource yang Tidak Dipakai: Jika selesai bereksperimen, segera Terminate instance EC2 atau hapus S3 Bucket yang tidak diperlukan.
Cek Dasbor Free Tier: Pantau penggunaan Anda di menu Billing & Cost Management -> Free Tier.
🏁 Langkah Selanjutnya
Selamat! Akun Anda sudah siap. Langkah pertama yang disarankan: Aktifkan MFA (Multi-Factor Authentication) pada akun Root Anda untuk keamanan maksimal sebelum mulai membuat resource apa pun.
![alt text](<Screenshot 2026-03-13 195210.png>)