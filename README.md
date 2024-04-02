# Review-Paper-TDPGRVRA
Tugas Review Paper Game **(Rifqi M. Riefard 6025231001)**

**Judul Paper**:Aplikasi Pemandu Wisata Pada Candi Plaosan Berbasis Augmented Reality<br/>
**Author**: Reza Aprillian Nugroho, Anna Dina Kalifia<br/>
**Jurnal**: JUKI : Jurnal Komputer Informatika<br/>
**Tahun**: 2023<br/>
<br/>
<br/>
![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/f3c22b76-1354-4f6b-9ba5-a4c8f72d9348)

**#OVERVIEW**
<br/>
Artikel ini membahas pengembangan aplikasi pemandu wisata berbasis augmented reality untuk Candi Plaosan menggunakan metode waterfall. Aplikasi bernama ReSan AR berhasil dikembangkan dan diuji dengan hasil yang menunjukkan kinerja yang baik. Implementasi program dari aplikasi AR ReSan menampilkan candi dan relief dengan objek 3D, serta telah diuji menggunakan metode black box untuk memastikan fungsi tombol dan webcam berjalan dengan baik. Hasilnya menunjukkan bahwa aplikasi markerless AR memberikan pengalaman interaktif tanpa marker fisik dan dapat meningkatkan keterlibatan pengguna. Penelitian ini juga mencakup tinjauan pustaka yang mendukung penggunaan metode augmented reality dalam berbagai konteks, seperti pemasaran, pendidikan, dan hiburan, serta menyoroti keefektifan metode marker based tracking dalam meningkatkan pengalaman pengguna. Dengan demikian, metode ini memiliki potensi besar dalam berbagai industri dan aplikasi.

**Apa**<br/>
Artikel ini membahas pengembangan aplikasi pemandu wisata berbasis augmented reality untuk Candi Plaosan. Aplikasi tersebut bertujuan untuk membantu pengunjung memahami sejarah dan nilai budaya candi tersebut. Penelitian ini mencakup pengembangan aplikasi mobile bernama ReSan AR dan hasil pengujian yang menunjukkan kinerja yang baik .
<br/>
**Mengapa**<br/>
Tujuan dari penelitian ini adalah untuk meningkatkan pengalaman pengunjung di Candi Plaosan dengan menyediakan panduan digital yang menawarkan pemahaman yang lebih dalam tentang nilai sejarah dan budaya situs tersebut. Dengan menggunakan teknologi augmented reality, aplikasi ini bertujuan membuat pembelajaran tentang candi menjadi lebih interaktif dan menarik bagi pengunjung. Penelitian ini juga bertujuan untuk mengeksplorasi potensi aplikasi AR tanpa marker dalam meningkatkan keterlibatan pengguna dan memberikan cara unik untuk mengalami situs bersejarah .
<br/>
**Bagaimana**<br/>
Metodologi penelitian yang digunakan dalam studi ini adalah metode waterfall, yang melibatkan pendekatan berurutan dalam pengembangan perangkat lunak. Proses pengembangan meliputi desain dan pengujian aplikasi ReSan AR untuk memastikan fungsionalitas dan kinerjanya. Pengujian black box dilakukan untuk memverifikasi fungsi tombol dan webcam. Studi ini juga mencakup tinjauan pustaka yang mendukung penggunaan augmented reality dalam berbagai konteks, seperti pemasaran, pendidikan, dan hiburan, serta menyoroti keefektifan metode pelacakan berbasis marker dalam meningkatkan pengalaman pengguna .
<br/>


