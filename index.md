# Dashboard Profil Pembangunan Desa Indonesia

## Abstrak
<p align="justify">
 Desa, sebagai wilayah administrasi terendah secara mandiri telah dijadikan subjek pembanguan. Tujuannya adalah untuk mengurangi kesenjangan pembangunan yang sejauh ini bias terhadap daerah perkotaan serta juga menjadi solusi terhadap berbagai permasalahan dan dinamika sosial ekonomi desa. Desa sebagai subjek pembangunan diharapkan mampu mendekatkan pelayanan terhadap warga melalui pembangunan infrastruktur dan pemberdayaan. Mulai dari menggerakkan perekonomian, membangun sarana Pendidikan, kesehatan, sarana dan prasarana energi, transportasi, dan komunikasi, serta sarana lain yang dibutuhkan. Dengan adanya urgensi tersebut maka pada penelitian ini akan dirancang dan dibangun dashboard profil pembangunan desa Indonesia guna memenuhi fungsi monitoring dan evaluasi pembangunan desa di seluruh Indonesia baik untuk tingkat nasional maupun di setiap provinsi. Dashboard yang telah dibangun kemudian dievaluasi dengan metode system usability scale diperoleh skor overall sebesar 83.011 yang mengindikasikan bahwa dashboard yang telah dibangun tergolong grade A, yaitu grade tertinggi terkait usability dengan kriteria excellent.
</p>

## Metodologi

### Cakupan dan Sumber Data

