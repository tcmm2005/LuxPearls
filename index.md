<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Showcase</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #f8c8d7, #ffaad4);
            color: #333;
            overflow-x: hidden;
        }

        header {
            background-color: #ff66b2;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            text-transform: uppercase;
            letter-spacing: 3px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .options2 {
            text-align: center;
            margin: 20px 0;
        }

        .options2 button {
            background-color: #ff66b2;
            color: white;
            font-size: 1.2em;
            padding: 12px 20px;
            margin: 10px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .options2 button:hover {
            background-color: #ff3385;
        }

        .products-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 40px;
            max-width: 1200px;
            margin: 30px auto;
            border-radius: 10px;
            background-color: #ffffffc0;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }

        .product {
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s ease-in-out;
        }

        .product:hover {
            transform: translateY(-8px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .product img {
            width: 100%;
            height: auto;
        }

        .product-info {
            padding: 15px;
            text-align: center;
        }

        .product-name {
            font-size: 1.4em;
            font-weight: bold;
            margin-bottom: 10px;
            color: #ff66b2;
        }

        .product-price {
            font-size: 1.2em;
            color: #444;
            margin-top: 5px;
        }

        .options {
            text-align: center;
            margin: 20px 0;
        }

        .options button {
            background-color: #ff66b2;
            color: white;
            font-size: 1.5em; /* Larger size for buttons 1 and 2 */
            padding: 15px 25px; /* Adjust padding for a bigger look */
            margin: 10px;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .options button:hover {
            background-color: #ff3385;
        }

        @media screen and (max-width: 768px) {
            header {
                font-size: 1.8em;
            }

            .products-container {
                grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
                padding: 15px;
            }

            .product-info .product-name {
                font-size: 1.2em;
            }

            .product-info .product-price {
                font-size: 1.1em;
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
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.42_9f1e4846.jpg" alt="Silver Shadow">
            <div class="product-info">
                <div class="product-name">Silver Shadow</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.42_702684ac.jpg" alt="Volcanic Gold">
            <div class="product-info">
                <div class="product-name">Volcanic Gold</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.43_c43c62ba.jpg" alt="White Sands">
            <div class="product-info">
                <div class="product-name">White Sands</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.46_cb63a0c9.jpg" alt="Black Sun">
            <div class="product-info">
                <div class="product-name">Black Sun</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.47_98ac9c04.jpg" alt="Lava Luxe">
            <div class="product-info">
                <div class="product-name">Lava Luxe</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.47_d48b22aa.jpg" alt="Crystal Stream">
            <div class="product-info">
                <div class="product-name">Crystal Stream</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.49_ee1d9e47.jpg" alt="Pearl Elegance">
            <div class="product-info">
                <div class="product-name">Pearl Elegance</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.50_11c7406c.jpg" alt="Honeycomb">
            <div class="product-info">
                <div class="product-name">Honeycomb</div>
                <div class="product-price">Price: TBD</div>
            </div>
        </div>

        <div class="product">
            <img src="C:\Users\tiger\Pictures\Camera Roll\WhatsApp Image 2024-12-27 at 13.17.51_addeec79.jpg" alt="Silver Streak">
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

