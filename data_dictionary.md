Nama Kolom,Tipe Data,Skala,Deskripsi,Kategori Data Pribadi,Tindakan Penanganan
id_peserta,string,Nominal,Kode unik registrasi peserta pelatihan,Quasi-identifier,Hash (SHA-256 + Salt)
nama_lengkap,string,Nominal,Nama lengkap peserta sesuai identitas kependudukan,Pengenal langsung,Hapus
nik,integer,Nominal,Nomor Induk Kependudukan 16 digit,Pengenal langsung,Hapus
no_hp,string,Nominal,Nomor telepon seluler/WhatsApp aktif peserta,Pengenal langsung,Hapus
email,string,Nominal,Alamat surat elektronik peserta,Pengenal langsung,Hapus
alamat_jalan,string,Nominal,"Alamat tempat tinggal detail (nama jalan, RT/RW)",Pengenal langsung,Hapus
kelurahan,string,Nominal,Nama wilayah administratif kelurahan,Quasi-identifier,Hapus
kecamatan,string,Nominal,Nama wilayah administratif kecamatan,Quasi-identifier,Pertahankan (Generalisasi Wilayah)
tanggal_lahir,date,Interval,Tanggal lahir peserta pelatihan,Quasi-identifier,Generalisasi ke Kelompok Umur
jenis_kelamin,category,Nominal,Jenis kelamin peserta (L/P),Quasi-identifier,Pertahankan
pendidikan_terakhir,category,Ordinal,Jenjang formal pendidikan terakhir peserta,Quasi-identifier,Generalisasi Tingkat Pendidikan
kategori_usaha,category,Nominal,Sektor industri/klaster bisnis yang dijalankan,Bukan data pribadi,Pertahankan
lama_usaha_tahun,float,Rasio,Durasi operasional usaha berjalan dalam tahun,Bukan data pribadi,Pertahankan
jumlah_karyawan,integer,Rasio,Jumlah tenaga kerja yang dipekerjakan,Bukan data pribadi,Pertahankan
omzet_usaha_bulanan,integer,Rasio,Rata-rata pendapatan kotor usaha per bulan,Bukan data pribadi,Pertahankan
kehadiran_persen,integer,Rasio,Persentase kehadiran selama sesi pelatihan,Bukan data pribadi,Pertahankan
skor_prates,integer,Interval,Nilai ujian sebelum pelatihan dimulai (0–100),Bukan data pribadi,Pertahankan
skor_pascates,float,Interval,Nilai ujian akhir setelah pelatihan selesai (0–100),Bukan data pribadi,Pertahankan
