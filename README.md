<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIX CALÇADOS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #fff;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        header img {
            max-width: 200px;
        }
        .banner {
            width: 100%;
            height: 200px;
            background: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUA...') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            font-size: 2em;
            font-weight: bold;
            text-shadow: 1px 1px 5px rgba(0,0,0,0.5);
        }
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
        }
        .product-card h3 {
            margin: 10px 0 5px 0;
        }
        .product-card p {
            margin: 5px 0 10px 0;
            font-weight: bold;
            color: #333;
        }
        .buy-btn {
            display: inline-block;
            padding: 10px 15px;
            background-color: #25D366;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .buy-btn:hover {
            background-color: #1ebe5d;
        }
    </style>
</head>
<body>

    <header>
        <!-- Logo embutida -->
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAA..(sua logo em base64 aqui).." alt="MIX CALÇADOS">
    </header>

    <div class="banner">
        Bem-vindo à MIX CALÇADOS
    </div>

    <section class="products">
        <div class="product-card">
            <img src="https://via.placeholder.com/200x150.png?text=Nike+Air+Force" alt="Nike Air Force Branco">
            <h3>Nike Air Force Branco</h3>
            <p>R$85,00</p>
            <a class="buy-btn" href="https://wa.me/5571981087046" target="_blank">Comprar no WhatsApp</a>
        </div>
    </section>

</
