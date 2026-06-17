# bytecraft<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ByteCraft | Premium Digital Solutions</title>
    <style>
        /* Modern & Smart Dark Theme Coding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #0b0f19;
            color: #ffffff;
            overflow-x: hidden;
        }

        /* Header / Navigation */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 8%;
            background: rgba(11, 15, 25, 0.8);
            backdrop-filter: blur(10px);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #00f2fe;
            letter-spacing: 1px;
        }

        .logo span {
            color: #4facfe;
        }

        nav a {
            color: #ffffff;
            text-decoration: none;
            margin-left: 35px;
            font-size: 16px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #00f2fe;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
            background: radial-gradient(circle at center, #1e293b 0%, #0b0f19 70%);
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #00f2fe, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.2rem;
            color: #94a3b8;
            max-width: 600px;
            margin-bottom: 40px;
            line-height: 1.6;
        }

        .cta-btn {
            background: linear-gradient(45deg, #00f2fe, #4facfe);
            color: #0b0f19;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            font-size: 18px;
            box-shadow: 0 4px 15px rgba(0, 242, 254, 0.4);
            transition: 0.3s transform, 0.3s box-shadow;
        }

        .cta-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 242, 254, 0.6);
        }

        /* Services Section */
        .services {
            padding: 100px 8%;
            text-align: center;
        }

        .services h2 {
            font-size: 2.5rem;
            margin-bottom: 50px;
            color: #ffffff;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background: #131c2e;
            padding: 40px 30px;
            border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: #00f2fe;
            box-shadow: 0 10px 20px rgba(0, 242, 254, 0.1);
        }

        .card h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: #4facfe;
        }

        .card p {
            color: #94a3b8;
            font-size: 15px;
            line-height: 1.6;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            color: #64748b;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">Byte<span>Craft</span></div>
        <nav>
            <a href="#">Home</a>
            <a href="#services">Services</a>
            <a href="#contact" id="contact-nav">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Transforming Bytes Into Digital Art</h1>
        <p>We craft premium websites, smart digital experiences, and high-performance modern solutions for your business.</p>
        <a href="https://fiverr.com" target="_blank" class="cta-btn" id="main-cta">Get Started</a>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <h2>Our Expertises</h2>
        <div class="services-grid">
            <div class="card">
                <h3>Web Development</h3>
                <p>Creating fast, modern, and fully responsive websites tailored to your unique brand needs.</p>
            </div>
            <div class="card">
                <h3>UI/UX Design</h3>
                <p>Designing smart, clean, and interactive user interfaces for apps and digital platforms.</p>
            </div>
            <div class="card">
                <h3>Digital Solutions</h3>
                <p>Helping your business scale up with innovative tools, tech support, and custom automations.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 ByteCraft. All rights reserved.</p>
    </footer>

    <!-- Simple Smart Interactive JavaScript -->
    <script>
        document.getElementById('main-cta').addEventListener('click', function() {
            console.log('Redirecting to order page...');
        });
        
        document.getElementById('contact-nav').addEventListener('click', function(e) {
            e.preventDefault();
            alert('ඔබේ Fiverr, Upwork හෝ WhatsApp Link එක මෙතැනට සම්බන්ධ කළ හැක!');
        });
    </script>
</body>
</html>