**#METHOD**
<br/>
**Arsitektur Sistem**<br/>
![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/42efacef-3d36-4b15-9dd4-c53da354d488)<br/>
Ada dua sisi yaitu admin dan pengguna.Informasi arsitektur sistem dari sisi administrator adalah sebagai berikut:
<br/>1.Administrator  dapat  mengolah  data  melalui  website  administrasi,  seperti  menambah  data, mengedit data, dan menghapus data.
<br/>2.Situs admin terhubung ke database. Administrator situs bertindak sebagai antarmuka pengguna atau perangkat lunak yang memungkinkan pengguna berinteraksi dengan database di Unity.
<br/>
<br/>Gambaran arsitektur sistem dari sisi pengguna adalah sebagai berikut:
<br/>1.Pengguna mengakses aplikasi AR ReSan.
<br/>2.Pengguna mengarahkan kamera AR pada area datar.
<br/>3.Sistem akan membaca penanda datar.
<br/>4.Jika pemindaian berhasil maka akan muncul objek relief 3D.<br/>
<br/>
<br/>
**#RESULTS**
<br/>
**OUTPUT**
<br/>
![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/a3c31c49-a564-4be6-a3c3-dc3c21f58ce3)![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/35579572-c030-463d-9c72-c05144435e64)![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/f8f6e9ea-9dcd-450c-8608-bc54d96b7783)![image](https://github.com/Rifera/Review-Paper-TDPGRVRA/assets/63510694/d973c786-c57a-441d-9d01-c00b77834fb5)
<br/>
<br/>
**1. Worlds**
<br/>
<br/>
Dalam paper ini, elemen "Worlds" merujuk pada penggabungan dunia nyata (lingkungan sekitar Candi Plaosan) dengan dunia maya (objek 3D dan informasi tambahan) melalui teknologi augmented reality. Aplikasi ReSan AR memungkinkan pengguna untuk menjelajahi dan berinteraksi dengan dunia maya yang disajikan di atas dunia nyata Candi Plaosan, menciptakan pengalaman yang memperluas persepsi pengguna terhadap lingkungan sekitarnya.
<br/>
<br/>
**2. Interactivity**
<br/>
<br/>
Elemen "Interactivity" dalam paper ini mengacu pada kemampuan pengguna untuk berinteraksi dengan objek virtual yang ditampilkan melalui aplikasi AR. Dengan menggunakan metode markerless AR, pengguna dapat berpartisipasi aktif dalam menjelajahi Candi Plaosan, memilih objek yang ingin dilihat, dan mendapatkan informasi tambahan dengan cara yang lebih dinamis dan interaktif.
<br/>
<br/>
**3. Sensory Feedback**
<br/>
<br/>
Dalam konteks paper ini, "Sensory Feedback" mengacu pada respons sensorik yang diterima oleh pengguna saat berinteraksi dengan aplikasi ReSan AR. Melalui visualisasi objek 3D, suara, dan informasi tambahan yang disajikan secara real-time, pengguna dapat merasakan pengalaman yang lebih mendalam dan imersif saat menjelajahi Candi Plaosan melalui teknologi augmented reality.
<br/>
<br/>
**4. Immersion**
<br/>
<br/>
lemen "Immersion" dalam paper ini menggambarkan tingkat keterlibatan dan kedalaman pengalaman yang dirasakan oleh pengguna saat menggunakan aplikasi AR. Dengan menggabungkan dunia nyata dan dunia maya secara mulus, ReSan AR menciptakan lingkungan yang imersif di sekitar Candi Plaosan, memungkinkan pengguna untuk merasakan pengalaman wisata yang lebih mendalam dan interaktif .
<br/>
<br/>
**#PERSONAL COMMENTS**
<br/><br/>
**STRENGTHS**
<br/>
1. **Pengembangan Aplikasi AR Inovatif**: Paper ini menghasilkan aplikasi pemandu wisata berbasis augmented reality yang inovatif untuk Candi Plaosan, memberikan pengalaman interaktif tanpa memerlukan marker fisik.<br/>
2. **Pengujian Fungsionalitas**: Pengujian black box dilakukan untuk memastikan fungsi tombol dan webcam berjalan dengan baik, menunjukkan komitmen terhadap kualitas aplikasi yang dikembangkan.<br/>
3. **Penerapan Teknologi Augmented Reality**: Penerapan teknologi augmented reality dalam aplikasi ini memberikan pengalaman interaktif yang unik dan meningkatkan keterlibatan pengguna dalam memahami sejarah dan nilai budaya Candi Plaosan.
<br/><br/>

**WEAKNESSES**<br/>
1. **Keterbatasan Tinjauan Pustaka:** Meskipun tinjauan pustaka disertakan, paper ini dapat diperkaya dengan lebih banyak referensi yang mendukung penggunaan augmented reality dalam konteks wisata dan budaya.<br/>
2. **Keterbatasan Implementasi:** Meskipun hasil pengujian menunjukkan kinerja yang baik, paper ini dapat memberikan informasi lebih rinci tentang tantangan yang dihadapi selama implementasi aplikasi AR dan cara mengatasinya untuk pengembangan di masa depan.<br/>
3. **Kurangya segi penulisan :** Dalam paper ini, terdapat beberapa kelemahan dari segi penulisan yang perlu diperhatikan. Salah satunya adalah kurangnya konsistensi dalam penggunaan gaya penulisan dan format, seperti penggunaan huruf kapital yang tidak konsisten pada beberapa bagian teks . Hal ini dapat mempengaruhi kesan keseluruhan dari paper dan perlu diperbaiki untuk meningkatkan kualitas penulisan.
<br/>
**NOVELTY**<br/>
Novelty dalam metode penelitian ini terletak pada penggunaan metode markerless AR dalam pengembangan aplikasi pemandu wisata untuk Candi Plaosan. Aplikasi ReSan AR memberikan pengalaman interaktif tanpa memerlukan marker fisik, memungkinkan pengguna untuk menjelajahi Candi Plaosan dengan objek 3D dan informasi tambahan yang disajikan secara dinamis .
<br/>
<br/>
**#CONCLUSSION**
<br/>
Penelitian ini menghasilkan aplikasi pemandu wisata berbasis augmented reality untuk Candi Plaosan menggunakan metode waterfall. Aplikasi AR ReSan menampilkan candi dan relief dengan objek 3D, memberikan pengalaman interaktif tanpa marker fisik. Pengujian black box memastikan fungsi tombol dan webcam berjalan dengan baik. Metode marker based tracking efektif dalam meningkatkan pengalaman pengguna dalam berbagai konteks. Potensi aplikasi AR ini dapat diterapkan dalam industri pemasaran, pendidikan, dan hiburan. Paper ini dapat menjadi referensi yang baik untuk projek akhir Mata Kuliah Pengembangan Game
<br/>
<br/>
**#FUTURE WORKS**
<br/>
Future work dari penelitian ini dapat meliputi pengembangan lebih lanjut pada aplikasi ReSan AR untuk meningkatkan fitur dan konten yang disajikan kepada pengguna. Selain itu, penelitian selanjutnya dapat memperluas cakupan pengujian aplikasi ini dengan melibatkan lebih banyak pengguna untuk mendapatkan umpan balik yang lebih luas .
