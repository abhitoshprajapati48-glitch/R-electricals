<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RS Electrical & Construction Services | Licensed Electrical Contractor</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Orbitron:wght@600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        :root {
            --bg-main: #121619;
            --bg-card: #1c2226;
            --accent-blue: #00b4d8;
            --accent-gold: #ffb703;
            --text-light: #f8f9fa;
            --text-muted: #a0aab2;
            --border-color: #2a343b;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg-main);
            color: var(--text-light);
            line-height: 1.6;
            background-image: 
                radial-gradient(circle at 80% 20%, rgba(0, 180, 216, 0.08) 0%, transparent 40%),
                radial-gradient(circle at 20% 80%, rgba(255, 183, 3, 0.05) 0%, transparent 40%);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.2rem 8%;
            background-color: rgba(28, 34, 38, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-color);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo { display: flex; align-items: center; gap: 12px; }
        .logo-text { font-family: 'Orbitron', sans-serif; font-size: 1.4rem; font-weight: 800; }
        .logo-text span { color: var(--accent-blue); }

        .btn-call {
            background: linear-gradient(135deg, var(--accent-blue), #0077b6);
            color: #fff;
            padding: 0.6rem 1.4rem;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 700;
        }

        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 4rem 8%;
            gap: 2rem;
            flex-wrap: wrap;
        }

        .hero-content { max-width: 550px; }
        .hero h1 { font-size: 2.8rem; font-weight: 800; line-height: 1.2; margin-bottom: 1rem; }
        .hero h1 span { color: var(--accent-blue); }
        .hero p { color: var(--text-muted); margin-bottom: 1.5rem; }

        .contractor-badges {
            display: flex;
            gap: 15px;
            margin-bottom: 1.5rem;
            font-size: 0.85rem;
            color: var(--accent-gold);
        }

        .hero-card {
            background-color: var(--bg-card);
            border: 1px solid var(--border-color);
            padding: 2rem;
            border-radius: 12px;
            width: 100%;
            max-width: 420px;
        }

        .quote-form input, .quote-form select, .quote-form textarea {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            background: var(--bg-main);
            border: 1px solid var(--border-color);
            color: var(--text-light);
            border-radius: 6px;
        }

        .btn-submit {
            width: 100%;
            background: linear-gradient(135deg, var(--accent-gold), #e09f00);
            color: #000;
            padding: 0.8rem;
            border: none;
            font-weight: 700;
            border-radius: 6px;
            cursor: pointer;
        }

        .services { padding: 4rem 8%; }
        .services-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1.5rem; margin-top: 2rem;}
        .service-card { background: var(--bg-card); padding: 1.8rem; border-radius: 8px; border: 1px solid var(--border-color); }
        .service-card i { font-size: 2rem; color: var(--accent-blue); margin-bottom: 1rem; }

        footer { text-align: center; padding: 2rem; background-color: var(--bg-card); border-top: 1px solid var(--border-color); color: var(--text-muted); }
    </style>
</head>
<body>

    <nav>
        <div class="logo">
            <i class="fa-solid fa-helmet-safety" style="color: var(--accent-gold); font-size: 1.5rem;"></i>
            <div class="logo-text">RS <span>ELECTRICAL & CONTRACTING</span></div>
        </div>
        <a href="tel:+918591328092" class="btn-call"><i class="fa-solid fa-phone"></i> Call Contractor</a>
    </nav>

    <section class="hero">
        <div class="hero-content">
            <div class="contractor-badges">
                <span><i class="fa-solid fa-certificate"></i> Government Licensed</span>
                <span><i class="fa-solid fa-shield-check"></i> Insured Work</span>
            </div>
            <h1>Commercial & Residential <span>Electrical</span> Contractor</h1>
            <p>Turnkey electrical contracting, industrial panel wiring, structural cable setup, and maintenance across Mira Bhayandar[cite: 1].</p>
        </div>

        <div class="hero-card">
            <h3>Request Contractor Quote</h3>
            <p style="font-size:0.85rem; color: var(--text-muted); margin-bottom: 1rem;">Get an estimated proposal for your project.</p>
            <form class="quote-form">
                <input type="text" placeholder="Your Name" required>
                <input type="tel" placeholder="Phone Number" required>
                <select>
                    <option>Commercial Construction</option>
                    <option>Residential Wiring</option>
                    <option>Industrial Electrical Setup</option>
                    <option>Emergency Maintenance</option>
                </select>
                <button type="submit" class="btn-submit">Submit Request</button>
            </form>
        </div>
    </section>

    <section class="services">
        <h2 style="text-align: center;">Contracting Capabilities</h2>
        <div class="services-grid">
            <div class="service-card">
                <i class="fa-solid fa-building-flag"></i>
                <h3>Commercial Projects</h3>
                <p>Complete conduits, layout planning, and high-load wiring setups for builders and developers.</p>
            </div>
            <div class="service-card">
                <i class="fa-solid fa-industry"></i>
                <h3>Industrial Maintenance</h3>
                <p>Control panel installations, three-phase wiring, and heavy machinery setups.</p>
            </div>
            <div class="service-card">
                <i class="fa-solid fa-house-gear"></i>
                <h3>Turnkey Residential</h3>
                <p>Whole-building wiring, smart distribution boards, and safety system setups[cite: 1].</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 RS Electricals & Contracting. Licensed General Electrical Contractor[cite: 1].</p>
    </footer>

</body>
</html>
