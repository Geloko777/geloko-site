<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GELÔKO - O frio que conquista</title>
    <style>
        body {
            margin: 0;
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            overflow-x: hidden;
        }
        header {
            text-align: center;
            padding: 30px 0;
            font-size: 40px;
            font-weight: bold;
            color: #00ffff;
        }
        .sub {
            text-align: center;
            font-size: 20px;
            color: #ccc;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        .produto {
            background-color: #111;
            border-radius: 10px;
            padding: 20px;
            transition: 0.5s;
            cursor: pointer;
        }
        .produto:hover {
            transform: scale(1.05);
            background-color: #222;
        }
        .produto img {
            width: 200px;
            border-radius: 10px;
        }
        .botao {
            display: block;
            margin: 30px auto;
            background-color: #00ffff;
            color: black;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-size: 20px;
            text-decoration: none;
        }
        .gelo {
            position: fixed;
            top: -100px;
            left: 50%;
            font-size: 50px;
            opacity: 0.2;
            animation: cair 6s linear infinite;
        }
        @keyframes cair {
            0% {top: -100px; left: 50%;}
            100% {top: 100%; left: 55%;}
        }
    </style>
</head>
<body>

<header>GELÔKO</header>
<div class="sub">O frio que conquista</div>

<div class="container">
    <div class="produto">
        <img src="https://i.imgur.com/FOgzE9r.png" alt="Gelo Tradicional">
        <p style="text-align:center;">Gelo Tradicional</p>
    </div>

    <div class="produto">
        <img src="https://i.imgur.com/LkXU2Sx.png" alt="Gelo Premium">
        <p style="text-align:center;">Gelo Premium</p>
    </div>
</div>

<a class="botao" href="https://linktr.ee/mansao_marombaro?utm_source=linktree_profile_share&ltsid=5b5f13c1-793b-4774-be13-ce9161850a98" target="_blank">FALE CONOSCO NO WHATSAPP</a>

<div class="gelo">❄️</div>

<audio autoplay loop>
  <source src="https://www.fesliyanstudios.com/play-mp3/387" type="audio/mpeg">
</audio>

</body>
</html>
