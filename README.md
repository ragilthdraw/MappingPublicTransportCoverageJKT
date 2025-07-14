# Pemetaan Cangkupan Transportasi Publik di Jakarta
Project ini bertujuan untuk mengetahui cankupan dan aksesbilitas transportassi publik di Provinsi Jakarta, Indonesia. Project ini menggunakan data spasial kecamatan di Provinsi Jakarta dan GTFS (General Transit Feed Specification) format. Peta ini dapat digunakan untuk mengetahui kecamatan mana saja di Provinsi Jakarta yang memiliki kecangkupan dan akses terhadap fasilitas transportasi publik.  

🎯 Objectives:
- Konversi data GTFS menjadi titik
- Memvisualisasikan pemberhentian fasilitas transportasi publik
- Melakukan buffer pada titik pemeberhentian fasilitas berjarak 500 meter
- Melakukan overlay pada buffer coverage dengan batas administrasi provinsi 
- Menghitung presentasi area yang tercangkup transportasi publik
- Memvisualisasikan hasil analisis berupa peta

🛠️ Technologies Used:
- Python: GeoPandas, Pandas, Matplotlib
- GTFS: stops.txt, routes.txt, trips.txt (custom-built)
- OpenStreetMap: Base map and road network reference

📈 Expected Outcomes:
- Lapisan spasial yang menunjukkan area cakupan yang dapat dilalui pejalan kaki dari halte transportasi
- Peta koroplet yang memvisualisasikan persentase cakupan per lingkungan
- Laporan CSV yang merangkum area yang kurang terlayani
- Rekomendasi untuk perluasan rute dan penempatan halte

📦 Use Cases:
- Perencanaan kota dan analisis kebijakan transportasi yang berkeadilan
- Studi aksesibilitas transportasi
- Mendukung inisiatif mobilitas berkelanjutan dan kota pintar