<p align="justify">
Sumber data utama yang digunakan pada perancangan dashboard visualisasi informasi profil pembangunan desa Indonesia adalah hasil pendataan potensi desa tahun 2018 oleh Badan Pusat Statistik.
</p>
<p align="justify"> 
Wilayah administrasi yang didata pada pendataan podes harus memenuhi tiga syarat : 1) ada wilayah dengan batas yang jelas, 2) ada penduduk yang menetap, dan 3) ada pemerintah desa/ kelurahan. Penelitian ini dibatasi pada lingkup Indonesia yang mencakup 34 provinsi, 514 kabupaten/ kota, dan 75044 desa.
</p>
<p align ="justify">
 Untuk melakukan visualisasi secara spasial juga digunakan shapefile provinsi-provinsi di Indonesia yang bersumber dari portal geospasial Indonesia (https://tanahair.indonesia.go.id/portal-web). 
</p>


### Indeks Pembangunan Desa

<p align="justify">
Indeks Pembangunan Desa atau IPD merupakan suatu ukuran yang disusun untuk menilai tingkat kemajuan atau perkembangan desa-desa di Indonesia. Tingkat kemajuan dan perkembangan pembangunan desa diukur menggunakan beberapa ukuran yang secara fungsional saling terkait untuk menggambarkan konsep tersebut secara komprehensif. Beberapa dimensi disusun untuk mencakup sekaligus beberapa variabel dan indikator. Antar dimensi diharapkan bersifat saling melengkapi untuk menggambarkan tingkat kemajuan pembangunan di setiap desa.
 <br><br>
Terdapat 5 dimensi pembentuk Indeks Pembangunan Desa, yaitu : Pelayanan Dasar, Kondisi Infrastruktur, Aksesibilat/ Transportasi, Pelayanan Umum, Penyelanggaran Pemerintahan.
 <br><br>
 <b>Pelayanan Dasar</b> mewakili aspek pelayanan dasar untuk mewujudkan bagian dari kebutuhan dasar, khusus untuk pendidikan dan kesehatan. Variabel yang termasuk sebagai komponen penyusunnya meliputi ketersediaan dan akses terhadap fasilitas pendidikan seperti TK, SD, SMP, dan SMA; serta ketersediaan dan akses terhadap fasilitas kesehatan seperti rumah sakit, rumah sakit bersalin, puskesmas/ pustu, tempat praktet dokter, poliklinik/ balai pengobatan, tempat praktek bidan, poskesdes, polindes, dan apotek.
 <br><br>
 <b>Kondisi Infrastruktur</b> mewakili Kebutuhan Dasar; Sarana; Prasarana; Pengembangan Ekonomi Lokal; dan Pemanfaatan Sumberdaya Alam secara Berkelanjutan dengan memisahkan aspek aksesibilitas/ transportasi. Variabel-variabel penyusunnya mencakup ketersediaan infrastruktur ekonomi seperti: kelompok pertokoan, minimarket, toko kelontong, pasar, restoran, rumah makan, maupun warung/kedai makanan, akomodasi hotel atau penginapan, serta bank; ketersediaan infrastruktur energi seperti: listrik, penerangan jalan, dan bahan bakar untuk memasak; ketersediaan infrastruktur air bersih dan sanitasi seperti: sumber air minum, sumber air mandi/cuci, dan fasilitas buang air besar; serta ketersediaan dan kualitas infrastruktur komunikasi dan informasi seperti: komunikasi menggunakan telepon seluler, internet, dan pengiriman pos/barang.
 <br><br>
 <b>Aksesibilitas/ Transportasi</b> dipisahkan sebagai dimensi tersendiri dalam indikator pembangunan desa dengan pertimbangan sarana dan prasarana transportasi memiliki kekhususan dan prioritas pembangunan desa sebagai penghubung kegiatan sosial ekonomi dalam desa. Variabel-variabel penyusunnya meliputi ketersediaan dan akses terhadap sarana transportasi seperti: lalu lintas dan kualitas jalan, aksesibilitas jalan, ketersediaan dan operasional angkutan umum; dan aksesibilitas transportasi seperti: waktu tempuh per kilometer transportasi ke kantor camat, biaya per kilometer transportasi ke kantor camat, waktu tempuh per kilometer transportasi ke kantor bupati/ walikota, dan biaya per kilometer transportasi ke kantor bupati/walikota.Indikator jarak antara desa dengan pusat pemerintahan ini merujuk dari variabel yang tercantum dalam Potensi Desa 2018, dengan asumsi bahwa pada umumnya pusat kegiatan sosial-ekonomi suatu kawasan berada di sekitar/dekat pusat- pusat pemerintahan.
 <br><br>
 <b>Pelayanan Umum</b> merupakan upaya pemenuhan kebutuhan pelayanan atas barang, jasa, dan/atau pelayanan administratif dengan tujuan memperkuat demokrasi, kohesi sosial, perlindungan lingkungan, dan sebagainya. Karena kekhususannya, variabel pelayanan administratif dinyatakan sebagai dimensi tersendiri (Penyelenggaraan Pemerintahan). Begitupun dengan variabel pendidikan, kesehatan, transportasi, dan lainnya menjadi dimensi tersendiri yang telah dijelaskan sebelumnya. Pelayanan dalam dimensi ini mewakili aspek ingkungan dan aspek pemberdayaan masyarakat serta mengacu pada ketersediaan data Potensi Desa 2018. Aspek lingkungan dalam hal ini terkait dengan kesehatan lingkungan masyarakat, sedangkan aspek pemberdayaan masyarakat diwakili dengan keberadaan kelompok kegiatan masyarakat. Oleh karena itu, variabel-variabel penyusun dimensi ini mencakup penanganan kesehatan masyarakat seperti: penanganan kejadian luar biasa (KLB), dan penanganan gizi buruk; serta ketersediaan fasilitas olah raga seperti: ketersediaan lapangan olah raga, dan kelompok kegiatan olah raga.
 <br><br>
 <b>Penyelenggaraan Pemerintahan</b> mewakili indikasi kinerja pemerintahan desa merupakan bentuk pelayanan administratif yang diselenggarakan penyelenggara pelayanan bagi warga yang dalam hal ini adalah Pemerintah. Oleh karena itu variabel ini perlu diukur dan berdiri sendiri sebagai sebuah indikator pembangunan desa, karena sifatnya sebagai perangkat terlaksananya tujuan pembangunan desa tersebut. Variabel-variabel penyusunnya meliputi kemandirian seperti: kelengkapan pemerintahan desa, otonomi desa, dan asset/kekayaan desa; serta kualitas sumber daya manusia seperti: kualitas SDM kepala desa dan sekretaris desa.

</p>




### Alur Pengolahan Data

## Evaluasi Hasil Dashboard
