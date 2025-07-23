# 21stlegislativecouncil2025
Matanao 21st legislative website
<!DOCTYPE html>
<html lang="ceb">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matanao 21st Legislative Council</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: maroon;
      color: white;
      padding: 1rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .main-button {
      background-color: darkorange;
      color: white;
      padding: 1rem;
      border: none;
      font-size: 1.2rem;
      cursor: pointer;
      margin: 1rem auto;
      display: block;
      border-radius: 8px;
    }
    section {
      padding: 2rem;
    }
    .section-title {
      color: maroon;
      border-bottom: 2px solid darkorange;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }
    .card {
      background-color: #f9f9f9;
      padding: 1rem;
      margin: 1rem 0;
      border-left: 5px solid maroon;
      border-radius: 5px;
    }
    footer {
      background-color: maroon;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="Untitled design.png" alt="Matanao Council Logo">
    <nav>
      <a href="#balita">Balita</a>
      <a href="#ordinansa">Ordinansa</a>
      <a href="#bag-ong-update">Bag-ong Update</a>
      <a href="#resolusyon">Resolusyon</a>
    </nav>
  </header>

  <button class="main-button" onclick="alert('Feature coming soon!')">Tanang Ordinansa ug Resolusyon</button>

  <section id="balita">
    <h2 class="section-title">Balita</h2>
    <div class="card">Walay bag-ong balita sa pagkakaron. Hulat lang para sa sunod nga update.</div>
  </section>

  <section id="ordinansa">
    <h2 class="section-title">Ordinansa</h2>
    <div class="card">📄 <a href="ordinance-001.pdf" target="_blank">Ordinansa Blg. 001 - Balaod sa Pagdumala sa Basura</a></div>
  </section>

  <section id="bag-ong-update">
    <h2 class="section-title">Bag-ong Update</h2>
    <div class="card">Ang sunod nga sesyon sa Konseho kay ipahigayon sa Agosto 5, 2025 sa alas 9 sa buntag.</div>
  </section>

  <section id="resolusyon">
    <h2 class="section-title">Resolusyon</h2>
    <div class="card">📄 <a href="resolution-010.pdf" target="_blank">Resolusyon Blg. 010 - Suporta sa mga Mag-uuma</a></div>
  </section>

  <footer>
    &copy; 2025 Konseho sa Lehislatibo sa Matanao ika-21 nga Henerasyon. Tanang katungod gireserba.
  </footer>
</body>
</html>
