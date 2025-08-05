# Index.Html

<!DOCTYPE html>

<html lang="es">

<head>

&nbsp; <meta charset="UTF-8" />

&nbsp; <meta name="viewport" content="width=device-width, initial-scale=1.0" />

&nbsp; <title>Changa – Tu próximo trabajo está aquí</title>

&nbsp; <meta name="description" content="Conectamos talento local con quienes necesitan un servicio rápido y confiable.">

&nbsp; <link rel="stylesheet" href="style.css" />

&nbsp; <!-- Google Fonts -->

&nbsp; <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700\&display=swap" rel="stylesheet">

&nbsp; <!-- Font Awesome -->

&nbsp; <script src="https://kit.fontawesome.com/a81368914c.js" crossorigin="anonymous"></script>

</head>

<body>

&nbsp; <!-- HERO -->

&nbsp; <header class="hero">

&nbsp;   <nav class="nav container">

&nbsp;     <h1 class="logo">Changa</h1>

&nbsp;     <ul class="nav\_\_links">

&nbsp;       <li><a href="#about">Sobre nosotros</a></li>

&nbsp;       <li><a href="#plans">Membresías</a></li>

&nbsp;       <li><a href="#contact">Contacto</a></li>

&nbsp;     </ul>

&nbsp;   </nav>

&nbsp;   <div class="hero\_\_content container">

&nbsp;     <h2>Trabajá con pasión.<br>Encontrá quien te necesita.</h2>

&nbsp;     <p>Unite a miles de changarines que ya viven de lo que aman. Registrate hoy y empezá a ganar.</p>

&nbsp;     <a href="#register-worker" class="btn btn--primary">Quiero trabajar</a>

&nbsp;     <a href="#post-need" class="btn btn--outline">Necesito un changarín</a>

&nbsp;   </div>

&nbsp; </header>



&nbsp; <!-- REGISTER WORKER -->

&nbsp; <section id="register-worker" class="section">

&nbsp;   <div class="container grid-2">

&nbsp;     <div>

&nbsp;       <h3>Registrate como changarín</h3>

&nbsp;       <p>Completá tus datos y empezá a recibir ofertas cerca tuyo.</p>

&nbsp;       <form class="form" id="form-worker">

&nbsp;         <input type="text" placeholder="Nombre completo" required />

&nbsp;         <input type="email" placeholder="Correo electrónico" required />

&nbsp;         <select required>

&nbsp;           <option value="">Rubro principal</option>

&nbsp;           <option value="plomeria">Plomería</option>

&nbsp;           <option value="electricidad">Electricidad</option>

&nbsp;           <option value="jardineria">Jardinería</option>

&nbsp;           <option value="pintura">Pintura</option>

&nbsp;           <option value="otro">Otro</option>

&nbsp;         </select>

&nbsp;         <button type="submit" class="btn btn--primary">Enviar</button>

&nbsp;       </form>

&nbsp;     </div>

&nbsp;     <div class="img-wrapper">

&nbsp;       <img src="https://images.unsplash.com/photo-1520390138845-fd2d229dd553?auto=format\&fit=crop\&w=800\&q=60" alt="Changarín sonriendo" />

&nbsp;     </div>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <!-- POST NEED -->

&nbsp; <section id="post-need" class="section bg-grey">

&nbsp;   <div class="container grid-2">

&nbsp;     <div class="img-wrapper order-2">

&nbsp;       <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?auto=format\&fit=crop\&w=800\&q=60" alt="Cliente satisfecho" />

&nbsp;     </div>

&nbsp;     <div>

&nbsp;       <h3>Publicá tu necesidad</h3>

&nbsp;       <p>Contanos qué necesitás y recibí presupuestos en minutos.</p>

&nbsp;       <form class="form" id="form-need">

&nbsp;         <input type="text" placeholder="¿Qué necesitás?" required />

&nbsp;         <textarea placeholder="Descripción del trabajo" rows="3" required></textarea>

&nbsp;         <input type="text" placeholder="Ubicación" required />

&nbsp;         <button type="submit" class="btn btn--primary">Publicar gratis</button>

&nbsp;       </form>

