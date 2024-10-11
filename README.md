<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bling Beads - Handmade Accessories for Women">
    <meta name="description" content="Bling Beads - Product Table with Horizontal Scroll">
    <title>Bling Beads - Single Page</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Navbar */
        nav {
            background-color: #ff0066;
            padding: 15px;
        }

        nav .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav .logo a {
            color: white;
            text-decoration: none;
            font-size: 1.5em;
            font-weight: bold;
        }

        nav ul {
            list-style-type: none;
        }

        nav ul li {
            display: inline-block;
            margin-left: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
        }

        /* Header */
        header {
            background: url('Image/Desain tanpa judul.png') no-repeat center center/cover;
            height: 500px;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            display: none;
        }

        header.active {
            display: flex;
        }

        /* Sections */
        section {
            padding: 40px;
            display: none;
        }

        section.active {
            display: block;
        }

        /* Arrow Buttons */
        .arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: #ff6f61;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }

        /* Footer */
        footer {
            background-color: #ff0066;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>

<body style="background-color: antiquewhite;">

    <!-- Navbar -->
    <nav>
        <div class="container">
            <div class="logo">
                <a href="#" onclick="showPage('home')">Bling Beads</a>
            </div>
            <ul class="nav-links">
                <li><a href="#" onclick="showPage('home')">Home</a></li>
                <li><a href="#" onclick="showPage('about')">About Us</a></li>
                <li><a href="#" onclick="showPage('products')">Products</a></li>
                <li><a href="#" onclick="showPage('contact')">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Home Page -->
    <header id="home" class="active">
        <h1>Welcome to Bling Beads</h1>
        <p>Sparkle in Every Strand</p>
        <a href="#" class="btn" onclick="showPage('products')">Shop Now</a>
    </header>

    <!-- About Us Section -->
    <section id="about">
        <div class="container" style="color: crimson; text-align: center; font-family: Arial, Helvetica, sans-serif;">
            <h2>About BlingBeads Studio</h2>
            <div class="text-wrap">
                <p> <img src="Image/LOGO.png" style="display: inline-block; width: 200px; height: 200px;">
                    <p style="display: inline-block;">"Blingbead Studio" sendiri sudah mengandung makna yang kuat. "Bling" mengacu pada kilauan manik-manik, sedangkan "bead" adalah manik-manik itu sendiri. 
                    Kata "studio" menunjukkan tempat di mana kreativitas dan keindahan diwujudkan. 
                    Dengan menggabungkan logo kupu-kupu yang penuh makna dan nama usaha yang kuat, 
                    Blingbead Studio berhasil menciptakan identitas merek yang unik dan mudah diingat. 
                    Logo ini tidak hanya menjadi simbol visual yang menarik, tetapi juga mencerminkan nilai-nilai dan visi dari bisnis ini.
                </p>
            </div>
        </div>
    </section>

     <!-- Product Table Section -->
     <section id="products">
      <div class="container">
          <!-- Tombol Panah Kiri -->
           <button class="arrow left" onclick="scrollTable(-1)">&#9664;</button>

        <style>
          body {
              font-family: 'Arial', sans-serif;
              margin: 0;
              padding: 0;
              background-color: #ff8dbc;
          }

          h1 {
              color: #ffffff;
              font-family: luminari ;
          }
  
          
          .container {
              display: flex;
              justify-content: center;
              align-items: center;
              flex-wrap: wrap;
              padding: 20px;
          }
  
          .product {
              background-color: #ffc6c6;
              border-radius: 10px;
              margin: 10px;
              padding: 20px;
              text-align: center;
              width: 250px;
              box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
          }
  
          .product img {
              width: 150px;
              height: 150px;
              border-radius: 50%;
              margin-bottom: 10px;
              cursor: pointer;
          }
  
          .product h3 {
              color: #333;
          }
  
          .product p {
              color: #666;
          }

          th, td {
              text-align: left;
              padding: 8px;
              border-bottom: 1px solid #ff008c;
          }

          td button {
            background-color: #ff008c;
          }
  
          th {
              background-color: #ff008c;
          }

          .arrow.left {
            left: 0;
        }

        .arrow.right {
            right:0%;
        }
  
      </style>
  </head>
  <body>
  
    <div class="product-table-container">
      <!-- Tombol Panah Kiri -->
      <button class="arrow left" onclick="scrollTable(-1)">&#9664;</button>
  <div class="container">
      <div class="product" >
          <img src="Image/Gelang.jpeg" alt="Perfume 1" onclick="window.location.href='https://www.instagram.com/blingbead.studio/'">
          <h3>Bracellet</h3>
          <p>Gelang manik-manik dari BlingBead Studio adalah aksesori cantik yang dirancang dengan keahlian tangan penuh detail dan ketelitian. 
            Terbuat dari bahan manik-manik berkualitas tinggi yang berkilau, 
            setiap gelang memberikan kesan feminim. </p>
          <p> RP 15.000</p>
          <td><button>Add to Cart</button></td>
      </div>
  
      <div class="product" >
          <img src="Image/Kalung.jpeg" alt="Perfume 2" onclick="window.location.href='https://www.instagram.com/blingbead.studio/'">
          <h3>Necklace</h3>
          <p>Blingbead Studio menghadirkan koleksi kalung manik-manik handmade yang memukau. 
            Setiap kalung adalah karya seni unik, dirakit dengan teliti menggunakan manik-manik berkualitas tinggi.
        </p>
          <p>RP 20.000</p>
          <td><button>Add to Cart</button></td>
      </div>
  
      <div class="product" >
          <img src="Image/cincin.jpeg" alt="Perfume 3" onclick="window.location.href='https://www.instagram.com/blingbead.studio/'">
          <h3>Ring</h3>
          <p>Setiap cincin adalah karya seni unik, dibuat dengan tangan oleh pengrajin kami yang terampil. Kami menggunakan manik-manik berkualitas tinggi dengan berbagai bentuk dan warna, sehingga setiap cincin memiliki karakternya sendiri. Dapatkan tampilan yang menawan dan ungkapkan dirimu melalui perhiasan yang penuh makna.
        </p>
          <p> RP 5.000</p>
          <td><button>Add to Cart</button></td>
      </div>
  
      <div class="product" >
        <img src="Image/strap phone.jpeg" alt="Perfume 4" onclick="window.location.href='https://www.instagram.com/blingbead.studio/'">
        <h3>Strap Phone</h3>
        <p>Pilihan strap handphone dengan desain yang kreatif dan berkualitas tinggi. Dapatkan koleksi strap handphone terbaru kami dengan berbagai pilihan warna, bahan, dan motif yang sesuai dengan gaya pribadimu.
        </p>
        <p> RP 10.000</p>
        <td><button>Add to Cart</button></td>
    </div>
  
        <div class="product" >
          <img src="Image/gantungan knci.jpeg" alt="Perfume 3" onclick="window.location.href='https://www.instagram.com/blingbead.studio/'">
          <h3>Key Chain</h3>
          <p>Blingbead Studio menawarkan koleksi gantungan kunci yang unik dan menarik. Setiap desainnya dibuat dengan penuh kreativitas, menggabungkan berbagai elemen menarik untuk menghasilkan aksesori yang tidak hanya fungsional, tapi juga menjadi pernyataan gaya. Bahan-bahan berkualitas tinggi dipilih untuk memastikan daya tahan dan keindahan gantungan kunci ini.
        </p>
          <p> RP 12.000</p>
          <td><button>Add to Cart</button></td>
        </div>
        
         <!-- Tombol Panah Kanan -->
         <button class="arrow right" onclick="scrollTable(1)">&#9654;</button>
  </div>
</body>

  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div style="color: crimson;">
        <h2>Hubungi Kami</h2>
        <p>Silakan isi form di bawah ini untuk menghubungi kami.</p>
        <form>
            <label for="nama">Nama:</label>
            <input type="text" id="nama" name="nama" required>
  
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
  
            <label for="pesan">Pesan:</label>
            <textarea id="pesan" name="pesan" required></textarea>
  
            <button type="submit">Kirim</button>
        </form>
        <p>Atau hubungin kami melalui: </p>
        <address>
            <p>DM Instagram: @blingbead.studio</p>
            <p>Email: studioblingbead.gmail.com</p>
            </address>
    </div>
  </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Bling Beads. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        function showPage(page) {
            // Hide all sections
            var sections = document.querySelectorAll("section, header");
            sections.forEach(function (section) {
                section.classList.remove("active");
            });

            // Show the selected page
            document.getElementById(page).classList.add("active");
        }
    </script>
</body>

</html>
