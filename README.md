<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>elektro-schmidt | Sicherheitstechnik Neustadt</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Einfache, moderne Website */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; }
        
        /* Header */
        header {
            background: linear-gradient(135deg, #0A2463 0%, #1E3A8A 100%);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }
        .logo { font-size: 2.5rem; margin-bottom: 1rem; }
        .logo i { color: #FF6B35; }
        
        /* Hero Bereich */
        .hero {
            background: url('https://images.unsplash.com/photo-1558618666-fcd25c85cd64?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80') center/cover no-repeat;
            padding: 5rem 1rem;
            text-align: center;
            color: white;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background: rgba(10, 36, 99, 0.8);
        }
        .hero-content { position: relative; z-index: 1; }
        
        /* Services */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 3rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }
        .service-card:hover { transform: translateY(-5px); }
        
        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 3rem;
        }
        
        /* Button */
        .btn {
            display: inline-block;
            background: #FF6B35;
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            margin-top: 1rem;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <i class="fas fa-bolt"></i>
            <h1>elektro-schmidt</h1>
        </div>
        <p>Sicherheit s Technik GmbH Neustadt</p>
        <p>Seit 1998 – Ihr Partner für Sicherheit</p>
    </header>
    
    <section class="hero">
        <div class="hero-content">
            <h2>Elektroinstallation & Sicherheitstechnik</h2>
            <p>Brandmeldeanlagen • Videoüberwachung • Zutrittskontrolle • Notstrom</p>
            <a href="#contact" class="btn">Kostenlose Beratung anfordern</a>
        </div>
    </section>
    
    <section class="services">
        <div class="service-card">
            <i class="fas fa-fire-extinguisher" style="font-size: 3rem; color: #0A2463; margin-bottom: 1rem;"></i>
            <h3>Brandmeldeanlagen</h3>
            <p>Planung nach DIN 14675 mit modernster Technik</p>
        </div>
        <div class="service-card">
            <i class="fas fa-video" style="font-size: 3rem; color: #0A2463; margin-bottom: 1rem;"></i>
            <h3>Videoüberwachung</h3>
            <p>HD-Systeme mit KI-Analyse und Cloud-Speicher</p>
        </div>
        <div class="service-card">
            <i class="fas fa-key" style="font-size: 3rem; color: #0A2463; margin-bottom: 1rem;"></i>
            <h3>Zutrittskontrollen</h3>
            <p>Chipkarten, Fingerprint, Gesichtserkennung</p>
        </div>
        <div class="service-card">
            <i class="fas fa-bolt" style="font-size: 3rem; color: #0A2463; margin-bottom: 1rem;"></i>
            <h3>Notstromanlagen</h3>
            <p>USV-Systeme für unterbrechungsfreien Betrieb</p>
        </div>
    </section>
    
    <section id="contact" style="padding: 3rem 1rem; text-align: center;">
        <h2 style="color: #0A2463;">Kontakt & Notdienst</h2>
        <p><i class="fas fa-phone"></i> 0123 456789</p>
        <p><i class="fas fa-phone" style="color: #FF6B35;"></i> Notdienst: 0800 1234567 (24/7)</p>
        <p><i class="fas fa-map-marker-alt"></i> Neustadt, Deutschland</p>
        <p><i class="fas fa-envelope"></i> info@elektro-schmidt.de</p>
    </section>
    
    <footer>
        <p>© 2023 elektro-schmidt Sicherheit s Technik GmbH</p>
        <p>Hosted on GitHub Pages</p>
    </footer>
    
    <script>
        // Einfache Animation
        document.addEventListener('DOMContentLoaded', function() {
            console.log('⚡ elektro-schmidt Website geladen!');
        });
    </script>
</body>
</html>
