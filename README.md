<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizzeria Bella Pizza</title>
    <style>
      body {
        font-family: 'Segoe UI', sans-serif;
        background-color: #fff8f0;
        margin: 0;
        padding: 0;
      }

      header {
        background-color: #d62828;
        color: white;
        text-align: center;
        padding: 2rem 1rem;
      }

      header h1 {
        margin: 0;
        font-size: 2.5rem;
      }

      .menu {
        max-width: 800px;
        margin: 2rem auto;
        padding: 1rem;
        background-color: #fefae0;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0.1);
      }

      .section {
        margin-bottom: 2rem;
      }

      .section h2 {
        color: #d62828;
        border-bottom: 2px solid #d62828;
        padding-bottom: 0.5rem;
      }

      .item {
        display: flex;
        justify-content: space-between;
        padding: 0.5rem 0;
        border-bottom: 1px dashed #ccc;
      }

      .item:last-child {
        border-bottom: none;
      }

      .item-name {
        font-weight: bold;
      }

      .item-price {
        color: #333;
      }

      footer {
        text-align: center;
        padding: 1rem;
        font-size: 0.9rem;
        color: #555;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Pizzeria Bella Pizza</h1>
      <p>Il gusto autentico della tradizione italiana</p>
    </header>

    <div class="menu">
      <div class="section">
        <h2>Pizze Classiche</h2>
        <div class="item"><span class="item-name">Margherita</span><span class="item-price">€6.00</span></div>
        <div class="item"><span class="item-name">Marinara</span><span class="item-price">€5.50</span></div>
        <div class="item"><span class="item-name">Diavola</span><span class="item-price">€7.00</span></div>
        <div class="item"><span class="item-name">Capricciosa</span><span class="item-price">€8.00</span></div>
      </div>

      <div class="section">
        <h2>Pizze Speciali</h2>
        <div class="item"><span class="item-name">Bella Pizza</span><span class="item-price">€9.00</span></div>
        <div class="item"><span class="item-name">Bufalina</span><span class="item-price">€8.50</span></div>
        <div class="item"><span class="item-name">Tartufo e Funghi</span><span class="item-price">€10.00</span></div>
      </div>

      <div class="section">
        <h2>Bevande</h2>
        <div class="item"><span class="item-name">Acqua Naturale</span><span class="item-price">€9.00</span></div>
        <div class="item"><span class="item-name">Coca-Cola</span><span class="item-price">€8.50</span></div>
        <div class="item"><span class="item-name">Birra Artigianale</span><span class="item-price">€10.00</span></div>
      </div>
  </div>
  </body>
</html>
