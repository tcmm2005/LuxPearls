<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Showcase</title>
    <style>
         body {
    font-family: 'Georgia', serif; /* Elegant font */
    margin: 0;
    padding: 0;
    background: radial-gradient(circle, #ffe5f0, #ffc1d6, #ffaad4);
    color: #444;
    overflow-x: hidden;
}

header {
    background: linear-gradient(90deg, #ff66b2, #ff3385);
    color: white;
    padding: 30px 0;
    text-align: center;
    font-size: 2.5em;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 5px;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.options2 {
    text-align: center;
    margin: 30px 0;
}

.options2 button {
    background: linear-gradient(145deg, #ff66b2, #ff3385); /* Smooth gradient */
    color: white;
    font-size: 1.5em;
    padding: 18px 30px;
    margin: 10px;
    border: 2px solid transparent;
    border-radius: 25px;
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
    cursor: pointer;
    transition: all 0.3s ease, box-shadow 0.4s ease-in-out;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: bold;
}

.options2 button:hover {
    background: linear-gradient(145deg, #ff3385, #ff66b2); /* Reversed gradient */
    color: #fff;
    border: 2px solid #ff66b2;
    box-shadow: 0 8px 25px rgba(255, 105, 180, 0.5); /* Soft glowing effect */
    transform: scale(1.1); /* Slight enlargement */
    text-shadow: 0 0 15px rgba(255, 105, 180, 0.7), 0 0 25px rgba(255, 105, 180, 0.5);
}

.options2 button:focus {
    outline: none;
}

.products-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    padding: 50px;
    max-width: 1200px;
    margin: 30px auto;
    border-radius: 15px;
    background-color: rgba(255, 255, 255, 0.9);
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
}

.product {
    background: linear-gradient(135deg, #ffe5f0, #ffd6eb);
    border: 1px solid #ffaad4;
    border-radius: 15px;
    overflow: hidden;
    transition: transform 0.4s, box-shadow 0.4s ease-in-out;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.product:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.product img {
    width: 100%;
    height: auto;
    border-bottom: 2px solid #ffaad4;
}

.product-info {
    padding: 20px;
    text-align: center;
}

.product-name {
    font-size: 1.5em;
    font-weight: bold;
    margin-bottom: 10px;
    color: #ff3385;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.1);
}

.product-price {
    font-size: 1.3em;
    color: #666;
    font-style: italic;
}

.options {
    text-align: center;
    margin: 30px 0;
}

.options button {
    background: linear-gradient(145deg, #ff66b2, #ff3385); /* Smooth gradient */
    color: white;
    font-size: 1.5em;
    padding: 15px 30px;
    margin: 10px;
    border: none;
    border-radius: 25px;
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
    cursor: pointer;
    transition: all 0.3s ease, box-shadow 0.4s ease-in-out;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: bold;
}

.options button:hover {
    background: linear-gradient(145deg, #ff3385, #ff66b2); /* Reversed gradient */
    color: #fff;
    border: 2px solid #ff66b2;
    box-shadow: 0 8px 25px rgba(255, 105, 180, 0.5); /* Soft glowing effect */
    transform: scale(1.1); /* Slight enlargement */
    text-shadow: 0 0 15px rgba(255, 105, 180, 0.7), 0 0 25px rgba(255, 105, 180, 0.5);
}

.options button:focus {
    outline: none;
}

@media screen and (max-width: 768px) {
    header {
        font-size: 2em;
    }

    .products-container {
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        padding: 20px;
    }

    .product-info .product-name {
        font-size: 1.3em;
    }

    .product-info .product-price {
        font-size: 1.2em;
    }
}
    </style>
</head>
<body>
    <div class="options2">
        <button onclick="gotoobracelet()">Bracelet</button>
        <button onclick="gotoonecklace()">Necklace</button>
        <button onclick="gotooearings()">Earrings</button>
    </div>

    <header>Bracelets</header>

    <div class="products-container">
        <div class="product">
            <img src="https://i.imgur.com/suUIfmH.jpeg" alt="Midnight Bloom">
            <div class="product-info">
                <div class="product-name">Midnight Bloom</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/vtEvs3z.jpeg" alt="Silver Shadow">
            <div class="product-info">
                <div class="product-name">Silver Shadow</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/fJyDbrG.jpeg" alt="Volcanic Gold">
            <div class="product-info">
                <div class="product-name">Volcanic Gold</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/T2ZPcH3.jpeg" alt="White Sands">
            <div class="product-info">
                <div class="product-name">White Sands</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/UCROymP.jpeg" alt="Black Sun">
            <div class="product-info">
                <div class="product-name">Black Sun</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/BdtqlkH.jpeg" alt="Lava Luxe">
            <div class="product-info">
                <div class="product-name">Lava Luxe</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/3zrQFiX.jpeg" alt="Crystal Stream">
            <div class="product-info">
                <div class="product-name">Crystal Stream</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/CtmJvmh.jpeg" alt="Pearl Elegance">
            <div class="product-info">
                <div class="product-name">Pearl Elegance</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/i8tt7uE.jpeg" alt="Honeycomb">
            <div class="product-info">
                <div class="product-name">Honeycomb</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="https://i.imgur.com/y74x33K.jpeg" alt="Silver Streak">
            <div class="product-info">
                <div class="product-name">Silver Streak</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>
    </div>

    <div class="options">
        <button onclick="gotoo1()">1</button>
        <button onclick="gotoo2()">2</button>
    </div>

    <script>
        function gotoo1() {
            window.location.href = "bracelet.html";
        }

        function gotoo2() {
            window.location.href = "bracelet2.html";
        }

        function gotoobracelet() {
            window.location.href = "bracelet.html";
        }

        function gotoonecklace() {
            window.location.href = "necklace.html";
        }

        function gotooearings() {
            window.location.href = "earings.html";
        }
    </script>
</body>

