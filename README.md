<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: blue;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        #planes {
            border: 1px solid white;
            height: 80%;
            margin: 20px auto;
            box-sizing: border-box;
            display: flex;
            flex-wrap: wrap;
        }

        .plan {
            background-color: #f2f2f2;
            padding: 15px;
            margin: 10px;
            border-radius: 10px;
            width: 27%;
            text-align: center
            
        }

        a.button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #3498db;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        a.button:hover {
            background-color: #2980b9;
        }

        @media (max-width: 700px) {
            .plan {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <h1>Elija el plan más adecuado...</h1>
    <div id="planes">
        <div class="plan" style=" font-size: 35px;"">Principiante
            <p style=" font-size: 18px;"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores nam, quasi adipisci optio reprehenderit expedita voluptatem blanditiis culpa totam unde tempore, fugiat saepe dolorem iste asperiores commodi et ad magnam.</p>
            <p style="font-style: italic;">10€/MES</p>
            <p><a href="#">Elegir</a></p>
        </div>
        <div class="plan" style=" font-size: 35px;"">Básico
            <p style=" font-size: 18px;"> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores nam, quasi adipisci optio reprehenderit expedita voluptatem blanditiis culpa totam unde tempore, fugiat saepe dolorem iste asperiores commodi et ad magnam.</p>
            <p style="font-style: italic;">15€/MES</p>
            <p><a href="#">Elegir</a></p>
        </div>
        <div class="plan" style=" font-size: 35px;"">Premium
            <p style=" font-size: 18px;" > Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores nam, quasi adipisci optio reprehenderit expedita voluptatem blanditiis culpa totam unde tempore, fugiat saepe dolorem iste asperiores commodi et ad magnam.</p>
            <p style="font-style: italic;">20€/MES</p>
            <p><a href="#">Elegir</a></p>
        </div>
    </div>
    <a href="#" class="button">Elegir</a>
</body>
</html>

