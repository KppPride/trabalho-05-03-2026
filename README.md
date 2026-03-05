# trabalho-05-03-2026

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Buggati</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #00420e, #022452);
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(to right, #00420e, #022452);
            color: #000000;
            padding: 15px;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .card {
           background: linear-gradient(to right, #d3f0ed, #c8f7d3);
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        img {
            width: 300px;
            border-radius: 8px;
        }

        a {
            color: #32db49;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: #07e2fa;
        }

        button {
            background-color: #32db49;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #c29fa1;
        }

        footer {
            background-color: #000000;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>

</head>
<body>

<header>
    <h1>Farmadores de Aura 67</h1>
    <p>67 & im at the club</p>
</header>

<main>

    <div class="card">
        <h1>Sobre o aluno</h2>
        <p>Nome:Miguel, Luiz, Josué e Ana Luiza</p>
        <p>Turma:301</p>
        <p>Data: 25 / 02 / 2026</p>
    </div>

    <div class="card">
        <h2>Variações de Farmar AURA</h2>
        <ul>
            <li>67 SIX SEVEN</li>
            <li>IM AT THE CLUB</li>
            <li>CITY BOY</li>
            <li>PARALINFO</li>
        </ul>
    </div>

    <div class="card">
<center>
        <h2>SIX SEVEN</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwjVjuWOkL-7pCAWlUiDqkak71d2k4XqHiTg&s">
</center>
    </div>

<div class="card">
<center>
        <h2>IA AM THE CLUB</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSg9pjPb1DrvpNAGKdKGQSAl5o0vcOxdKqeeA&s">
</center>
    </div>

<div class="card">
<center>
        <h2>CITY BOY</h2>
        <img src="https://i.scdn.co/image/ab67616d0000b2738ffb2205086af3902fc600ff">
</center>
    </div>

<div class="card">
<center>
        <h2>PARALINFO</h2>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLfEI9mx-iSwupIcDSsTToD10OIoq_nSjR5w&s">
</center>
    </div>

    <div class="card">
        <h2>SIX SEVEN</h2>
        <p>
            <a href="https://www.youtube.com/watch?v=zpJjK6YSSHo&list=PLkjoc6SW0aVG3BuL31XCLebT9eiXrUBM8">
                Abrir a AURA
            </a>
        </p>
    </div>


    <div class="card">
        <h2>IM AT THE CLUB</h2>
        <p>
            <a href="https://www.tiktok.com/@vonfagundes/video/7610842425250155794?q=IM%20AT%20THE%20CLUB&t=1772731958985">
                Abrir a AURA
            </a>
        </p>
    </div>


    <div class="card">
        <h2>CITY BOY</h2>
        <p>
            <a href="https://www.google.com/search?q=CITY+BOY&oq=CITY+BOY&gs_lcrp=EgZjaHJvbWUqBggAEEUYOzIGCAAQRRg70gEIMzMxMGowajeoAgCwAgA&sourceid=chrome&ie=UTF-8&safe=active&ssui=on#fpstate=ive&vld=cid:006f7232,vid:Ofq0n8sQWDc,st:0">
                Abrir a AURA
            </a>
        </p>
    </div>


    <div class="card">
        <h2>PARALINFO</h2>
        <p>
            <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTLfEI9mx-iSwupIcDSsTToD10OIoq_nSjR5w&s">
                Abrir a AURA
            </a>
        </p>
    </div>

    <div class="card">
        <h2>Interação</h2>
        <button onclick="mostrarMensagem()">Clique aqui</button>
        <p id="mensagem"></p>
    </div>

</main>

<footer>
    Página criada no Laboratório Web
</footer>

<script>
    function mostrarMensagem() {
        document.getElementById("mensagem").innerHTML =
        "Obrigado por chegar até aqui. :D";
    }
</script>

</body>
</html>
