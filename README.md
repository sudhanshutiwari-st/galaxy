</head>
<body>
    <header>
        <div class="logo">
            <h1>GALAXY</h1>
        </div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">Contact</a>
            <a href="#" id="cartLink">Cart (<span id="cartCount">0</span>)</a>
        </nav>
    </header>

    <section class="product-list">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button onclick="addToCart('Product 1', 10)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>$15.00</p>
            <button onclick="addToCart('Product 2', 15)">Add to Cart</button>
        </div>


 <section class="product-list">
        <div class="product">
            <img src="product1.jpg" alt="Product 3">
            <h3>Product 3</h3>
            <p>$10.00</p>
            <button onclick="addToCart('Product 3', 10)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="product4.jpg" alt="Product 4">
            <h3>Product 4</h3>
            <p>$15.00</p>
            <button onclick="addToCart('Product 4', 15)">Add to Cart</button>
        </div>

        <!-- More products can be added similarly -->
    </section>

    <footer>
        <p>&copy; 2024 My Shop</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
