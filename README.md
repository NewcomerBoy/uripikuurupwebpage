<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Laman Web Yng Dibuat Sama Chat GPT Tapi Tak Edit mwehehe</title>
  <style>
   /* Reset dasar */
   * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      display: flex;
      min-height: 100vh;
      background-color: #f0f0f5;
    }

    body {
      display: flex;
      min-height: 100vh;
      color: #333;
      background-color: #fafafa;
      overflow-x: hidden;
    }

     /* Card utk page Styling */
     .cardo {
      background-color: #fff;
      padding: 0px;
      margin: 15px 0;
      border-radius: 0px;
      box-shadow: 0 0px 0px rgba(0, 0, 0, 0.1);
    }

    .cardo h2 {
      font-size: 1.25rem;
      color: #6200ea;
      margin-bottom: 10px;
    }


    /* Header */
    .header {
      width: 100%;
      height: 60px;
      background-color: #6200ea;
      color: white;
      display: flex;
      align-items: center;
      padding: 0 20px;
      position: fixed;
      top: 0;
      z-index: 10;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .header .logo {
      font-size: 1.5rem;
      font-weight: bold;
      margin-right: auto;
    }

    /* Sidebar */
    .sidebar {
      width: 240px;
      background-color: #ffffff;
      position: fixed;
      top: 60px;
      bottom: 0;
      padding-top: 20px;
      border-right: 1px solid #ddd;
      box-shadow: 2px 0 5px rgba(0, 0, 0, 0.1);
    }

    .sidebar a {
      display: block;
      padding: 15px 20px;
      color: #333;
      text-decoration: none;
      font-size: 1rem;
      border-radius: 8px;
      margin: 5px 10px;
      transition: background-color 0.3s;
    }

    .sidebar a:hover {
      background-color: #e0e0e0;
    }

    /* Main Content */
    .main-content {
      margin-top: 60px;
      margin-left: 250px;
      padding: 20px;
      width: calc(100% - 240px);
      overflow-y: auto;
    }

    /* Card Styling */
    .card {
      background-color: #fff;
      padding: 20px;
      margin: 15px 0;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }

    .card h2 {
      font-size: 1.25rem;
      color: #6200ea;
      margin-bottom: 10px;
    }

    /* Button Styling */
    .button {
      display: inline-block;
      padding: 10px 20px;
      font-size: 1rem;
      color: white;
      background-color: #6200ea;
      border-radius: 8px;
      text-decoration: none;
      transition: background-color 0.3s;
      text-align: center;
    }

    .button:hover {
      background-color: #3700b3;
    }
    

    /* Page transitions */
    .fade-in {
      animation: fadeIn 0.5s ease-in;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .sidebar {
        width: 100%;
        height: auto;
        position: relative;
        top: 0;
      }
     
    
   
  }

  * Kontainer untuk Gulir Vertikal */
  .scroll-container {
    margin-left: 250px; /* Mengimbangi lebar sidebar */
    padding: 20px;
    max-width: 800px;
    margin: 0 auto;
    max-height: 90vh; /* Tinggi maksimal kontainer */
    overflow-y: auto; /* Gulir vertikal jika konten melebihi max-height */
  }

  /* Styling Kartu di Kontainer Utama */
  .card {
    background-color: #ffffff;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
    padding: 20px;
    margin-bottom: 15px;
  }

  .card h3 {
    color: #6200ea;
    font-size: 1.25em;
    margin-bottom: 10px;
  }

  .card p {
    color: #333;
    line-height: 1.5;
    margin-bottom: 20px;
  }

  .card .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #6200ea;
    color: white;
    border: none;
    border-radius: 8px;
    text-decoration: none;
    text-align: center;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .card .button:hover {
    background-color: #3700b3;
  }
  </style>
</head>
<body>

  <!-- Header -->
  <div class="header">
    <div class="logo">Urip Iku Urup</div>
  </div>

  <!-- Sidebar -->
  <nav class="sidebar">
    <a href="#" onclick="loadPage('home')">Nasehat</a>
    <a href="#" onclick="loadPage('about')">Modul Pelajaran</a>
    <a href="#" onclick="loadPage('services')">Target</a>
    <a href="#" onclick="loadPage('list')">Waiting List Activity</a>
    <a href="#" onclick="loadPage('poto')">Dokumentasi Pribadi</a>
    <a href="#" onclick="loadPage('omongan')">Just Blah-Blah</a>
    <a href="#" onclick="loadPage('settings')"> Web Settings</a>
  </nav>

  <!-- Main Content -->
 
<body>
<!-- Konten Utama -->
<div class="main-content fade-in" id="content">
  <!-- Kartu Utama -->
  <div class="card">
    <h3>Welcome to Muhajir Manufacture</h3>
    <p>This is a sample homepage. Use the sidebar to navigate through different pages.</p>
    <a href="#" class="button">Get Started</a>
  </div>

  <!-- Kartu Tambahan jika diperlukan -->
  <div class="card">
    <h3>Sample Card 2</h3>
    <p>Content for the second card goes here. You can add any other information as needed.</p>
  </div>

  <div class="card">
    <h3>Sample Card 3</h3>
    <p>This is another card example. Cards can be used to display information in an organized way.</p>
  </div>

  <div class="card">
    <h3>Sample Card 3</h3>
    <p>This is another card example. Cards can be used to display information in an organized way.</p>
  </div>

  <div class="card">
    <h3>Sample Card 3</h3>
    <p>This is another card example. Cards can be used to display information in an organized way.</p>
  </div>

  <div class="card">
    <h3>Sample Card 3</h3>
    <p>This is another card example. Cards can be used to display information in an organized way.</p>
  </div>
</div>


  <script>
    // Function to load different pages into main content
    function loadPage(page) {
      const content = document.getElementById('content');
      content.classList.remove('fade-in');

      setTimeout (() => {
        if (page === 'home') {
          content.innerHTML = `
            <div class="card">
              <h2>Nasehat-nasehat</h2>
              <p>Hadeeth penyemangat dan beberapa kiat yang semoga membantu.</p>
              <a href="#" class="button">Hadeeth</a>
              <a href="#" class="button" onclick="loadPage('page1')">Kiat-kiat</a>
            </div>`;
        } else if (page === 'about') {
          content.innerHTML = `
            <div class="card">
              <h2>Modul Belajar X TM C</h2>
              <p>Kumpulan modul dan materi kelas X TM C.</p>
              <!-- Tombol yang berfungsi sebagai link -->
              <a href="https://link" class="button" target="_blank">Semester 1</a>
              <a href="#" class="button">Semester 2</a>
            </div>`;
        } else if (page === 'services') {
          content.innerHTML = `
            <div class="card">
              <h2>Target</h2>
              <p>Daftar target pekanan, bulanan, dan tahunan.</p>
            </div>`;
        } else if (page === 'list') {
          content.innerHTML = `
            <div class="card">
              <h2>Waiting List Activity</h2>
              <p>Rencana kegiatan yang mau dilakukan berikutnya, belon tahu kapan.</p>
            </div>`;
        }  else if (page === 'omongan') {
          content.innerHTML = `
            <div class="card">
              <h2>Just Blah-Blah</h2>
              <p>Ocehan bermanfaat.</p>
            </div>`;
        }  else if (page === 'poto') {
          content.innerHTML = `
            <div class="card">
              <h2>Dokumentasi</h2>
              <p>Kumpulan foto-foto terpilih.</p>
              <a href="#" class="button">Hobi dll</a>
              <a href="#" class="button">Dokumentasi</a>
              <a href="#" class="button">Family and Friends</a>
            </div>`;
        }  else if (page === 'settings') {
          content.innerHTML = `
            <div class="card">
              <h2>Settings</h2>
              <p>Adjust your preferences and configure the application settings here.</p>
            </div>`;
        } else if (page === 'page1') {
          content.innerHTML = `
            <div class="cardo">
              <h2>Kiat-Kiat</h2>
              <p>Beberapa kiat untuk diketahui.</p>
              <div class="card">
                <h3>Welcome to Muhajir Manufacture</h3>
    <p>This is a sample homepage. Use the sidebar to navigate through different pages.</p>
    <a href="#" class="button" onclick="loadPage('pagekiat1')">Lihat</a>
    <p></p>
              
    <h3>Welcome to Muhajir Manufacture</h3>
    <p>This is a sample homepage. Use the sidebar to navigate through different pages.</p>
    <a href="#" class="button" onclick="loadPage('pagekiat2')">Lihat</a>
    <p></p>

    <h3>Welcome to Muhajir Manufacture</h3>
    <p>This is a sample homepage. Use the sidebar to navigate through different pages.</p>
    <a href="#" class="button" onclick="loadPage('pagekiat3')">Lihat</a>
    <p></p>
            </div>`;

        } else if (page === 'pagekiat1') {
          content.innerHTML = `
            <div class="cardo">
              <h2>Tips-Tips Belajar Tenang Sentosa</h2>
              <p></p>
              <p2></p2>
              
              

            
              <h3.5>Awalnya tak kira belajar tu ya tinggal ambil buku kerjain tugas, beres deh. Dulu belajar
                  biasanya di kasur tuh.</h3.5>
              <h4>Simpen hp yang jauh, ampe siberia kalo perlu, setan gepeng akan membaut pikiran buyar haya dengan satu notif saja.</h4>
            </div>`;
        }
        content.classList.add('fade-in');
      }, 200);
    }
  </script>
</body>   


</html>

