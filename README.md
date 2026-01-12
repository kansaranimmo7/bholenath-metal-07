<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bholanath Metal | Ahmedabad</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2d1b15;
            --accent: #d4af37;
            --success: #25d366;
            --text-dark: #1d1d1f;
            --bg-light: #f5f5f7;
        }

        * {
            box-sizing: border-box;
            transition: all 0.3s ease;
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            background-color: var(--bg-light);
            color: var(--text-dark);
            scroll-behavior: smooth;
        }

        /* Interactive Navigation */
        header {
            background: rgba(45, 27, 21, 0.95);
            backdrop-filter: blur(10px);
            color: white;
            padding: 15px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 3px solid var(--accent);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .logo {
            font-weight: 700;
            font-size: 1.8rem;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        /* Hero Section with Animation */
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('tawa.jpg');
            /* Background trick */
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }

        /* Interactive Product Cards */
        .container {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 2.5rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            width: 80px;
            height: 4px;
            background: var(--accent);
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 40px;
        }

        .product-card {
            background: white;
            border-radius: 25px;
            overflow: hidden;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.05);
            cursor: pointer;
            border: 1px solid transparent;
        }

        .product-card:hover {
            transform: translateY(-15px);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.15);
            border-color: var(--accent);
        }

        .product-card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }

        .product-info {
            padding: 30px;
        }

        .product-info h3 {
            margin: 0 0 10px;
            font-size: 1.5rem;
            color: var(--primary);
        }

        /* Floating WhatsApp Button */
        .floating-wa {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: var(--success);
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            box-shadow: 0 10px 25px rgba(37, 211, 102, 0.4);
            z-index: 999;
            text-decoration: none;
        }

        .floating-wa:hover {
            transform: scale(1.1) rotate(15deg);
        }

        .cta-section {
            background: var(--primary);
            color: white;
            padding: 80px 20px;
            text-align: center;
            border-radius: 50px 50px 0 0;
            margin-top: 50px;
        }

        .whatsapp-btn {
            background: var(--success);
            color: white;
            padding: 20px 45px;
            text-decoration: none;
            border-radius: 100px;
            font-weight: 700;
            display: inline-block;
            font-size: 1.2rem;
            margin-top: 30px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .whatsapp-btn:hover {
            background: #1eb954;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
        }

        footer {
            background: #111;
            color: #888;
            padding: 40px;
            text-align: center;
        }

        /* Mobile Adjustments */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.2rem;
            }

            .section-title {
                font-size: 1.8rem;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">BHOLANATH METAL</div>
    </header>

    <section class="hero">
        <h1>Premium Iron Utensils</h1>
        <p>Crafting Quality Since Generations in Ahmedabad</p>
        <a href="#products" class="whatsapp-btn"
            style="background: var(--accent); font-size: 1rem; padding: 12px 30px;">View Products</a>
    </section>

    <section class="container" id="products">
        <h2 class="section-title">Our Best Sellers</h2>
        <div class="gallery">

            <div class="product-card"
                onclick="window.location.href='https://wa.me/919924626013?text=I am interested in Iron Tawa'">
                <img src="tawa.jpg" alt="Iron Tawa">
                <div class="product-info">
                    <h3>Pure Iron Tawa</h3>
                    <p>Heavy-duty, traditional non-stick iron for perfect parathas.</p>
                    <span style="color: var(--success); font-weight: bold;">Click to Enquire →</span>
                </div>
            </div>

            <div class="product-card"
                onclick="window.location.href='https://wa.me/919924626013?text=I am interested in Stainless Steel Items'">
                <img src="khalli.jpg" alt="Steel Items">
                <div class="product-info">
                    <h3>Premium Utensils</h3>
                    <p>High-grade stainless steel & aluminum kitchenware collection.</p>
                    <span style="color: var(--success); font-weight: bold;">Click to Enquire →</span>
                </div>
            </div>

            <div class="product-card"
                onclick="window.location.href='https://wa.me/919924626013?text=I am interested in Premium Patli'">
                <img src="patli.jpg" alt="Patli">
                <div class="product-info">
                    <h3>Heavy Duty Patli</h3>
                    <p>Balanced and stable rolling boards for smooth daily use.</p>
                    <span style="color: var(--success); font-weight: bold;">Click to Enquire →</span>
                </div>
            </div>

        </div>
    </section>

    <a href="https://wa.me/919924626013" class="floating-wa" title="Chat with us">
        <span style="font-size: 35px;">💬</span>
    </a>

    <section class="cta-section">
        <h2>Ready to Upgrade Your Kitchen?</h2>
        <p>Get the best rates directly from our factory in Odhav.</p>
        <p><strong>📍 Ahmedabad, Gujarat</strong></p>
        <a href="https://wa.me/919924626013" class="whatsapp-btn">Order Now via WhatsApp</a>
    </section>

    <footer>
        <p>&copy; 2026 Bholanath Metal - Ahmedabad. Quality You Can Trust.</p>
    </footer>

</body>

</html>
