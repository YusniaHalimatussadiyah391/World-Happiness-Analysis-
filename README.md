# World Happiness Report 2015

## Overview
Kebahagiaan adalah kondisi emosional yang dicirikan oleh perasaan senang, kepuasan, dan kepuasan diri. Meskipun ada banyak definisi kebahagiaan, itu sering dianggap sebagai sesuatu yang melibatkan perasaan positif dan kepuasan dalam kehidupan.

Laporan Kebahagiaan Dunia adalah studi penting tentang keadaan kebahagiaan di seluruh dunia. Laporan ini memberikan peringkat kepada 149 negara berdasarkan tingkat kebahagiaan yang dialami oleh penduduknya. Peringkat ini didasarkan pada sejumlah faktor termasuk pertumbuhan ekonomi, dukungan sosial, harapan hidup, kebebasan untuk membuat pilihan hidup, kedermawanan, dan persepsi korupsi. Laporan ini diterbitkan setiap tahun oleh Perserikatan Bangsa-Bangsa.

Dalam proyek analisis ini, kami akan mengeksplorasi dataset Laporan Kebahagiaan Dunia 2015 dengan menggunakan library Python untuk ilmu data seperti Pandas, NumPy, Matplotlib, dan Seaborn, dengan tujuan memvisualisasikan data melalui plot dan grafik guna membantu pemahaman data dan memberikan wawasan yang lebih mendalam tentang faktor-faktor yang memengaruhi kebahagiaan secara global. Dataset ini mencakup skor kebahagiaan dan berbagai indikator sosio-ekonomi untuk negara-negara di seluruh dunia.
## Descriptive Analysis
### ✨Dataset✨
#### Data Preparation adn Exploration
Dataset dari tahun 2015 dimuat dan diperiksa untuk eksplorasi awal. Data ini terdiri dari 158 dan 12 kolom
Skor Kebahagiaan dijelaskan oleh beberapa faktor berikut:
| Variabel | Penjelasan |
| ------ | ------ |
| Country | daftar nama negara yang terdapat dalam dataset |
| Region | klasifikasi geografis atau regional di mana suatu negara berada |
| Happiness Rank | peringkat kebahagiaan suatu negara dalam suatu periode waktu |
| Happiness Score | nilai atau skor yang menunjukkan tingkat kebahagiaan suatu negara dalam suatu periode waktu |
| Standard Error | ukuran variabilitas atau ketidakpastian dari Happiness Score suatu negara dalam suatu periode waktu tertentu. |
| GDP per capita | nilai ekonomi suatu negara per individu |
| Healthy Life Expectancy | angka harapan hidup sehat adalah rata-rata usia hidup dalam kondisi sehat |
| Social support | dukungan sosial mengacu pada bantuan atau dukungan yang diberikan oleh jaringan sosial kepada seseorang |
| Freedom to make life choices | kebebasan untuk membuat pilihan hidup |
| Generosity | kedermawanan dari respons terhadap pertanyaan GWP “Apakah Anda menyumbangkan uang ke badan amal dalam sebulan terakhir?” pada PDB per kapita |
| Corruption Perception | Ukurannya adalah rata-rata nasional dari respons survei terhadap dua pertanyaan dalam GWP: “Apakah korupsi tersebar luas di seluruh pemerintahan atau tidak” dan “Apakah korupsi tersebar luas di dunia usaha atau tidak?” |
| Dystopia Residual | nilai yang digunakan dalam model untuk mengukur tingkat ketidakberdayaan atau ketidaksempurnaan di luar faktor-faktor yang diukur dalam survei kebahagiaan |
#### Prepocessing
- checking missing value
- checking duplicate data
- rename columns
#### Exploratory Data Analysis
- Mengeksplorasi distribusi skor kebahagiaan dan variabel lainnya.
- Memvisualisasikan hubungan antar variabel menggunakan plot pasangan dan peta panas.
- Menganalisis variasi regional dalam skor kebahagiaan dan indikator ekonomi.

## Insight
1. Regional Happiness Variation
- Negara-negara Eropa Barat cenderung memiliki skor kebahagiaan yang lebih tinggi dibandingkan dengan wilayah lain, diikuti oleh Amerika Utara dan Australia/Selandia Baru.
- Afrika Selatan dan Asia Selatan menunjukkan skor kebahagiaan rata-rata yang lebih rendah dibandingkan dengan wilayah lain.
2. Economic Factors
- PDB per kapita berkorelasi positif dengan skor kebahagiaan di sebagian besar wilayah, yang mengindikasikan pengaruh ekonomi yang kuat terhadap kesejahteraan.
- Namun, beberapa wilayah, seperti Afrika Selatan, menunjukkan skor kebahagiaan yang lebih rendah meskipun PDB per kapita relatif tinggi.
3. Social - economic Factors
- Dukungan sosial (Keluarga), kesehatan (Angka Harapan Hidup), dan kebebasan secara signifikan berkontribusi terhadap skor kebahagiaan di seluruh wilayah.
- Kepercayaan terhadap pemerintah (Korupsi Pemerintah) menunjukkan variasi antar wilayah dan berkorelasi dengan kebahagiaan sampai batas tertentu.
