<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>CASH ON EXCHANGE</title>
  <style>
    /* ------------ Variables de color inspiradas en Revolut & CurrencyFair ------------- */
    :root{
      --clr-primary:#0076ff;      /* Azul Revolut */
      --clr-secondary:#5e00ff;   /* Morado Revolut */
      --clr-accent:#00c4cc;      /* Turquesa CurrencyFair */
      --clr-bg:#f4f6fb;          /* Fondo neutro claro */
      --clr-dark:#222222;        /* Texto oscuro */
      --radius:12px;
      --shadow:0 4px 10px rgba(0,0,0,.08);
    }

    /* ----------------------- Reset y tipografía ----------------------- */
    *{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth;}
    body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,Helvetica,Arial,sans-serif;background:var(--clr-bg);color:var(--clr-dark);line-height:1.6;}
    img{max-width:100%;height:auto;border-radius:var(--radius);box-shadow:var(--shadow);}    
    a{color:inherit;text-decoration:none;}

    /* -------------------------- Encabezado --------------------------- */
    header{
      background:linear-gradient(135deg,var(--clr-primary),var(--clr-secondary));
      color:#fff;
      padding:2.5rem 1rem 6rem; /* espacio extra para el hero */
      position:relative;
    }
    header h1{font-size:2.2rem;font-weight:700;text-align:center;max-width:1000px;margin:auto;}

    /* ---------- Navegación flotante (estilo Revolut minimal) ---------- */
    nav{
      position:sticky;top:0;z-index:999;
      background:#fff;box-shadow:0 2px 8px rgba(0,0,0,.05);
      display:flex;gap:1rem;justify-content:center;padding:.7rem 1rem;
    }
    nav a{
      padding:.4rem .8rem;border-radius:6px;font-weight:500;color:var(--clr-dark);transition:.2s;
    }
    nav a:hover{background:var(--clr-primary);color:#fff;}

    /* --------------------------- Layout ------------------------------ */
    main{max-width:1000px;margin:-4rem auto 4rem;padding:0 1rem;} /* levanta el main bajo header */
    section{background:#fff;border-radius:var(--radius);padding:2rem 1.5rem;margin-bottom:2rem;box-shadow:var(--shadow);}    
    section:nth-of-type(even){background:#fefefe;}
    h2{font-size:1.7rem;margin-bottom:1rem;color:var(--clr-primary);}  
    h3{font-size:1.1rem;margin:1rem 0;font-weight:400;}

    /* ------------------------- Botones CTA --------------------------- */
    .btn{
      display:inline-block;background:var(--clr-secondary);color:#fff;padding:.7rem 1.4rem;border-radius:var(--radius);box-shadow:var(--shadow);transition:.2s;font-weight:500;
    }
    .btn:hover{background:var(--clr-accent);transform:translateY(-2px);box-shadow:0 6px 14px rgba(0,0,0,.15);}    

    /* ------------------------- Responsive ---------------------------- */
    @media(max-width:600px){
      header h1{font-size:1.6rem;}
      nav{overflow-x:auto;gap:.4rem;}
      h2{font-size:1.4rem;}
      h3{font-size:1rem;}
    }
  </style>
</head>
<body>

  <header>
    <h1>GRUPO EMPRESARIAL CORPISE CASH ONE</h1>
  </header>

  <nav>
    <a href="#nosotros">Nosotros</a>
    <a href="#definiciones">Definiciones</a>
    <a href="#servicios">Servicios</a>
    <a href="#franquicias">Franquicias</a>
    <a href="#formatos">Formatos</a>
    <a href="#sucursales">Sucursales</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <main>
    <!-- ========================= NOSOTROS ========================= -->
    <section id="nosotros">
      <h2>Nosotros</h2>
      <h3><strong>¿Quiénes somos?</strong></h3>
      <h3>Somos un Grupo Empresarial integrado conforme a las disposiciones de carácter general a que se refiere el
      artículo 95 Bis de la Ley General de Organizaciones y Actividades Auxiliares del Crédito...</h3>

      <h3><strong>Misión</strong></h3>
      <h3>Otorgar servicios financieros de calidad a empresarios, turistas y viajeros...</h3>
      <img src="mision.png" alt="Misión">

      <h3><strong>Visión</strong></h3>
      <h3>Tener presencia nacional, creciendo bajo el modelo de grupos empresariales.</h3>
      <img src="vision.png" alt="Visión">

      <h3><strong>Valores</strong></h3>
      <img src="valores.png" alt="Valores">
      <h3><strong>Pasión:</strong> Hacer negocios con entrega total para que nuestros clientes nos prefieran.</h3>
      <img src="pasion.jpg" alt="Pasión">
      <h3><strong>Calidad:</strong> Buscar la excelencia.</h3>
      <img src="calidad.jpg" alt="Calidad">
      <h3><strong>Transparencia:</strong> Transparentar nuestras operaciones.</h3>
      <img src="transpa.jpg" alt="Transparencia">
    </section>

    <!-- ====================== DEFINICIONES ======================= -->
    <section id="definiciones">
      <h2>Definiciones</h2>
      <h3><strong>Operaciones Permitidas</strong></h3>
      <ul>
        <li>Cambio de billetes, monedas, cheque de viajero...</li>
        <li>Cantidad diaria por persona: $10,000 USD</li>
        <li>Solo efectivo y cheques de viajero</li>
      </ul>
      <h3><strong>Operaciones Prohibidas</strong></h3>
      <ul>
        <li>Transferencias</li>
        <li>Liquidar por anticipado</li>
        <li>Aceptar billetes falsos...</li>
      </ul>
      <h3><strong>Identificaciones Válidas</strong></h3>
      <ul>
        <li>Identificaciones oficiales vigentes con fotografía</li>
        <li>Documentos expedidos por el Instituto Nacional de Migración...</li>
      </ul>
    </section>

    <!-- ====================== SERVICIOS ======================= -->
    <section id="servicios">
      <h2>Servicios</h2>
      <h3><strong>Compra y venta de efectivo</strong></h3>
      <ul>
        <li>Dólares</li>
        <li>Euros</li>
        <li>Dólar Canadiense</li>
      </ul>
      <h3><strong>Compra de metales amonedados</strong></h3>
      <ul>
        <li>Onza Libertad</li>
        <li>Centenario</li>
        <li>Onza de Oro...</li>
      </ul>
      <img src="doc3.jpg" alt="Metales y Divisas">
    </section>

    <!-- ====================== FRANQUICIAS ======================= -->
    <section id="franquicias">
      <h2>Franquicias</h2>
      <h3><strong>¿Por qué invertir en una franquicia?</strong></h3>
      <h3>Las estadísticas indican que el emprendedor independiente tiene el 80% de posibilidades de no llegar al segundo año...</h3>
      <h3><strong>Respaldo corporativo</strong></h3>
      <h3>Nuestro Grupo "CORPISE" cuenta con la experiencia y profesionalismo...</h3>
      <h3><strong>Modalidad renta</strong></h3>
      <h3>Única franquicia en el país de centros cambiarios que brinda modalidad de renta...</h3>
      <img src="doc2.jpg" alt="Franquicias">
      <a href="#contacto" class="btn">Quiero más información</a>
    </section>

    <!-- ====================== FORMATOS ======================= -->
    <section id="formatos">
      <h2>Formatos</h2>
      <h3>Nuestros centros cambiarios pueden solicitar en cualquier momento cualquiera de los siguientes formatos:</h3>
      <ul>
        <li>Anexo 1: Sociedades, dependencias y entidades...</li>
        <li>Anexo 2: Identificaciones oficiales permitidas</li>
        <li>Anexo 3: Información de domicilio...</li>
        <li>Anexo 4, 5, 8, 9, 10, 13...</li>
      </ul>
      <a href="formatos.html" class="btn">Descargar Anexos</a>
    </section>

    <!-- ====================== SUCURSALES ======================= -->
    <section id="sucursales">
      <h2>Sucursales</h2>
      <h3><strong>Espacio</strong> - Av. Tecnológico #120...</h3>
      <h3><strong>Velaria</strong> - Av. Aguascalientes Sur S/N Local 7...</h3>
      <h3><strong>Calvillo</strong> - Independencia 108-A...</h3>
      <h3><strong>Morelos</strong> - José Maria Morelos y Pavón #215-A...</h3>
      <h3><strong>Hospitalidad</strong> - Calle Hospitalidad #119-B...</h3>
      <h3><strong>Huatulco</strong> - Benito Juarez No. 1-a Bis...</h3>
      <h3><strong>Los Cabos</strong> - Boulevard Marina Lote 6...</h3>
    </section>

    <!-- ====================== CONTACTO ======================= -->
    <section id="contacto">
      <h2>Contacto</h2>
      <img src="doc4.jpg" alt="Contacto">
      <h3>CORPISE CASH ONE S.A. DE C.V. CCO210209I76</h3>
      <h3>Priva Arquitectos 102, Colonia Centro, Aguascalientes, C.P. 20000</h3>
      <h3>Tel: 449-155-84-79 / 449-361-68-88</h3>
      <a class="btn" href="mailto:info@cashonexchange.com">Escríbenos</a>
    </section>
  </main>

  <footer style="text-align:center;padding:1rem;background:#fff;border-top:1px solid #e5e5e5;">
    <p>© 2025 CORPISE CASH ONE. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
