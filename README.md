# repaflashdelivery
delivery app in leon gto 
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Catálogo - Repaflash Delivery</title>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="hero">
    <div class="overlay"></div>
    <header class="topbar">
      <img class="logo" src="https://www.repaflash-delivery.com/_next/image?url=%2Flogo-repaflash.png&w=256&q=75" alt="Repaflash" />
    </header>

    <main class="content">
      <h1>CONOCE NUESTROS CLIENTES</h1>

      <section class="grid">
        <a class="card" href="#comida" aria-label="Ver comida">
          <img src="https://www.repaflash-delivery.com/_next/image?q=75&url=%2F_next%2Fstatic%2Fmedia%2Fcomida.feb6dc7c.jpg&w=1920" alt="Comida" />
          <span>COMIDA</span>
        </a>

        <a class="card" href="#otros" aria-label="Ver otros">
          <img src="https://www.repaflash-delivery.com/_next/image?q=75&url=%2F_next%2Fstatic%2Fmedia%2Fotros.5f4f0a6e.jpg&w=1920" alt="Otros" />
          <span>OTROS</span>
        </a>

        <a class="card" href="#fidelidad" aria-label="Ver fidelidad">
          <img src="https://www.repaflash-delivery.com/_next/image?q=75&url=%2F_next%2Fstatic%2Fmedia%2Ffidelidad.e1f0a2bc.jpg&w=1920" alt="Fidelidad" />
          <span>FIDELIDAD</span>
        </a>
      </section>
    </main>
  </div>

  <section class="sections">
    <div id="comida" class="section">
      <h2>Comida</h2>
      <p>Aquí puedes listar negocios de comida y enlazarlos a su WhatsApp.</p>
    </div>
    <div id="otros" class="section">
      <h2>Otros</h2>
      <p>Servicios, tiendas y más.</p>
    </div>
    <div id="fidelidad" class="section">
      <h2>Fidelidad</h2>
      <p>Programas de puntos y beneficios para clientes.</p>
    </div>
  </section>

  <footer class="footer">
    <small>© Repaflash Delivery</small>
  </footer>

  <script>
    // Scroll suave para anclas
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        e.preventDefault();
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el){ el.scrollIntoView({behavior:'smooth'}); }
      });
    });
  </script>
</body>
</html>
