<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hillana Leticia Silva</title>

   <github:hillana13></github:hillana13>

    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap" rel="stylesheet">


<p id="mensagem"></p>

    <style>
        body {
            font-family: 'Quicksand', sans-serif;
            background: linear-gradient(to bottom, #e6e6fa, #d3d3d3);
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 30px auto;
            background-color: #ffffffcc;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        h1 {
            text-align: center;
            font-weight: bold;
            color: #6a0dad;
            font-size: 32px;
        }

        h2, ul {
            font-weight: bold;
            color: #1e3a8a;
            margin-top: 25px;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .button-link {
            background-color: #ff69b4; /* rosa */
            color: white;
            padding: 10px 18px;
            border-radius: 8px;
            text-decoration: none;
            display: inline-block;
            margin: 8px 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .button-link:hover {
            background-color: #cc2f76;
        }

        .foto {
            display: block;
            margin: 20px auto;
            border-radius: 100px;
            border: 5px solid #6a0dad;
            width: 200px;
            height: 200px;
            object-fit: cover;
        }

        ul {
            background-color: #f0f0f0;
            padding: 10px 20px;
            border-radius: 10px;
            list-style-type: disc;
        }

        li {
            margin-bottom: 8px;
        }

        table {
            width: 80%;
            margin: 30px auto;
            border-collapse: collapse;
            background-color: #f9f9ff;
            box-shadow: 0 0 8px rgba(0,0,0,0.1);
        }

        th, td {
            padding: 12px;
            border: 1px solid #b0b0b0;
            text-align: center;
        }

        th {
            background-color: #d0d4f5;
            color: #1e3a8a;
        }

        td {
            background-color: #ffffff;
        }

        @media (max-width: 600px) {
            .container {
                padding: 15px;
            }

            .foto {
                width: 150px;
                height: 150px;
            }

            table {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="container">

        <h1>Hillana Leticia Silva</h1>

        <img src="https://images.unsplash.com/photo-1610484826917-1f3ee9835be3?auto=format&fit=crop&w=300&q=80" alt="Imagem que representa Hillana" class="">

        <div>
            <a class="button-link" href="https://site.taglivros.com/">TAG Livros</a>
            <a class="button-link" href="https://g1.globo.com/podcast/o-assunto/noticia/2020/11/20/o-assunto-328-o-reconhecimento-da-negritude-no-brasil.ghtml">Reconhecimento da Negritude</a>
            <a class="button-link" href="https://open.spotify.com/show/1592iJQt0IlC5u5lKXrbyS">Bom Dia Obvious</a>
        </div>

        <p>Olá! Meu nome é Hillana, nasci em São Paulo e atualmente moro em Senhor do Bonfim, no interior da Bahia. Sou professora de Português, Literatura, Inglês, Robótica e Pensamento Computacional. Também sou estudante de Ciência da Computação no Instituto Federal Baiano (IF Baiano).</p>

        <p>Tenho 28 anos, sou casada e compartilho a vida com meu gatinho chamado Dante. Apaixonada por livros, sou uma leitora voraz e adoro viver novas experiências — especialmente quando envolvem viagens e descobertas culturais. Já atuei no centro estudantil do meu curso e participo ativamente da minha comunidade quilombola por meio da associação local. Levo comigo o compromisso com a educação, a tecnologia e a valorização das raízes culturais.</p>

        <h2>Hobbies</h2>
        <ul>
            <li>Leitura</li>
            <li>Escrita</li>
            <li>Viagens</li>
        </ul>

        <h2>Atividades de Lazer</h2>
        <ul>
            <li>Pilates</li>
            <li>Correr</li>
            <li>Cozinhar</li>
        </ul>

        <h2>Países que quero visitar</h2>
        <table>
            <tr>
                <th>País</th>
                <th>Cidade/Destino</th>
            </tr>
            <tr>
                <td>Inglaterra</td>
                <td>Londres</td>
            </tr>
            <tr>
                <td>França</td>
                <td>Paris</td>
            </tr>
            <tr>
                <td>Espanha</td>
                <td>Madrid ou Barcelona</td>
            </tr>
        </table>
    </div>
</body>
</html>
    <button id="btnMensagem" class="button-link">Clique para ver uma mensagem!</button>
        <p id="mensagem" style="text-align:center; font-weight:bold; color:#ff69b4; margin-top:10px;"></p>

    </div> <!-- fim container -->

    <script>
document.getElementById("btnMensagem").addEventListener("click", function() {
        document.getElementById("mensagem").textContent = "Você é capaz de realizar coisas incríveis! ✨";
      });
    </script>
