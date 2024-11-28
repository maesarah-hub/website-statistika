<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengenalan Statistik - Kelas 8</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Mengatur desain global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa;
            padding: 20px;
        }

        .container {
            width: 85%;
            margin: 30px auto;
            padding: 30px;
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #007bff;
            text-align: center;
            font-size: 3em;
            margin-bottom: 30px;
            font-weight: bold;
        }

        h2 {
            color: #343a40;
            font-size: 1.8em;
            margin-top: 20px;
            margin-bottom: 15px;
            font-weight: 600;
        }

        p, ul {
            font-size: 1.1em;
            line-height: 1.8;
            color: #495057;
        }

        ul {
            margin-top: 10px;
            margin-left: 30px;
        }

        .stat-image {
            width: 100%;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }

        .quote {
            font-style: italic;
            color: #6c757d;
            border-left: 6px solid #007bff;
            padding-left: 15px;
            margin: 25px 0;
            font-size: 1.2em;
        }

        .interactive {
            background-color: #e9ecef;
            padding: 20px;
            border-radius: 8px;
            margin-top: 30px;
        }

        .interactive h3 {
            font-size: 1.5em;
            font-weight: 600;
            margin-bottom: 20px;
        }

        .fun-fact {
            color: #28a745;
            font-weight: bold;
            font-size: 1.1em;
        }

        .navbar {
            background-color: #007bff;
            border-radius: 8px;
        }

        .navbar-nav .nav-link {
            color: #ffffff;
            padding: 12px 20px;
            font-size: 1.1em;
        }

        .navbar-nav .nav-link:hover {
            background-color: #0056b3;
            border-radius: 8px;
        }

        .footer {
            text-align: center;
            font-size: 1em;
            color: #6c757d;
            margin-top: 50px;
        }

        /* Responsif */
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }
            h1 {
                font-size: 2.5em;
            }
            h2 {
                font-size: 1.6em;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar Responsif -->
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
            <a class="navbar-brand" href="tugas1web.html">STATISTIKA</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="materi-statistika.html">MATERI</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="media-statistika.html">MEDIA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="lk-statitika.html">LEMBAR KERJA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="tgs-statistika.html">TUGAS</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container">
        <h1>Pengenalan Statistik</h1>
        <img src="statistika.jpeg" alt="Statistik" class="stat-image">

        <h2>Apa itu Statistik?</h2>
        <p>Statistik adalah cabang ilmu yang mempelajari pengumpulan, analisis, interpretasi, presentasi, dan organisasi data. Dalam kehidupan sehari-hari, statistik membantu kita memahami informasi dan membuat keputusan yang lebih baik berdasarkan data yang ada.</p>

        <h2>Tujuan Statistik</h2>
        <ul>
            <li>Menganalisis data untuk menemukan pola atau tren.</li>
            <li>Membantu dalam pengambilan keputusan yang lebih tepat.</li>
            <li>Memberikan gambaran yang jelas tentang populasi atau fenomena.</li>
        </ul>

        <h2>Jenis-Jenis Statistik</h2>
        <p>Statistik dibagi menjadi dua jenis utama:</p>
        <ul>
            <li><strong>Statistik Deskriptif:</strong> Ini digunakan untuk mendeskripsikan dan merangkum data. Contoh: rata-rata, median, modus.</li>
            <li><strong>Statistik Inferensial:</strong> Ini digunakan untuk menarik kesimpulan atau membuat prediksi berdasarkan sampel data. Contoh: estimasi parameter populasi.</li>
        </ul>

        <h2>Contoh Penggunaan Statistik</h2>
        <p>Statistik diterapkan dalam berbagai bidang, antara lain:</p>
        <ul>
            <li><strong>Pendidikan:</strong> Menganalisis hasil ujian untuk mengetahui tingkat pemahaman siswa.</li>
            <li><strong>Kesehatan:</strong> Mengumpulkan data untuk memantau kesehatan masyarakat dan epidemi.</li>
            <li><strong>Bisnis:</strong> Menggunakan survei untuk memahami preferensi pelanggan.</li>
        </ul>

        <div class="interactive">
            <h3>Ayo Coba Hitung!</h3>
            <p>Jika kamu memiliki nilai ujian sebagai berikut: 80, 90, 70, 85, dan 95. Cobalah untuk menghitung:</p>
            <ul>
                <li>Rata-rata nilai.</li>
                <li>Median nilai.</li>
                <li>Modus nilai.</li>
            </ul>
            <p class="fun-fact">Fakta Menarik: Rata-rata nilai bukanlah satu-satunya cara untuk memahami data. Cobalah untuk menganalisis median dan modus juga!</p>
        </div>

        <div class="quote">
            "Statistik adalah alat yang sangat kuat untuk memahami dunia di sekitar kita!"
        </div>

        <h2>Pentingnya Statistik</h2>
        <p>Statistik sangat penting karena membantu kita memahami data dengan lebih baik, membuat keputusan yang lebih tepat, dan mengomunikasikan informasi dengan jelas. Dalam dunia yang penuh informasi, kemampuan untuk menganalisis data adalah keterampilan yang sangat berharga.</p>
    </div>


    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
