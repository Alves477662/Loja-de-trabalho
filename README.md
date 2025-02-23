<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balong - Loja de Tênis</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            text-align: center;
        }
        header {
            padding: 20px 0;
            font-size: 24px;
            font-weight: bold;
        }
        .product {
            display: inline-block;
            margin: 20px;
            padding: 20px;
            border: 1px solid #444;
            border-radius: 10px;
            background-color: #111;
        }
        .product img {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }
        .buy-button {
            display: block;
            margin-top: 10px;
            padding: 10px;
            background-color: #444;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .buy-button:hover {
            background-color: #666;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>Balong - Loja de Tênis</header>
        <div class="product">
            <img src="tenis1.jpg" alt="Tênis Modelo X">
            <p>Tênis Modelo X</p>
            <p>R$ 299,90</p>
            <button class="buy-button">Comprar via Pix</button>
        </div>
    </div>
</body>
</html>
