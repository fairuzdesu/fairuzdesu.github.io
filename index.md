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
 <p align="center"> <img src="pelayanandasar.png" alt="Variabel dan Indikator Dimensi Pelayanan Dasar" width="431" height="293" class="center"> </p>
 <br><br>
 <b>Kondisi Infrastruktur</b> mewakili Kebutuhan Dasar; Sarana; Prasarana; Pengembangan Ekonomi Lokal; dan Pemanfaatan Sumberdaya Alam secara Berkelanjutan dengan memisahkan aspek aksesibilitas/ transportasi. Variabel-variabel penyusunnya mencakup ketersediaan infrastruktur ekonomi seperti: kelompok pertokoan, minimarket, toko kelontong, pasar, restoran, rumah makan, maupun warung/kedai makanan, akomodasi hotel atau penginapan, serta bank; ketersediaan infrastruktur energi seperti: listrik, penerangan jalan, dan bahan bakar untuk memasak; ketersediaan infrastruktur air bersih dan sanitasi seperti: sumber air minum, sumber air mandi/cuci, dan fasilitas buang air besar; serta ketersediaan dan kualitas infrastruktur komunikasi dan informasi seperti: komunikasi menggunakan telepon seluler, internet, dan pengiriman pos/barang.
	
	<br><br>
 <p align="center"><img src="kondisiinfrastruktur.png" alt="Variabel dan Indikator Dimensi Kondisi Infrastruktur" width="437" height="269" class="center"></p> 
	
	<br><br>
 <b>Aksesibilitas/ Transportasi</b> dipisahkan sebagai dimensi tersendiri dalam indikator pembangunan desa dengan pertimbangan sarana dan prasarana transportasi memiliki kekhususan dan prioritas pembangunan desa sebagai penghubung kegiatan sosial ekonomi dalam desa. Variabel-variabel penyusunnya meliputi ketersediaan dan akses terhadap sarana transportasi seperti: lalu lintas dan kualitas jalan, aksesibilitas jalan, ketersediaan dan operasional angkutan umum; dan aksesibilitas transportasi seperti: waktu tempuh per kilometer transportasi ke kantor camat, biaya per kilometer transportasi ke kantor camat, waktu tempuh per kilometer transportasi ke kantor bupati/ walikota, dan biaya per kilometer transportasi ke kantor bupati/walikota.Indikator jarak antara desa dengan pusat pemerintahan ini merujuk dari variabel yang tercantum dalam Potensi Desa 2018, dengan asumsi bahwa pada umumnya pusat kegiatan sosial-ekonomi suatu kawasan berada di sekitar/dekat pusat- pusat pemerintahan.
	
<br><br>
	<p align="center"> <img src="aksesibilitastransportasi.png" alt="Variabel dan Indikator Dimensi Aksesibilitas Transportasi" width="437" height="165" class="center"> </p>
 <br><br>
	
 <b>Pelayanan Umum</b> merupakan upaya pemenuhan kebutuhan pelayanan atas barang, jasa, dan/atau pelayanan administratif dengan tujuan memperkuat demokrasi, kohesi sosial, perlindungan lingkungan, dan sebagainya. Karena kekhususannya, variabel pelayanan administratif dinyatakan sebagai dimensi tersendiri (Penyelenggaraan Pemerintahan). Begitupun dengan variabel pendidikan, kesehatan, transportasi, dan lainnya menjadi dimensi tersendiri yang telah dijelaskan sebelumnya. Pelayanan dalam dimensi ini mewakili aspek ingkungan dan aspek pemberdayaan masyarakat serta mengacu pada ketersediaan data Potensi Desa 2018. Aspek lingkungan dalam hal ini terkait dengan kesehatan lingkungan masyarakat, sedangkan aspek pemberdayaan masyarakat diwakili dengan keberadaan kelompok kegiatan masyarakat. Oleh karena itu, variabel-variabel penyusun dimensi ini mencakup penanganan kesehatan masyarakat seperti: penanganan kejadian luar biasa (KLB), dan penanganan gizi buruk; serta ketersediaan fasilitas olah raga seperti: ketersediaan lapangan olah raga, dan kelompok kegiatan olah raga.
	
