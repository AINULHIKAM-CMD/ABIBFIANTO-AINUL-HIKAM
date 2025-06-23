# ABIBFIANTO-AINUL-HIKAM <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abibfianto Ainul Hikam - Profesional Agribisnis</title>
    <style>
        :root {
            --primary-color: #2e7d32;
            --secondary-color: #81c784;
            --light-color: #f1f8e9;
            --dark-color: #1b5e20;
            --text-color: #333;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        
        header p {
            margin: 0.5rem 0 0;
            font-size: 1.2rem;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            margin-top: 1rem;
        }
        
        section {
            padding: 2rem 0;
            border-bottom: 1px solid #eee;
        }
        
        section:last-child {
            border-bottom: none;
        }
        
        h2 {
            color: var(--dark-color);
            position: relative;
            padding-bottom: 0.5rem;
        }
        
        h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background-color: var(--secondary-color);
        }
        
        .education-item, .experience-item, .organization-item {
            margin-bottom: 1.5rem;
        }
        
        .education-item h3, .experience-item h3, .organization-item h3 {
            margin-bottom: 0.3rem;
            color: var(--primary-color);
        }
        
        .date {
            color: #666;
            font-style: italic;
            margin-bottom: 0.5rem;
        }
        
        ul {
            padding-left: 20px;
        }
        
        li {
            margin-bottom: 0.3rem;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        
        .skill-category {
            flex: 1;
            min-width: 250px;
            background-color: white;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .skill-category h3 {
            color: var(--dark-color);
            border-bottom: 2px solid var(--light-color);
            padding-bottom: 0.5rem;
            margin-top: 0;
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 1rem;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
        }
        
        .contact-info a:hover {
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .skills {
                flex-direction: column;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 0.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <!-- Ganti dengan foto Anda -->
            <img src="profile-placeholder.jpg" alt="Abibfianto Ainul Hikam" class="profile-img">
            <h1>Abibfianto Ainul Hikam</h1>
            <p>Lulusan Agribisnis | Quality Control | Pengembangan Bisnis | Hubungan Masyarakat</p>
        </div>
    </header>
    
    <main class="container">
        <section id="about">
            <h2>Tentang Saya</h2>
            <p>Lulusan Sarjana Agribisnis dari Universitas Wijaya Kusuma Surabaya dengan kompetensi besar di bidang quality control, pengembangan bisnis, dan hubungan masyarakat. Saya memiliki kemampuan komunikasi yang efektif dan mampu menjalin hubungan baik dengan pihak eksternal. Selama masa kuliah, saya aktif di organisasi Departemen Hubungan Masyarakat dan mampu bekerja sama dalam tim.</p>
        </section>
        
        <section id="education">
            <h2>Pendidikan</h2>
            <div class="education-item">
                <h3>Universitas Wijaya Kusuma Surabaya</h3>
                <p>S1 - Agribisnis (Pertanian)</p>
                <p class="date">2021 - 2025 | IPK: 3.64/4.00</p>
                <p><strong>Mata Kuliah Relevan:</strong> Dasar Dasar Manajemen, Manajemen Sumber Daya Manusia, Penyuluhan dan Pemberdayaan, Pembangunan Pertanian Berkelanjutan, Komunikasi Agribisnis</p>
            </div>
        </section>
        
        <section id="experience">
            <h2>Pengalaman Kerja</h2>
            <div class="experience-item">
                <h3>PT Miwon Indonesia</h3>
                <p>Helper Gudang</p>
                <p class="date">[Tanggal kerja]</p>
                <ul>
                    <li>Memasukkan Barang Produksi ke Gudang</li>
                    <li>Memastikan Stock Barang di Gudang sesuai dengan Sistem</li>
                    <li>Bertanggung Jawab atas Kebersihan Gudang</li>
                </ul>
            </div>
            
            <div class="experience-item">
                <h3>Kampoeng Roti</h3>
                <p>Produksi</p>
                <p class="date">[Tanggal kerja]</p>
                <ul>
                    <li>Mencegah terjadinya waste dengan memastikan proses produksi dijalankan sesuai prosedur</li>
                    <li>Memastikan kualitas bahan baku yang digunakan sesuai standar</li>
                    <li>Menjalankan Prosedur Keamanan Pangan</li>
                    <li>Bertanggung jawab atas ketepatan waktu dan kuantitas hasil produksi</li>
                </ul>
            </div>
        </section>
        
        <section id="internship">
            <h2>Pengalaman Magang</h2>
            <div class="experience-item">
                <h3>PT. Tritani Agri Jaya Surabaya</h3>
                <p class="date">[Tanggal magang]</p>
                <ul>
                    <li>Menguasai sistem produksi pertanian, khususnya pada hidroponik dan budidaya melon</li>
                    <li>Melayani customer dengan berkomunikasi yang efektif</li>
                    <li>Mampu mengidentifikasi dan mengantisipasi setiap kegagalan pembudidayaan</li>
                    <li>Bertanggung jawab penuh pada penanaman, perawatan sampai penjualan terhadap komoditas pertanian</li>
                    <li>Menjadi pemandu dalam workshop "cara mudah berkebun dengan hidroponik di rumah"</li>
                    <li>Berkontribusi dalam lomba "Kampung Surabaya Sehat"</li>
                    <li>Berkontribusi dalam proyek kebun rooftop di BAPPEDA JATIM</li>
                    <li>Bertanggung jawab dalam branding perusahaan melalui media sosial seperti TikTok dan Instagram</li>
                </ul>
            </div>
        </section>
        
        <section id="organization">
            <h2>Pengalaman Organisasi</h2>
            <div class="organization-item">
                <h3>Badan Eksekutif Mahasiswa Fakultas Pertanian (BEM-FP)</h3>
                <p>Anggota - Departemen Humas</p>
                <p class="date">Juli 2023 - Juli 2024</p>
                <ul>
                    <li>Menjalin hubungan baik dengan pihak internal maupun eksternal</li>
                    <li>Menjadi ketua pelaksana proker Latihan Keterampilan Manajemen Mahasiswa-Tingkat Dasar (LKMM-TD)</li>
                    <li>Bertanggung jawab penuh pada citra dan reputasi positif organisasi melalui sosial media</li>
                </ul>
            </div>
            
            <div class="organization-item">
                <h3>Himpunan Mahasiswa Agribisnis (HIMAGRI)</h3>
                <p>Anggota - Departemen Penalaran</p>
                <p class="date">Juli 2022 - Juli 2023</p>
                <ul>
                    <li>Membantu ketua departemen dalam pengembangan pemikiran pada anggota organisasi maupun mahasiswa agribisnis</li>
                    <li>Terlibat dalam kepanitiaan proker PKKMB 2022 dan LKMM-TD 2022 sebagai anggota divisi dokumentasi dan anggota divisi Koordinasi Lapangan</li>
                </ul>
            </div>
        </section>
        
        <section id="skills">
            <h2>Keterampilan</h2>
            <div class="skills">
                <div class="skill-category">
                    <h3>Soft Skills</h3>
                    <ul>
                        <li>Mampu menjalin hubungan baik</li>
                        <li>Detail Oriented</li>
                        <li>Public Speaking</li>
                        <li>Problem Solving</li>
                        <li>Adaptif dan Asertif</li>
                        <li>Teliti dan Cekatan</li>
                        <li>Komunikasi yang Efektif</li>
                        <li>Mampu Bekerja Sama dalam Tim</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Hard Skills</h3>
                    <ul>
                        <li>Microsoft Office</li>
                        <li>Google Workspace</li>
                        <li>Canva, Capcut dan Corel</li>
                        <li>Mampu menyusun dan mengelola suatu program kerja dengan baik</li>
                        <li>Mengkoordinir proses penyelesaian permasalahan di organisasi maupun tim</li>
                    </ul>
                </div>
            </div>
        </section>
    </main>
    
    <footer>
        <div class="container">
            <h2>Hubungi Saya</h2>
            <div class="contact-info">
                <a href="mailto:abibfiantoainulhikam@gmail.com">abibfiantoainulhikam@gmail.com</a>
                <p>Sidoarjo, Indonesia</p>
            </div>
        </div>
    </footer>
</body>
</html>