&nbsp;     </div>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <!-- PLANS -->

&nbsp; <section id="plans" class="section">

&nbsp;   <div class="container">

&nbsp;     <h3>Elegí tu membresía</h3>

&nbsp;     <div class="plans">

&nbsp;       <div class="plan">

&nbsp;         <h4>Gratis</h4>

&nbsp;         <span class="price">$0<span>/mes</span></span>

&nbsp;         <ul>

&nbsp;           <li>Perfil público</li>

&nbsp;           <li>Hasta 3 ofertas mensuales</li>

&nbsp;         </ul>

&nbsp;         <button class="btn btn--outline">Actual</button>

&nbsp;       </div>

&nbsp;       <div class="plan plan--featured">

&nbsp;         <h4>Pro</h4>

&nbsp;         <span class="price">$2.990<span>/mes</span></span>

&nbsp;         <ul>

&nbsp;           <li>Perfil destacado</li>

&nbsp;           <li>Ofertas ilimitadas</li>

&nbsp;           <li>Soporte prioritario</li>

&nbsp;         </ul>

&nbsp;         <button class="btn btn--primary">Comenzar</button>

&nbsp;       </div>

&nbsp;       <div class="plan">

&nbsp;         <h4>Empresa</h4>

&nbsp;         <span class="price">$9.990<span>/mes</span></span>

&nbsp;         <ul>

&nbsp;           <li>Hasta 5 cuentas</li>

&nbsp;           <li>Facturación mensual</li>

&nbsp;           <li>Dashboard avanzado</li>

&nbsp;         </ul>

&nbsp;         <button class="btn btn--outline">Contactar</button>

&nbsp;       </div>

&nbsp;     </div>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <!-- TESTIMONIOS -->

&nbsp; <section class="section bg-grey">

&nbsp;   <div class="container">

&nbsp;     <h3>Lo que dicen los changarines</h3>

&nbsp;     <div class="testimonials">

&nbsp;       <blockquote>

&nbsp;         <p>“Con Changa dejé mi empleo en fábrica y hoy gano el doble pintando casas.”</p>

&nbsp;         <cite>— Martín, pintor</cite>

&nbsp;       </blockquote>

&nbsp;       <blockquote>

&nbsp;         <p>“Me contactan todos los días y elijo los trabajos que más me convienen.”</p>

&nbsp;         <cite>— Lucía, plomera</cite>

&nbsp;       </blockquote>

&nbsp;       <blockquote>

&nbsp;         <p>“Publicar un trabajo es súper fácil. En 10 minutos ya tenía 3 presupuestos.”</p>

&nbsp;         <cite>— Diego, cliente</cite>

&nbsp;       </blockquote>

&nbsp;     </div>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <!-- ABOUT -->

&nbsp; <section id="about" class="section">

&nbsp;   <div class="container grid-2">

&nbsp;     <div>

&nbsp;       <h3>Sobre nosotros</h3>

&nbsp;       <p>Changa nació en 2024 con la misión de democratizar el acceso al trabajo informal en Argentina. Creemos que cada habilidad vale y que la tecnología puede conectar talento con oportunidades en minutos.</p>

&nbsp;     </div>

&nbsp;     <div class="img-wrapper">

&nbsp;       <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?auto=format\&fit=crop\&w=800\&q=60" alt="Equipo reunido" />

&nbsp;     </div>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <!-- CONTACT / WHATSAPP -->

&nbsp; <section id="contact" class="section">

&nbsp;   <div class="container center">

&nbsp;     <h3>¿Dudas? Escribinos</h3>

&nbsp;     <a href="https://wa.me/5491122334455?text=Hola,%20quiero%20más%20info%20sobre%20Changa" class="btn btn--wa">

&nbsp;       <i class="fab fa-whatsapp"></i> Chatear por WhatsApp

&nbsp;     </a>

&nbsp;   </div>

&nbsp; </section>



&nbsp; <footer class="footer">

&nbsp;   <p>\&copy; 2024 Changa – Hecho con ❤️ en Argentina</p>

&nbsp; </footer>



&nbsp; <script src="script.js"></script>

</body>

</html>

