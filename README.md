# INKA-nation 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>INKA Nation - Label</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; background: #0d0d0d; color: white; }
    header { background: url('https://images.unsplash.com/photo-1507874457470-272b3c8d8ee2') center/cover no-repeat; height: 100vh; display: flex; align-items: center; justify-content: center; flex-direction: column; text-align: center; }
    header h1 { font-size: 4rem; text-transform: uppercase; letter-spacing: 5px; }
    header p { font-size: 1.5rem; margin-top: 10px; }
    nav { position: fixed; top: 0; width: 100%; background: rgba(0,0,0,0.8); padding: 10px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    h2 { font-size: 2.5rem; margin-bottom: 20px; text-align: center; }
    .artistes { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .artiste { background: #1a1a1a; padding: 20px; border-radius: 10px; text-align: center; }
    .artiste img { width: 100%; border-radius: 10px; }
    footer { background: #111; text-align: center; padding: 20px; margin-top: 40px; }
  </style>
</head>
<body>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#apropos">À propos</a>
    <a href="#artistes">Artistes</a>
    <a href="#musique">Musique</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="accueil">
    <h1>INKA Nation</h1>
    <p>Un label qui fait vibrer l’Afrique et le monde</p>
  </header>

  <section id="apropos">
    <h2>À propos</h2>
    <p>INKA Nation est un label indépendant qui met en avant les talents africains et internationaux. Notre mission est de donner une voix aux artistes et de partager une musique authentique et universelle.</p>
  </section>

  <section id="artistes">
    <h2>Nos Artistes</h2>
    <div class="artistes">
      <div class="artiste">
        <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e" alt="Artiste 1">
        <h3>Artiste 1</h3>
        <p>Afrobeat / World Music</p>
      </div>
      <div class="artiste">
        <img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91" alt="Artiste 2">
        <h3>Artiste 2</h3>
        <p>Hip-Hop / RnB</p>
      </div>
    </div>
  </section>

  <section id="musique">
    <h2>Écoute Notre Musique</h2>
    <div style="text-align:center;">
      <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1DXbYM3nMM0oPk" width="80%" height="380" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">📧 contact@inkanation.com</p>
    <p style="text-align:center;">📱 +243 999 999 999</p>
    <p style="text-align:center;">🌍 Suivez-nous sur Instagram, Facebook et YouTube</p>
  </section>

  <footer>
    <p>© 2025 INKA Nation. Tous droits réservés.</p>
  </footer>

</body>
</html>
