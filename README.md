# Lyly-daisy-flowers
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lyly Daisy Flowers - Valentine's Special</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>❤️ Welcome to Lyly Daisy Flowers ❤️</h1>
        <p>Celebrate Love with Beautiful Flowers!</p>
    </header>

    <section class="flowers">
        <div class="flower-card">
            <img src="rose.jpg" alt="Red Rose">
            <h2>Red Roses</h2>
            <p>Symbol of love and passion</p>
            <button onclick="orderNow('Red Roses')">Order Now</button>
        </div>

        <div class="flower-card">
            <img src="tulip.jpg" alt="Tulips">
            <h2>Tulips</h2>
            <p>Perfect for expressing deep emotions</p>
            <button onclick="orderNow('Tulips')">Order Now</button>
        </div>

        <div class="flower-card">
            <img src="lily.jpg" alt="Lilies">
            <h2>White Lilies</h2>
            <p>Represents purity and devotion</p>
            <button onclick="orderNow('White Lilies')">Order Now</button>
        </div>
    </section>

    <footer>
        <p>❤️ Order now and surprise your loved ones! ❤️</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #fff0f5;
    color: #d63384;
}

header {
    background-color: #ff4d6d;
    padding: 20px;
    color: white;
}

.flowers {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.flower-card {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    width: 200px;
}

.flower-card img {
    width: 100%;
    border-radius: 10px;
}

button {
    background-color: #ff4d6d;
    color: white;
    border: none;
    padding: 10px;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #d63384;
}

footer {
    margin-top: 20px;
    padding: 10px;
    background-color: #ff4d6d;
    color: white;
}
function orderNow(flower) {
    alert("You have selected " + flower + "! We will contact you soon.");
}
