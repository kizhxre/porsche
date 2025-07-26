<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Porsche Car Showroom</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: black;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .car-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin: 20px;
        }
        .car {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 15px;
            padding: 15px;
            width: 300px;
            text-align: center;
        }
        .car img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Porsche Car Showroom</h1>
    <p>Explore the Latest Porsche Models</p>
</header>

<section class="car-list">
    <div class="car">
        <img src="https://www.porsche.com/filestore/image/multimedia/none/992-carrera-modelimage-sideshot/thumbwhite/abc3e63a-ecb1-11eb-80d5-005056bbdc38;sG;twebp/porsche-thumbwhite.webp" alt="Porsche 911">
        <h3>Porsche 911</h3>
        <p>Iconic design. Timeless performance. Starting at $114,400.</p>
    </div>
    <div class="car">
        <img src="https://files.porsche.com/filestore/image/multimedia/none/j1-taycan-cross-turismo-modelimage-sideshot/thumbwhite/7313e004-ecb1-11eb-80d5-005056bbdc38;sF;twebp/porsche-thumbwhite.webp" alt="Porsche Taycan">
        <h3>Porsche Taycan</h3>
        <p>Electric performance. Unmatched acceleration. Starting at $86,700.</p>
    </div>
    <div class="car">
        <img src="https://files.porsche.com/filestore/image/multimedia/none/cayenne-modelimage-sideshot/thumbwhite/48e91a04-ecb1-11eb-80d5-005056bbdc38;sF;twebp/porsche-thumbwhite.webp" alt="Porsche Cayenne">
        <h3>Porsche Cayenne</h3>
        <p>Luxury SUV with Porsche DNA. Starting at $79,200.</p>
    </div>
</section>

<footer>
    &copy; 2025 Porsche Showroom. All rights reserved.
</footer>

</body>
</html>
