 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NutriLife - Complete Nutrition Made Simple</title>
    <style>
        :root {
            --primary-color: #FE5000;    /* Orange */
            --secondary-color: #000000;   /* Black */
            --light-color: #D3D3D3;      /* Light Gray */
        }
        
        body {
            font-family: 'Arial', sans-serif;  /* We can update this with your brand font */
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: white;
        }

        header {
            background-color: var(--light-color);
            color: var(--secondary-color);
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: var(--secondary-color);
            font-weight: 500;
        }

        .hero-section {
            margin-top: 80px;
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1490818387583-1baba5e638af');
            background-size: cover;
            color: white;
            text-align: center;
            padding: 150px 20px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .cta-button {
            background-color: var(--primary-color);
            color: white;
            padding: 12px 30px;
            border-radius: 4px;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        .cta-button:hover {
            background-color: #00a884;
        }

        .benefits-section {
            padding: 4rem 2rem;
            background-color: var(--light-color);
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .benefit-card {
            text-align: center;
            padding: 2rem;
        }

        .benefit-card img {
            width: 80px;
            height: 80px;
            margin-bottom: 1rem;
        }

        .featured-products {
            padding: 4rem 2rem;
            text-align: center;
        }

        .product-image {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 8px;
        }

        .nutrition-facts {
            background-color: white;
            padding: 4rem 2rem;
            text-align: center;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
            max-width: 1200px;
            margin: 2rem auto;
        }

        .stat-card {
            padding: 2rem;
            background-color: var(--light-color);
            border-radius: 8px;
        }

        .testimonials {
            padding: 4rem 2rem;
            background-color: var(--light-color);
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .testimonial-card {
            background-color: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">NutriLife</div>
            <div>
                <a href="#products">Products</a>
                <a href="#nutrition">Nutrition</a>
                <a href="#about">About</a>
                <a href="#blog">Blog</a>
                <a href="#cart" class="cta-button">Shop Now</a>
            </div>
        </nav>
    </header>

    <section class="hero-section">
        <h1>Transform Your Health</h1>
        <p>Complete nutrition with real ingredients. No compromises.</p>
        <a href="#shop" class="cta-button">Shop Now</a>
    </section>

    <section class="benefits-section">
        <div class="benefits-grid">
            <div class="benefit-card">
                <img src="path/to/plant-icon.png" alt="Plant-Based">
                <h3>100% Plant-Based</h3>
                <p>Sustainable nutrition from natural sources</p>
            </div>
            <div class="benefit-card">
                <img src="path/to/nutrition-icon.png" alt="Complete Nutrition">
                <h3>Complete Nutrition</h3>
                <p>All essential nutrients in every serving</p>
            </div>
            <div class="benefit-card">
                <img src="path/to/convenience-icon.png" alt="Convenient">
                <h3>Quick & Easy</h3>
                <p>Ready in seconds, perfect for busy lifestyles</p>
            </div>
        </div>
    </section>
</body>
</html>
