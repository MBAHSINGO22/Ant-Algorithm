<h1 align="center">Implementasi Algoritma Ant Colony Optimization (ACO)</h1>

<hr>

<h2>📌 Deskripsi</h2>

<p>
Project ini merupakan implementasi algoritma Ant Colony Optimization (ACO) menggunakan bahasa Python.
Algoritma ACO terinspirasi dari perilaku koloni semut dalam mencari jalur tercepat menuju sumber makanan menggunakan jejak feromon.
</p>

<p>
Pada project ini, algoritma digunakan untuk mencari rute optimal berdasarkan nilai jarak antar node atau kota.
</p>

<hr>

<h2>🛠 Teknologi yang Digunakan</h2>

<ul>
  <li>Python</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>✨ Fitur</h2>

<ul>
  <li>Implementasi algoritma Ant Colony Optimization</li>
  <li>Perhitungan probabilitas jalur semut</li>
  <li>Pembaruan nilai feromon</li>
  <li>Pencarian jalur optimal</li>
  <li>Visualisasi hasil pencarian rute</li>
  <li>Simulasi pergerakan semut</li>
</ul>

<hr>

<h2>⚙️ Cara Kerja Algoritma</h2>

<ol>
  <li>Inisialisasi node dan matriks jarak</li>
  <li>Inisialisasi nilai feromon</li>
  <li>Semut memilih jalur berdasarkan probabilitas</li>
  <li>Semut menyelesaikan perjalanan</li>
  <li>Feromon diperbarui berdasarkan kualitas jalur</li>
  <li>Iterasi dilakukan hingga mendapatkan jalur terbaik</li>
</ol>

<hr>

<h2>📂 Struktur Project</h2>

<pre>
project-folder/
│
├── ACO.ipynb
└── README.md
</pre>

<hr>

<h2>🚀 Instalasi</h2>

<p>Clone repository:</p>

<pre>
git clone https://github.com/username/nama-repository.git
</pre>

<p>Install dependency:</p>

<pre>
pip install numpy matplotlib
</pre>

<hr>

<h2>▶️ Cara Menjalankan</h2>

<ol>
  <li>Buka file <b>ACO.ipynb</b> menggunakan Jupyter Notebook atau Google Colab</li>
  <li>Jalankan seluruh cell program</li>
  <li>Lihat proses pencarian jalur optimal</li>
  <li>Amati hasil visualisasi algoritma</li>
</ol>

<hr>

<h2>💻 Contoh Kode</h2>

<pre>
pheromone = np.ones((num_nodes, num_nodes))

probability = (pheromone[current_node] ** alpha) * ((1 / distance[current_node]) ** beta)
</pre>

<hr>

<h2>👨‍💻 Author</h2>

<p>
Eugenius Kriswinar Adi Cahya
</p>

<hr>

<h2>📄 License</h2>

<p>
Project ini dibuat untuk kebutuhan pembelajaran dan penelitian.
</p>
