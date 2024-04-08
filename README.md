# **Capstone Project Module 2**
Exploratory Data Analysis mengenai Dataset TransJakarta


### **Overview TransJakarta**

Transjakarta (terkadang ditulis sebagai TransJakarta) adalah sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan, yang beroperasi sejak tahun 2004 di Jakarta, Indonesia. Sistem ini didesain berdasarkan sistem TransMilenio di Bogota, Kolombia. Transjakarta dirancang sebagai moda transportasi massal pendukung aktivitas ibu kota yang sangat padat. Transjakarta merupakan sistem BRT dengan jalur lintasan terpanjang di dunia (251,2 km), serta memiliki 287 halte yang tersebar dalam 13 koridor (rute utama), yang pada awalnya beroperasi dari pukul 05.00–22.00 WIB, dan kini beroperasi selama 24 jam di seluruh koridornya.

Manfaat Transjakarta :

1. **Tarif Terjangkau**: Transjakarta adalah transportasi umum dengan **tarif paling murah** di Jakarta. Per Oktober 2022, tarifnya adalah:
   - Jam operasional 05.00 – 07.00 WIB: Rp2.000
   - Jam 07.00 – 24.00 WIB: Rp3.500
   - Jam 24.00 – 05.00 WIB: Rp3.500. Dengan tarif ini, warga bisa berpergian ke mana pun di Jakarta tanpa membayar lebih.
2. **Halte Tersedia di Banyak Titik**: Transjakarta memiliki **260 halte** yang tersebar di **13 koridor** di Jakarta. Jadwal kedatangan Transjakarta juga relatif singkat, sekitar lima hingga 12 menit saja.
3. **Fasilitas Memadai**: Bus Transjakarta dilengkapi dengan fasilitas keamanan dan keselamatan, seperti CCTV dan petugas keamanan. Selain itu, fasilitas penumpangnya juga nyaman, termasuk AC, kursi empuk, dan jendela besar.
4. **Meningkatkan Kualitas Hidup**: Dengan menggunakan Transjakarta, masyarakat Jakarta dapat memperoleh akses ke berbagai tempat dengan lebih mudah, sehingga meningkatkan kualitas hidup mereka.
5. **Memperkuat Transportasi Massal di Jakarta**: Dengan menggunakan Transjakarta, masyarakat Jakarta dapat mendukung dan memperkuat sistem transportasi massal yang ada di kota, membantu pemerintah membangun sistem yang lebih baik dan efisien di masa depan².


Sumber:
(1) Transjakarta – PT Transportasi Jakarta. https://transjakarta.co.id/produk-dan-layanan/layanan-bus/transjakarta/.
(2) PT Transportasi Jakarta. https://www.jakarta.go.id/pt-transportasi-jakarta.
(3) Tentang Transjakarta – PT Transportasi Jakarta. https://transjakarta.co.id/tentang-transjakarta/.
(4) Transjakarta: A Study in Success - Institute for Transportation and .... https://itdp-indonesia.org/2019/07/transjakarta-study-success/.

### **Problem**

1. Koridor/Halte mana yang menjadi koridor/halte tersibuk dan terpadat.
2. Koridor/Halte mana yang paling banyak diakses oleh perempuan.
3. Klasifikasi koridor/Halte terhadap kelas umur penumpang.
4. Apa alasan banyaknya penumpang tidak tap out.

### **Goals / Tujuan dari analisis**

Merekomendasikan beberapa solusi yang sekiranya dapat menjadi pertimbangan oleh perusahaan PT Transportasi Jakarta dan Pemerintah Provinsi DKI Jakarta dalam meningkatkan kualitas layanan serta kualitas himpunan data yang diperoleh.

### **Dataset**
Dataset ini berisi informasi terkait umur, jenis kelamin, asal, tujuan, dan jenis moda transportasi pengguna layanan PT. TransJakarta. Ada 22 kolom di dalam dataset Transjakarta, yaitu:
|No. | Nama Kolom | Keterangan |
|----|------------|------------|
|1.	|transID| Unique transaction id for every transaction|
|2.	|payCardID| Customers main identifier. The card customers use as a ticket for entrance and exit.|
|3.	|payCardBank| Customers card bank issuer name|
|4.	|payCardName| Customers name that is embedded in the card.|
|5.	|payCardSex| Customers sex that is embedded in the card|
|6.	|payCardBirthDate| Customers birth year|
|7.	|corridorID| Corridor ID / Route ID as key for route grouping.|
|8.	|corridorName| Corridor Name / Route Name contains Start and Finish for each route.|
|9.	|direction| 0 for Go, 1 for Back. Direction of the route.|
|10.|tapInStops| Tap In (entrance) Stops ID for identifying stops name|
|11.|tapInStopsName| Tap In (entrance) Stops Name where customers tap in.|
|12.|tapInStopsLat| Latitude of Tap In Stops|
|13.|tapInStopsLon| Longitude of Tap In Stops|
|14.|stopStartSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|15.|tapInTime| Time of tap in. Date and time|
|16.|tapOutStops| Tap Out (Exit) Stops ID for identifying stops name|
|17.|tapOutStopsName| Tap out (exit) Stops Name where customers tap out.|
|18.|tapOutStopsLat| Latitude of Tap Out Stops|
|19.|tapOutStopsLon| Longitude of Tap Out Stops|
|20.|stopEndSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|21.|tapOutTime| Time of tap out. Date and time|
|22.|payAmount| The number of what customers pay. Some are free. Some not.|

### **Kesimpulan & Rekomendasi Solusi**

Termasuk didalam nya terdapat beberapa kesimpulan mengenai Exploratory Data Analysis ini beserta solusi yang dapat dikemukakan sebagai pertimbangan untuk perbaikan pelayanan angkutan umum PT Transportasi Jakarta.