<br><br>
	<p align="center"><img src="pelayananumum.png" alt="Variabel dan Indikator Dimensi Pelayanan Umum" width="453" height="76" class="center"></p>
 <br><br>
 <b>Penyelenggaraan Pemerintahan</b> mewakili indikasi kinerja pemerintahan desa merupakan bentuk pelayanan administratif yang diselenggarakan penyelenggara pelayanan bagi warga yang dalam hal ini adalah Pemerintah. Oleh karena itu variabel ini perlu diukur dan berdiri sendiri sebagai sebuah indikator pembangunan desa, karena sifatnya sebagai perangkat terlaksananya tujuan pembangunan desa tersebut. Variabel-variabel penyusunnya meliputi kemandirian seperti: kelengkapan pemerintahan desa, otonomi desa, dan asset/kekayaan desa; serta kualitas sumber daya manusia seperti: kualitas SDM kepala desa dan sekretaris desa.

<br><br>
<p align="center"><img src="penyelenggaraanpemerintahan.png" alt="Variabel dan Indikator Dimensi Penyelenggaraan Pemerintahan" width="437" height="103" class="center"> </p>
<br><br>

</p>




### Alur Pengolahan Data
<ol>
<li>Memperoleh data pendataan PODES 2018 melalui permintaan data ke BPS</li>
<li>Menghitung setiap indikator pada setiap dimensi IPD untuk setiap desa</li>
<li>Agregasi di tingkat kabupaten dilakukan untuk memenuhi kebutuhan data pada usecase monitoring setiap provinsi, tahapan yang dilakukan antara lain : 
    <ol>
      <li>Agregasi Indikator</li>
      <li>Perhitungan setiap dimensi</li>
      <li>Perhitungan IPD-Kabupaten</li>
    </ol>
</li>
<li>Agregasi di tingkat provinsi dilakukan untuk memenuhi kebutuhan data pada usecase overview Indonesia, tahapan yang dilakukan antara lain :
<ol>
  <li>Agregasi indikator</li>
  <li>Perhitungan setiap dimensi</li>
  <li>Perhitungan IPD-Provinsi</li>
</ol>
</li>
<li>Melakukan perhitungan IPD di tingkat nasional</li>
</ol>


## Evaluasi Hasil Dashboard
<p>
Untuk mengukur usability dari dashboard profil pembangunan desa, maka survey evaluasi dashboard pun dilakukan dengan menggunakan kuesioner system usability scale. 
Pada survey ini terdapat 44 responden, dimana 10 diantaranya adalah pegawai BPS, dan 34 sisanya merupakan mahasiswa Politeknik Statistika STIS
<br><br>
	<p align="center"><img src="subjectmatter.png" class="center"></p>
	
<br><br>
Berdasarkan gambar diatas terlihat bahwa secara overall (Mahasiswa STIS + BPS) telah dicapai skor SUS sebesar 83.011. Skor 83.011 > 80 mengindikasikan bahwa dashboard yang telah dibangun itu memiliki usability dengan grade A, yaitu grade tertinggi dari pengkategorian SUS, dengan karakteristik excellent. Dengan demikian dapat disimpulkan bahwa dashboard yang telah dibangun memenuhi aspek usability dengan sangat baik.
<br><br>
Kemudian meskipun sama-sama tergolong grade A, dan excellent, terdapat perbedaan penilaian usability berdasarkan kategori responden. Pada responden pegawai BPS diperoleh skor SUS sebesar 80 sedangkan untuk mahasiswa Politeknik Statistika STIS sebesar 83.9. Hal ini berarti bahwa mahasiswa Politeknik Statistika STIS lebih menilai tinggi usability dari dashboard yang telah dirancang. Hal ini mengindikasikan bahwa mahasiswa Politeknik Statistika STIS lebih menilai tinggi usability dari dashboard yang telah dibangun dibandingkan pegawai BPS. Masih kurang jelas apa yang menyebabkan hal ini, studi lebih lanjut harus dilakukan. 
<br><br>
<p align="center"><img src="question.png" class="center"></p>
<br><br>
Kemudian berdasarkan gambar diatas, dapat dilihat rata-rata skor kontribusi dari tiap pernyataan. Pernyataan ke-10, yaitu ???Saya perlu membiasakan diri terlebih dahulu sebelum mengunjungi dashboard??? memiliki rata-rata skor kontribusi terendah. Di sisi lain pernyataan ke-5, yaitu ???Saya merasa fitur-fitur pada dashboard ini berjalan dengan mestinya???. Hal ini berarti bahwa meskipun dashboard yang dirancang telah bebas dari bug dan sudah sesuai dengan fungsinya, dashboard tersebut masih belum cukup self explanatory dan intuitif sehingga pengguna akan membutuhkan waktu hingga terbiasa dalam menggunakan interface dashboard


</p>
