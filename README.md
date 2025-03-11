<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Meu Amor ❤️</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffe6e6;
            padding: 50px;
        }
        #imagem {
            display: none;
            width: 80%;
            max-width: 500px;
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .botao {
            background-color: #ff4d4d;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .botao:hover {
            background-color: #cc0000;
        }
    </style>
</head>
<body>
    <h1>Oi, meu amor! 💖</h1>
    <p>Clique no botão abaixo para ver algo especial! 😊</p>
    <button class="botao" onclick="mostrarImagem()">Clique aqui</button>
    <br>
    <img id="imagem" src=["SUA_IMAGEM_AQUI"](https://photos.google.com/search/Cg1NYWlzIHJlY2VudGVzIggSBgoEcgIKACjv2%2FO42DI%3D/photo/AF1QipMn4QX-F-oej1t7Nu5splamBrNPYAk_pt7xI5Pu) alt="Nossa Foto Juntos">

    <script>
        function mostrarImagem() {
            document.getElementById("imagem").style.display = "block";
        }
    </script>
</body>
</html>
