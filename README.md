# <!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>L'Oasi della Buona Tavola</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #232f3e;
      color: white;
      padding: 1rem;
      text-align: center;
      font-size: 2rem;
    }
    nav {
      background-color: #37475a;
      display: flex;
      justify-content: center;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    h2 {
      border-bottom: 2px solid #ffa41c;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }
    .prodotto {
      display: flex;
      flex-direction: column;
      align-items: center;
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin-bottom: 2rem;
      padding: 1rem;
      max-width: 300px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .prodotto img {
      width: 100%;
      border-radius: 8px;
    }
    .prodotto p {
      margin: 0.5rem 0;
    }
    .prodotto button {
      margin-top: 1rem;
      background-color: #ffa41c;
      color: white;
      border: none;
      padding: 0.7rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }
    .prodotti-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    footer {
      background-color: #232f3e;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <header>L'Oasi della Buona Tavola 🍝</header>

  <nav>
    <a href="#chi-siamo">Chi Siamo</a>
    <a href="#prodotti">Prodotti</a>
    <a href="#contatti">Contatti</a>
  </nav>

  <section id="chi-siamo">
    <h2>Chi Siamo</h2>
    <p>Siamo un'attività artigianale locale con sede a Ceprano (FR), attiva nel settore ristorativo dal 2000. Offriamo monoporzioni fatte a mano, confezionate in atmosfera protetta (A.T.M.), senza conservanti!</p>
  </section>

  <section id="prodotti">
    <h2>Primi Piatti</h2>
    <h2>Prodotti</h2>
    <div class="prodotti-grid">
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1617191518000-118bc4bdc841" alt="Lasagna">
    <p><strong>Lasagna al Ragù</strong></p>
    <p>€3.97 / €5.30</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20una%20Lasagna%20al%20Ragù'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1604908177225-52c1c3a897f0" alt="Cannelloni">
    <p><strong>Cannelloni alla Carne</strong></p>
    <p>€4.32 / €5.80</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Cannelloni%20alla%20Carne'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1603133872878-684f208fb94c" alt="Gnocchi">
    <p><strong>Gnocchi alla crema di Scampi</strong></p>
    <p>€4.32 / €5.80</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Gnocchi%20alla%20crema%20di%20Scampi'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f" alt="Polpette">
    <p><strong>Polpette di Manzo e fagioli</strong></p>
    <p>€4.47</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Polpette%20di%20Manzo%20e%20fagioli'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1613141411246-cff8930483d3" alt="Hamburger Vegano">
    <p><strong>Maxi Hamburger Vegano</strong></p>
    <p>€4.32</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20un%20Hamburger%20Vegano'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1613141379287-3af6cfbca313" alt="Crocchette">
    <p><strong>Crocchette di Patate</strong></p>
    <p>€/kg 10.00</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Crocchette%20di%20Patate'">Ordina</button>
  </div>
  <div class="prodotto">
    <img src="https://images.unsplash.com/photo-1599785209798-83d4f571bd4d" alt="Crostata ciliegia">
    <p><strong>Crostata alla ciliegia</strong></p>
    <p>€6.10</p>
    <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20una%20Crostata%20alla%20ciliegia'">Ordina</button>
  </div>
</div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1604908177225-52c1c3a897f0" alt="Cannelloni">
        <p><strong>Cannelloni alla Carne</strong></p>
        <p>€4.32 / €5.80</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Cannelloni%20alla%20Carne'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1613141411246-cff8930483d3" alt="Hamburger Vegano">
        <p><strong>Maxi Hamburger Vegano</strong></p>
        <p>€4.32</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20un%20Hamburger%20Vegano'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1599785209798-83d4f571bd4d" alt="Crostata ciliegia">
        <p><strong>Crostata alla ciliegia</strong></p>
        <p>€6.10</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20una%20Crostata%20alla%20ciliegia'">Ordina</button>
      </div>
    </div>

    <h2>Secondi Piatti</h2>
    <div class="prodotti-grid">
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1551218808-94e220e084d2" alt="Arista di Maiale">
        <p><strong>Arista di Maiale e Olive</strong></p>
        <p>€4.47</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Arista%20di%20Maiale%20e%20Olive'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1562967914-74ef83bba909" alt="Broccoletti e Salsiccia">
        <p><strong>Broccoletti e Salsiccia</strong></p>
        <p>€4.47</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Broccoletti%20e%20Salsiccia'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1582281298054-e8e6fa7d378d" alt="Peperone Ripieno">
        <p><strong>Peperone Ripieno alla Carne</strong></p>
        <p>€4.47</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Peperone%20Ripieno%20alla%20Carne'">Ordina</button>
      </div>
    </div>

    <h2>Fritti</h2>
    <div class="prodotti-grid">
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1576866209830-0b06cbb1e132" alt="Supplì">
        <p><strong>Supplì (70g)</strong></p>
        <p>€/kg 10.00</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Supplì'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1571867424487-bc0e93c6d31e" alt="Olive Ascolane">
        <p><strong>Olive Ascolane (30g)</strong></p>
        <p>€/kg 9.00</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Olive%20Ascolane'">Ordina</button>
      </div>
    </div>

    <h2>Dolci</h2>
    <div class="prodotti-grid">
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1549576490-b0b4831ef60a" alt="Tozzetti alle Mandorle">
        <p><strong>Tozzetti alle Mandorle</strong></p>
        <p>€/kg 9.00</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Tozzetti%20alle%20Mandorle'">Ordina</button>
      </div>
      <div class="prodotto">
        <img src="https://images.unsplash.com/photo-1623341215467-2f6de110af62" alt="Ciambelline al Vino">
        <p><strong>Ciambelline al Vino Rosso/Bianco</strong></p>
        <p>€5.98</p>
        <button onclick="window.location.href='https://wa.me/393922340754?text=Vorrei%20ordinare%20Ciambelline%20al%20Vino'">Ordina</button>
      </div>
    </div>
  </section>

  <section id="contatti">
    <h2>Contatti</h2>
    <p>📞 Roberto: 375 7785994</p>
    <p>📞 Marco: 392 2340754</p>
    <p>📞 Maurizio: 388 9552404</p>
  </section>

  <footer>
    Made with ❤️ a Ceprano (FR) | © 2025 L'Oasi della Buona Tavola
  </footer>
</body>
</html>
