<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Minimalist beauty products store: skincare, makeup, and perfumes.">
    <title>Beauty Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .category {
            margin-bottom: 40px;
        }
        .category h2 {
            text-align: center;
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #000;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            font-size: 1.2rem;
            color: #000;
            margin: 10px 0;
        }
        .product p {
            color: #666;
            font-size: 0.9rem;
        }
        .product button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 1rem;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #000;
        }
        footer {
            background-color: #000;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Beauty Store</h1>
    </header>
    <nav>
        <a href="#skincare">Skincare</a>
        <a href="#makeup">Makeup</a>
        <a href="#perfumes">Perfumes</a>
    </nav>

    <div class="container">
        <!-- Skincare Section -->
        <section id="skincare" class="category">
            <h2>Skincare</h2>
            <div class="products">
                <!-- Example Product -->
                <div class="product">
                    <img src="https://via.placeholder.com/200" alt="Product 1">
                    <h3>Moisturizing Cream</h3>
                    <p>$20.00</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products here -->
            </div>
        </section>

        <!-- Makeup Section -->
        <section id="makeup" class="category">
            <h2>Makeup</h2>
            <div class="products">
                <!-- Example Product -->
                <div class="product">
                    <img src="https://via.placeholder.com/200" alt="Product 2">
                    <h3>Lipstick</h3>
                    <p>$15.00</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products here -->
            </div>
        </section>

        <!-- Perfumes Section -->
        <section id="perfumes" class="category">
            <h2>Perfumes</h2>
            <div class="products">
                <!-- Example Product -->
                <div class="product">
                    <img src="https://via.placeholder.com/200" alt="Product 3">
                    <h3>Floral Perfume</h3>
                    <p>$50.00</p>
                    <button>Add to Cart</button>
                </div>
                <!-- Add more products here -->
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Beauty Store. All rights reserved.</p>
    </footer>
</body>
</html>
