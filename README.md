<!doctype html>

<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Flores de Ensueño — Landing</title>
  <style>
    :root{
      --bg:#fffafc;
      --primary:#d63384;
      --secondary:#f8d7e6;
      --dark:#3b0a45;
      --muted:#6c757d;
    }
    *{box-sizing:border-box;margin:0;padding:0;font-family:'Segoe UI',sans-serif}
    body{background:var(--bg);color:var(--dark);line-height:1.6}
    header{background:linear-gradient(135deg,var(--primary),#ff80b5);color:white;text-align:center;padding:60px 20px}
    header h1{font-size:42px;margin-bottom:10px}
    header p{font-size:20px}
    section{padding:60px 20px;max-width:1100px;margin:auto}
    h2{text-align:center;font-size:32px;margin-bottom:30px;color:var(--primary)}
    .catalogo{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
    .producto{background:white;border-radius:12px;box-shadow:0 4px 14px rgba(0,0,0,0.1);overflow:hidden;display:flex;flex-direction:column}
    .producto img{width:100%;height:220px;object-fit:cover}
    .producto .info{padding:16px}
    .producto h3{margin:0;font-size:20px;color:var(--dark)}
    .producto p{margin:8px 0;font-size:14px;color:var(--muted)}
    .precio{font-weight:bold;color:var(--primary)}
    .beneficios{display:flex;flex-wrap:wrap;gap:20px;justify-content:center;margin-top:20px}
    .beneficio{flex:1 1 200px;background:var(--secondary);padding:20px;border-radius:12px;text-align:center}
    footer{background:var(--dark);color:white;text-align:center;padding:20px;margin-top:40px}
    .btn{display:inline-block;background:var(--primary);color:white;padding:12px 20px;margin-top:10px;border-radius:8px;text-decoration:none;font-weight:600}
  </style>
</head>
<body>
  <header>
    <h1>Flores de Ensueño</h1>
    <p>Regala la belleza que perdura ✨</p>
  </header>  <section id="presentacion">
    <h2>La Magia de lo Eterno</h2>
    <p style="text-align:center;max-width:800px;margin:auto">En <strong>Flores de Ensueño</strong>, transformamos simples limpiapipas en obras de arte florales que desafían el tiempo. Cada pétalo y cada tallo es cuidadosamente elaborado a mano en Colombia, creando un regalo único, sostenible y lleno de significado. Regala un recuerdo que nunca se marchita.</p>
  </section>  <section id="catalogo">
    <h2>Catálogo</h2>
    <div class="catalogo">
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Aurora" alt="Ramo Aurora">
        <div class="info">
          <h3>Ramo 'Aurora'</h3>
          <p>Vibrantes tulipanes y flores en tonos rosa y fucsia, con mariposas y empaque premium.</p>
          <p class="precio">$95.000 COP</p>
        </div>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Amor+Eterno" alt="Ramo Amor Eterno">
        <div class="info">
          <h3>Ramo 'Amor Eterno'</h3>
          <p>Rosas y girasoles, símbolo de pasión y alegría, opción de luces LED.</p>
          <p class="precio">$135.000 COP</p>
        </div>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Sol+Naciente" alt="Ramo Sol Naciente">
        <div class="info">
          <h3>Ramo 'Sol Naciente'</h3>
          <p>Explosión de color con girasoles, rosas y flores silvestres en gran formato.</p>
          <p class="precio">$180.000 COP</p>
        </div>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Tulipán" alt="Tulipán Eterno">
        <div class="info">
          <h3>Tulipán Eterno</h3>
          <p>Elegancia en un solo tallo. Colores: rosa, blanco, morado, amarillo.</p>
          <p class="precio">$10.000 COP</p>
        </div>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Rosa" alt="Rosa Clásica">
        <div class="info">
          <h3>Rosa Clásica</h3>
          <p>La flor del amor eterno. Colores: rojo, blanco, rosa, amarillo.</p>
          <p class="precio">$18.000 COP</p>
        </div>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/400x220?text=Girasol" alt="Girasol Luminoso">
        <div class="info">
          <h3>Girasol Luminoso</h3>
          <p>Un rayo de sol eterno. Centro marrón o negro.</p>
          <p class="precio">$15.000 COP</p>
        </div>
      </div>
    </div>
  </section>  <section id="beneficios">
    <h2>Beneficios</h2>
    <div class="beneficios">
      <div class="beneficio"><strong>Hecho a Mano</strong><br>Con amor y detalle</div>
      <div class="beneficio"><strong>Belleza Eterna</strong><br>No se marchitan nunca</div>
      <div class="beneficio"><strong>Sostenible</strong><br>Regalo único y responsable</div>
    </div>
  </section>  <section id="contacto">
    <h2>Haz tu Pedido</h2>
    <p style="text-align:center">Escríbenos para personalizar tu ramo y recibirlo en casa.</p>
    <div style="text-align:center">
      <a href="https://wa.me/573000000000" class="btn">Pedir por WhatsApp</a>
    </div>
  </section>  <footer>
    <p>© 2025 Flores de Ensueño · Hecho a mano en Colombia</p>
  </footer>
</body>
</html>
