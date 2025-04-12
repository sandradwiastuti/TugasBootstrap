# TugasBootstrap
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Kami</title>
 
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background: url('https://wallpapercave.com/wp/wp11291046.jpg') center center/cover no-repeat;
      height: 90vh;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-shadow: 2px 2px 5px #000;
    }
    footer {
      background-color: #007bff;
      color: white;
      padding: 20px 0;
    }
    a {
      color: white;
      margin: 0 10px;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand" href="#">Logo</a>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#">Beranda</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Tentang</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  
  <div class="hero text-center">
    <h1>Selamat Datang di Website Kami</h1>
    <p class="lead">Ini adalah halaman latihan Bootstrap untuk mahasiswa.</p>
    <a href="#" class="btn btn-primary btn-lg mt-3">Pelajari Lebih Lanjut</a>
  </div>

  <footer class="text-center">
    <p>Ikuti kami di:</p>
    <a href="#">Facebook</a>
    <a href="#">Twitter</a>
    <a href="#">Instagram</a>
    <p class="mt-3">© 2025 Website Kami. All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
