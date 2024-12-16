# buonbantainguyen
tài nguyên mmo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MMO Resource Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>MMO Resource Shop</h1>
        <nav>
            <ul>
                <li><a href="#products">Products</a></li>
                <li><a href="#cart">Cart</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="products">
            <h2>Available Resources</h2>
            <div class="product-list">
                <!-- Product 1 -->
                <div class="product">
                    <h3>Gold Coins</h3>
                    <p>Price: $10 / 1,000 coins</p>
                    <button onclick="addToCart('Gold Coins', 10)">Add to Cart</button>
                </div>
                <!-- Product 2 -->
                <div class="product">
                    <h3>XP Boost</h3>
                    <p>Price: $5 / 1 hour</p>
                    <button onclick="addToCart('XP Boost', 5)">Add to Cart</button>
                </div>
                <!-- Product 3 -->
                <div class="product">
                    <h3>Premium Gear</h3>
                    <p>Price: $50 / set</p>
                    <button onclick="addToCart('Premium Gear', 50)">Add to Cart</button>
                </div>
            </div>
        </section>

        <section id="cart">
            <h2>Your Cart</h2>
            <ul id="cart-list">
                <!-- Cart items will appear here -->
            </ul>
            <p>Total: $<span id="total-price">0</span></p>
            <button id="checkout-button" onclick="checkout()">Checkout</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 MMO Resource Shop</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
