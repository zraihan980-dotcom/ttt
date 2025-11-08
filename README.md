<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kopi Kita - Menu Lengkap</title>
  <style>
    /* Import font Poppins dari Google Fonts */
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

    /* ====== RESET DASAR ====== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f9f6f1; /* Krem muda */
      color: #3e2723; /* Cokelat tua */
    }

    header {
      background: linear-gradient(135deg, #4e342e, #3e2723); /* Gradien cokelat */
      color: #fff;
      text-align: center;
      padding: 40px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 2.5em;
      letter-spacing: 2px;
    }

    header p {
      font-style: italic;
      opacity: 0.9;
    }

    /* ====== JUDUL KATEGORI MENU ====== */
    .menu-category-title {
      text-align: center;
      font-size: 2em;
      color: #4e342e;
      margin: 60px auto 30px auto;
      max-width: 1200px;
      border-bottom: 3px solid #6d4c41;
      padding-bottom: 10px;
    }

    /* ====== MENU SECTION (Grid) ====== */
    .menu {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .menu-item {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s, box-shadow 0.3s;
      display: flex;
      flex-direction: column; 
    }

    .menu-item:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.15);
    }

    .menu-item img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .menu-content {
      padding: 20px;
      flex-grow: 1; /* Konten tumbuh untuk mendorong tombol ke bawah */
      display: flex;
      flex-direction: column;
    }

    .menu-content h3 {
      font-size: 1.3em;
      margin-bottom: 8px;
      color: #4e342e;
    }

    .menu-content p {
      font-size: 0.95em;
      color: #6d4c41;
      margin-bottom: 15px; 
      flex-grow: 1; /* Deskripsi tumbuh untuk menjaga konsistensi tinggi kartu */
    }

    .price-order-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 10px; 
      padding-top: 10px;
      border-top: 1px dashed #efebe9;
    }

    .price {
      font-weight: bold;
      color: #3e2723;
      font-size: 1.1em;
    }

    .order-button {
      background-color: #a1887f; /* Cokelat muda */
      color: #fff;
      border: none;
      padding: 8px 15px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: 600;
      transition: background-color 0.3s, transform 0.1s;
      text-align: center;
      font-size: 0.9em;
    }

    .order-button:hover {
      background-color: #6d4c41; /* Cokelat sedang */
      transform: translateY(-1px);
    }

    /* Media Query untuk layout yang lebih kecil */
    @media (max-width: 600px) {
      .menu {
        grid-template-columns: 1fr;
      }
      .menu-category-title {
        font-size: 1.7em;
      }
    }

    /* ====== FOOTER ====== */
    footer {
      background: #3e2723;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
    }

    footer a {
      color: #ffe0b2;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Kopi Kita</h1>
    <p>Temukan kehangatan dalam setiap tegukan ☕</p>
  </header>

    <h2 class="menu-category-title">Pilihan Kopi Terbaik ☕</h2>
  <section class="menu">
        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8ZXNwcmVzc298ZW58MHx8MHx8fDA%3D" alt="Espresso">
      <div class="menu-content">
        <h3>Espresso</h3>
        <p>Kopi pekat dengan cita rasa kuat dan aroma khas Italia, disajikan dalam porsi kecil yang intens.</p>
        <div class="price-order-container">
          <span class="price">Rp 20.000</span>
          <button class="order-button" onclick="alert('Espresso telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.pexels.com/photos/312418/pexels-photo-312418.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Cappuccino">
      <div class="menu-content">
        <h3>Cappuccino</h3>
        <p>Perpaduan sempurna antara espresso, susu kukus, dan foam lembut di atasnya.</p>
        <div class="price-order-container">
          <span class="price">Rp 25.000</span>
          <button class="order-button" onclick="alert('Cappuccino telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8bGF0dGV8ZW58MHx8MHx8fDA%3D" alt="Latte">
      <div class="menu-content">
        <h3>Caffè Latte</h3>
        <p>Kopi susu lembut dengan rasio susu yang lebih banyak dan sentuhan seni latte art yang memukau.</p>
        <div class="price-order-container">
          <span class="price">Rp 27.000</span>
          <button class="order-button" onclick="alert('Caffè Latte telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1551024601-bec78aea704b?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTR8fG1vY2hhfGVufDB8fDB8fHww" alt="Mocha">
      <div class="menu-content">
        <h3>Mocha</h3>
        <p>Perpaduan nikmat antara espresso, sirup cokelat premium, dan susu hangat yang kaya.</p>
        <div class="price-order-container">
          <span class="price">Rp 28.000</span>
          <button class="order-button" onclick="alert('Mocha telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
        </div>
    </div>

        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1498804103079-a6351b050096?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8Y29sZCUyMGJyZXd8ZW58MHx8MHx8fDA%3D" alt="Cold Brew">
      <div class="menu-content">
        <h3>Cold Brew</h3>
        <p>Kopi diseduh dingin selama lebih dari 12 jam, menghasilkan rasa yang halus dan tingkat keasaman rendah.</p>
        <div class="price-order-container">
          <span class="price">Rp 30.000</span>
          <button class="order-button" onclick="alert('Cold Brew telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>
  </section>

    <h2 class="menu-category-title">Pilihan Makanan Pendamping 🥐</h2>
  <section class="menu">
        <div class="menu-item">
      <img src="https://wildwildwhisk.com/wp-content/uploads/2018/04/How-to-make-Croissant-baked-1.jpg" alt="Croissant">
      <div class="menu-content">
        <h3>Butter Croissant</h3>
        <p>Roti klasik Perancis dengan lapisan mentega, renyah di luar, lembut di dalam. Cocok untuk sarapan atau camilan.</p>
        <div class="price-order-container">
          <span class="price">Rp 18.000</span>
          <button class="order-button" onclick="alert('Butter Croissant telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://static.promediateknologi.id/crop/0x500:1080x1500/0x0/webp/photo/p2/74/2025/07/06/Screenshot_20250706_230023-3907047721.jpg" alt="Brownies">
      <div class="menu-content">
        <h3>Fudgy Brownies</h3>
        <p>Kue cokelat padat dan lengket dengan rasa cokelat yang intens. Pemanis yang sempurna untuk kopi Anda.</p>
        <div class="price-order-container">
          <span class="price">Rp 22.000</span>
          <button class="order-button" onclick="alert('Fudgy Brownies telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.yummy.ph/yummy/uploads/2016/11/grilled-cheese-chicken-3.jpg" alt="Sandwich">
      <div class="menu-content">
        <h3>Chicken & Cheese Sandwich</h3>
        <p>Roti gandum utuh diisi ayam panggang, keju, dan sayuran segar. Pilihan yang mengenyangkan.</p>
        <div class="price-order-container">
          <span class="price">Rp 35.000</span>
          <button class="order-button" onclick="alert('Chicken & Cheese Sandwich telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <!-- Menu makanan tambahan -->
        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1558642452-9d2a7deb7f62?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8bXVkZGluJTIwY2FrZXxlbnwwfHwwfHx8MA%3D%3D" alt="Muffin">
      <div class="menu-content">
        <h3>Blueberry Muffin</h3>
        <p>Muffin lembut dengan blueberry segar, sempurna untuk sarapan atau camilan sore.</p>
        <div class="price-order-container">
          <span class="price">Rp 20.000</span>
          <button class="order-button" onclick="alert('Blueberry Muffin telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1528207776546-365bb710ee93?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cGFuY2FrZXN8ZW58MHx8MHx8fDA%3D" alt="Pancakes">
      <div class="menu-content">
        <h3>Fluffy Pancakes</h3>
        <p>Pancake lembut dengan sirup maple dan mentega, pilihan klasik untuk sarapan.</p>
        <div class="price-order-container">
          <span class="price">Rp 30.000</span>
          <button class="order-button" onclick="alert('Fluffy Pancakes telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

        <div class="menu-item">
      <img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8c2FsYWR8ZW58MHx8MHx8fDA%3D" alt="Salad">
      <div class="menu-content">
        <h3>Caesar Salad</h3>
        <p>Salad segar dengan romaine, crouton, parmesan, dan dressing Caesar yang lezat.</p>
        <div class="price-order-container">
          <span class="price">Rp 28.000</span>
          <button class="order-button" onclick="alert('Caesar Salad telah ditambahkan ke pesanan!')">Pesan Sekarang</button>
        </div>
      </div>
    </div>

  </section>

  <footer>
    <p>© 2025 Kopi Kita | <a href="#">Instagram</a> | <a href="#">TikTok</a></p>
  </footer>
</body>
</html>
