# German-Credit-Risk
![p](https://camo.githubusercontent.com/9d65cea2c05fe93a89a24c9d4740c4bdb2254ecf7cfbb63e11bce7d0b7d144eb/68747470733a2f2f69322e77702e636f6d2f746865706f696e74736775792e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032392f30342f5450472d554b2d4c61756e63682d436172647346616e6e696e672d30322e6769663f77696474683d32303030266865696768743d31303530266174746163686d656e745f69643d3638323338352673736c3d31)

## Table of Contents

- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Analytical Approach](#analytical-approach)
- [Definisi Kolom](#definisi-kolom)
- [Data Analyst & Clustering](#data-analyst)
  - [Kesimpulan](#kesimpulan)
  - [Saran](#saran)
- [Others Project](#others-project)

### **Problem Statement**
Analisis data adalah proses menganalisis data mentah untuk menarik informasi dan membuat kesimpulan tentang data tersebut. Analisis data adalah bidang penting dalam ilmu data karena membantu bisnis mengoptimalkan kinerjanya. Analisis data membantu bisnis mengurangi biaya dan meningkatkan efisiensi bisnis secara keseluruhan.

Ketika bank menerima aplikasi pinjaman, bank harus membuat keputusan apakah akan melanjutkan persetujuan pinjaman atau tidak. Bank membuat keputusan pinjaman berdasarkan profil pemohon. Dua jenis risiko terkait dengan keputusan bank.

Jika pemohon adalah risiko kredit yang baik, yaitu kemungkinan untuk membayar kembali pinjaman, maka tidak menyetujui pinjaman kepada orang tersebut mengakibatkan hilangnya bisnis ke bank, Jika pemohon adalah risiko kredit yang buruk, yaitu tidak mungkin untuk membayar kembali pinjaman, maka menyetujui pinjaman kepada orang tersebut mengakibatkan kerugian finansial bagi bank.

### **Objectives**
Tujuan dari Analisis Data Kredit Jerman adalah untuk meminimalkan kemungkinan mengeluarkan pinjaman berisiko kepada pemohon sambil memaksimalkan peluang untuk mendapatkan keuntungan dari pinjaman yang baik. Profil demografis dan sosial-ekonomi pemohon dipertimbangkan oleh manajer pinjaman sebelum keputusan diambil mengenai permohonan pinjamannya dengan cara memberikan gambaran tentang profil nasabah yang melakukan pinjaman uang di bank serta memberikan saran kepada manager terkait profil nasabah yang menguntungkan.

### **Analytical Approach**
- Pendekatan analisa ini dengan cara melakukan pembagian variabel pada saat dilakukan Exploratory Data Analyst dan Pengelompokan Konsumen :
  - Melakukan Exploratory Data Analyst terhadap seluruh variabel yang ada untuk mengetahui karakteristik pelanggan yang berbelanja dan berkunjung ke mall.
  - Melakukan pengelompokan konsumen berdasarkan Umur, Gender, Annual Income dan Spending Score dengan menggunakan Machine Learning Unsupervised (Clustering).

### **Definisi Kolom**
| **Nama Kolom** |**Keterangan Kolom** |
| --- | --- |
|Age| Umur Customer|
|Sex| Gender Customer|
|Job| Pekerjaan Customer|
|Housing| Jenis tempat tinggal|
|Saving accounts| Tingkatan Rekening Tabungan|
|Cheking accounts| Tingkatan Rekening Check|
|Credit amount| Total Pinjaman|
|Duration| Durasi Pinjaman|
|Purpose| Tujuan Pinjaman|

## Data Analyst & Clustering

### **Kesimpulan**

  - Cluster 0 : Banyak nasabah berumur remaja < 25 tahun dengan jenis kelamin laki laki yang mengajukan pinjaman dan sudah bekerja. Mereka memiliki tempat tinggal pribadi namun sebagian besar nasabah memiliki pinjaman dibank masuk kategori `little / sedikit` dan pengajuan pinjaman untuk nasabah cluster 0 ini paling banyak ada pada 12 bulan dengan tujuan pinjaman pembelian radio/tv, furniture rumah serta mobil dengan total pinjaman tertinggi 1200 USD.
  #
  - Cluster 1 : Banyak nasabah yang berumur dewasa (>25 tahun dan < 35 tahun) dengan jenis kelamin laki laki yang mengajukan pinjaman dan sudah bekerja. Mereka memiliki tempat tinggal pribadi sebagian besarnya dengan total tabungan di bank termasuk kategori `little / sedikit` dan pengajuan pinjaman untuk nasabah cluster 1 ini paling banyak 24 bulan lamanya dengan tujuan paling banyak ada untuk pembelian mobil, radio/tv dan untuk bisnis dengan total pinjaman paling besar mencapai 2000 USD.
  #
  - Cluster 2 : Banyak Nasabah yang berumus dewasa  (>25 tahun dan < 35 tahun) dengan jenis kelamin laki laki yang mengajukan pinjaman dan sudah bekerja. Mereka memiliki tempat tinggal pribadi sebagian besarnya dengan total tabungan di bank termasuk kategori `little / sedikit` dan pengajuan pinjaman untuk nasabah cluster 2 ini paling banyak 36 bulan lamanya dengan tujuan paling banyak ada untuk pembelian mobil, furniture dan untuk radio/tv dengan total pinjaman paling besar mencapai lebih dari 4000 USD.
  
## **Saran**
  - Saran kepada manager bank, pinjaman dapat diperioritaskan pada nasabah yang masuk dalam clustering 1 dengan kriteria nasabah 25-35 tahun, memiliki pekerjaan tetap dan memiliki simpanan tabungan. Selain itu pinjaman yang diajukan nasabah ini jika dibandingkan dengan nasabah lain paling menguntungkan untuk bank dan tingkat pembayaran yang dilakukan nasabah kecil dari resiko. Hal ini seperti perhitungan berikut
    - Secara hitungan :
      - Nasabah 1 : Pinjaman 2.000 USD / 24 Bulan = 83 Dollar nasabah harus membayar kepada bank, 
      - Nasabah 0 : Pinjaman 1.200 USD / 12 bulan = 100 Dollar nasabah harus membayar kepada bank,
      - Nasabah 2 : Pinjaman 4.000 USD / 36 bulan = 111 Dollar nasabah harus membayar kepada bank.
  - Dari perhitungan di atas dapat dilihat, nasabah yang masuk dalam cluster 1 memiliki total pembayaran pinjaman yang paling kecil kepada perbankan, dengan total simpanan tabungannya yang kecil kemungkinan hal ini tidak memberatkan nasabah dalam melakukam pembayaran bulanannya serta dari perbankan tetap bisa menjalankan bisnis dengan memberikan pinjaman kepada nasabah yang berjumlah berkisar diatas 1200 - 2000 USD dengan total jangka waktu pembayaran 24 bulan.

<br>

# Others Project

**My Project :** [Data Analyst](#data-analyst) | [Machine Learning](#machine-learning) | [Data Visualization](#data-visualization)

**Tech stacks currently using** <br>

<code><a href="https://code.visualstudio.com/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/visualstudio_code/visualstudio_code-ar21.svg"></a></code>
<code><a href="https://jupyter.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/jupyter/jupyter-ar21.svg"></a></code>
<code><a href="https://www.python.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></a></code>
<code><a href="https://www.mysql.com/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/mysql/mysql-ar21.svg"></a></code>
<code><a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank"><img height="50" src="https://cdn.worldvectorlogo.com/logos/microsoft-sql-server-1.svg"></a></code>
<code><a href="https://www.postgresql.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/postgresql/postgresql-ar21.svg"></a></code>
<code><a href="https://powerbi.microsoft.com/en-us/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/microsoft_powerbi/microsoft_powerbi-ar21.svg"></a></code>
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147" target="_blank"><img height="30" src="https://cdn.worldvectorlogo.com/logos/tableau-logo.svg"></a></code>
<br>
<br>
<table>
<tbody>
 <tr>

<h1 align="left">Data Analyst</h1>
  
<td align="left" width="50%">
<span><b><Left>E-Commers Pakistan</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/EDA---Pakistan-s-Larges-Ecommers" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/EDA---Pakistan-s-Larges-Ecommers/blob/main/Images/62253a402fccf.jpg"> 
</td>
<!-- <tr> -->
<td align="left" width="50%">
<span><b><Left>Employee Attrition</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Employee-Analysis-Attrition-Report" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/Employee-Analysis-Attrition-Report/blob/main/Aset/Reasons-Attrition1_large%20(1).jpg"> 
</td>
</tbody>
</table>
 <tr>
<br>
<table>
<tbody>
 <tr>
 
<h1 align="left">Machine Learning - Supervised</h1>

<td align="left" width="20%">
<span><b><left>California House Price</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/California-House-Price-Prediction-Using-Machine-Learning" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/California-House-Price-Prediction-Using-Machine-Learning/blob/main/gambar/CA-Sales-Home-Volume.png"> 
</td>

<td align="left" width="20%">
<span><b><left>Credit Card Fraud</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Credit-Card-Fraud-Prediction" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/Credit-Card-Fraud-Prediction/blob/main/68747470733a2f2f65787465726e616c2d636f6e74656e742e6475636b6475636b676f2e636f6d2f69752f3f753d687474707325334125324625324661692d6a6f75726e65792e636f6d25324677702d636f6e74656e7425324675706c6f61647325324632303139253246.jfif"> 
</td>

<!-- <tr> -->
<td align="left" width="20%">
<span><b><left>Telco Customer Churn</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Employee-Promotion" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/7-Strategies-To-Reduce-Customer-Churn-Rate.png"> 
</td>

<!-- <tr> -->
<td align="left" width="20%">
<span><b><left>Employee Promotion</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Telco-Customer-Churn-Predict" target="_blank">
<img height=150px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/advance-career.jpg"> 
</td>

</tbody>
</table>
 <tr>
  
<h1 align="left">Machine Learning - Unsupervised</h1>  

<table>
<tbody>
 <tr>  
  
<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation Customer Mall</center></b></span> 
<code><a href="https://github.com/mhdalfarisy/Segmentation-Customer-Mall" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/Segmentation-Customer-Mall/blob/main/2.-Customer-Segmentation.jpg"> 
</td>
 
<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation Customer Supermarket</center></b></span>
<code><a href="https://github.com/mhdalfarisy/Customer-Supermarket" target="_blank">
<img height=250px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/istockphoto-1254636143-612x612.jpg"> 
</td> 

<!-- <tr> -->
<td align="center" width="30%">
<span><b><left>Segmentation German Credit Risk</center></b></span>
<code><a href="https://github.com/mhdalfarisy/German-Credit-Risk" target="_blank">
<img height=250px src="https://media.istockphoto.com/vectors/banking-credit-card-vector-id1353716726?b=1&k=20&m=1353716726&s=612x612&w=0&h=qkwNRlcHCDUxeSgVYau8FczoM6x0sl693nvjAAcRmio="> 
</td> 
 
</tbody>
</table>
 <tr>
  
<br>

<table>
<tbody>
 <tr>

<h1 align="left">Data Visualization</h1>
  
<td align="left" width="20%">
<span><b><Left>E-Commers Pakistan</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/ProjectE-CommersPakistanDashboard/Dashboard1" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/Pakistan%20Visualisasi.png"> 
</td>
 
<!-- <tr> -->
<td align="left" width="30%">
<span><b><left>Employee Attrition Report</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/ProjectHumanResourceAttritionAnalysisDashboard/Dashboard1" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/HRD%20VIsualisasi.png"> 
</td>
 
<!-- <tr> -->
<td align="left" width="25%">
<span><b><left>Telco Customer Churn</center></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147/viz/CustomerChunVisualization/Dashboard2?publish=yes" target="_blank">
<img height=200px src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/Telco%20Customer%20Churn.png"> 
</td>
 
</tbody>
</table>
 <tr>



<br>
<!-- <h1 align="center">Others Data Visualization Report</h1> -->
<td align="left" width="30%">
<span><b><left>Others Data Visualization Report (Click Picture) :   </left></b></span> 
<code><a href="https://public.tableau.com/app/profile/muhammad.al.farisy6147" target="_blank"><img height="100" src="https://github.com/mhdalfarisy/mhdalfarisy/blob/main/tol_devices_optimized.png"></a></code>
<br>
<br>
<br>
 
**💬 Ask me about anything, I'll be happy to help!** <br>
**💬 My inbox is always open, Contact me**
<br>
<br> 
  </a>
  <a href="mailto:m.alfarisy797@gmail.com">
    <img align="left" alt="Muhammad Al-farisy | Gmail" width="26px" src="https://cdn.worldvectorlogo.com/logos/official-gmail-icon-2020-.svg" />
  </a>
  <a href="https://www.linkedin.com/in/m-alfarisy97/">
    <img align="left" alt="Muhammad Al-farisy | LinkedIN" width="26px" src="https://cdn.worldvectorlogo.com/logos/linkedin-icon-2.svg" />    
  </a>
<br>
<br>


| <a href="https://github.com/mhdalfarisy"><img align="center" src="https://github-readme-stats.vercel.app/api?username=mhdalfarisy&show_icons=true&include_all_commits=true&theme=buefy&hide_border=true" alt="Anurag's github stats" /></a> | <a href="https://github.com/mhdalfarisy/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mhdalfarisy&layout=compact&theme=buefy&hide_border=true" /></a> |
| ------------- | ------------- |
 
<table>
<tbody>
 <tr>
 
<h1 align="left">THANKS YOU !!! </h1>

<td align="center" width="30%">
<img height=300px src="https://media.giphy.com/media/dyzew7Py7bnW9DiJJj/giphy.gif"> 
</td>  
  
<!-- <td align="center" width="30%">
<img height=300px src="https://media.giphy.com/media/7c8QeB0VMddFOuu4iR/giphy.gif"> 
</td>
  
<td align="right" width="30%">
<img height=300px src="https://media.giphy.com/media/gutZ5Pm6Xl62eIf5RZ/giphy.gif"> 
</td>    -->

⭐️ From [Muhammad Al-farisy](https://github.com/mhdalfarisy)
