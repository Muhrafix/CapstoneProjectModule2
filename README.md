# Capstone Project Module 2: Data Analysis
Pada Capstone ini saya akan membahas analisa sebuah dataset yang diambil dari kaggle yang bersama **TSA Claims Database** (dataset dapat diakses melalui [link ini](https://www.kaggle.com/datasets/terminal-security-agency/tsa-claims-database)). Berikut adalah summary dari analisa tersebut:
<br>
TSA (Transportation Security Administration) merupakan sebuah agensi bagian dari Departemen *Homeland Security* Amerika Serikat yang mempunyai otoritas atas keamanan sistem transportasi baik di dalam, maupun yang berhubungan dengan Amerika Serikat. TSA Mengembangkan banyak kebijakan-kebijakan untuk melindungi sistem transportasi Amerika Serikat. Fokus utama dari TSA sendiri adalah mengenai **keamanan bandara**. TSA bertanggung jawab atas pemeriksaan penumpang dan bagasi di lebih dari 450 bandara di Amerika Serikat. TSA mencatat setiap klaim yang diajukan oleh para pengguna moda transportasi tersebut. Dengan adanya data klaim yang diajukan kepada TSA tersebut, TSA memiliki rekam jejak atas setiap kasus-kasus yang terjadi dan data tersebut dapat digunakan oleh TSA sebagai acuan untuk terus dapat meningkatkan kinerjanya.

Dengan adanya data klaim tersebut TSA ingin mengetahui bandara mana saja yang memiliki jumlah pengajuan klaim terbanyak. Informasi ini dapat membantu TSA dalam mengerucutkan bandara-bandara mana saja yang membutuhkan peningkatan kinerja sistem keamanannya, sehingga dapat mengurangi frekuensi klaim yang diajukan kepada TSA.

Sebagai *data analyst* saya akan berusaha menjawab pertanyaan berikut:

**Bagaimana karakteristik data pengajuan klaim yang dibuat oleh para penumpang?**

Dari pernyataan masalah di atas, saya akan mencoba membedah lebih mendalam kepada beberapa masalah, yaitu:
- Apa saja bandara yang memiliki jumlah pengajuan klaim dengan proporsi cukup besar (di atas rata-rata)?
- Apa tipe klaim yang paling sering dilaporkan oleh penumpang?
- Dimana saja titik yang paling sering terjadi pelaporan klaim tersebut?
- Bagaimana grafik jumlah klaim selama rentang tahun 2002-2015?

Dalam menjawab pertanyaan di atas, saya melakukan serangkaian analisa descriptive statistic. Namun sebelum melakukan analisa terhadap data, terlebih dahulu saya melakukan tahapan *data understanding* dan data cleaning*. Hal ini dilakukan supaya data benar-benar siap untuk dilakukan analisa secara mendalam.

Setelah dilakukan analisa, berikut adalah sejumlah insight yang dapat diambil:

1. Bandara **LAX** (Los Angeles International Airport) menjadi bandara dengan total klaim tertinggi, diikuti oleh Bandara **JFK** (John F. Kennedy International Airport) dan bandara **ORD** (Chicago O'Hare International Airport).

2. Mayoritas bandara yang memiliki total klaim di atas rata-rata, termasuk ke dalam bandara-bandara tersibuk di Amerika Serikat.

3. Tipe klaim ***Passenger Property Loss*** dan ***Property Damage*** menjadi tipe klaim dengan proporsi terbanyak. Kedua tipe klaim itu pun tetap menjadi yang terbanyak ketika dicek berdasarkan jumlah tiap tipe klaim di setiap bandara.

4. Lokasi claim ***Checked Baggage*** dan ***Checkpoint*** menjadi lokasi klaim dengan proporsi terbanyak. Hal ini disebabkan karena kedua titik tersebut merupakan titik dengan tingkat aktivitas dan kepadatan tertinggi di suatu bandara. Namun perlu diperhatikan untuk ***Checked Baggage***, maskapai penerbangan juga turut andil selama barang tersebut berada di dalam pesawat.

5. Mayoritas maskapai yang memiliki jumlah klaim ***Checked Baggage*** terbanyak turut masuk ke dalam maskapai terpopuler (sering digunakan) di AS.

6. Tahun 2002 menjadi tahun dengan data klaim terendah, dengan lonjakan cukup tinggi ada pada tahun 2004 dan total klaim cenderung menurun pada tahun-tahun berikutnya.
