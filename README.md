<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portefólios</title>
    <style>
        /* Definições básicas */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            height: 100vh;
            display: flex;
            flex-direction: column;
            background-color: #ffffff; /* Fundo branco padrão para o corpo */
            color: black; /* Texto padrão em preto */
            text-align: center; /* Alinha todo o texto ao centro */
        }

        /* Primeira seção: Fundo azul escuro */
        .section-darkblue {
            background-color: #2c3e50; /* Azul escuro */
            color: white;
            flex: 1; /* Primeira seção ocupa 1/3 da altura total */
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        /* Segunda seção: Fundo branco */
        .section-white {
            background-color: #ffffff; /* Branco */
            color: black;
            flex: 1; /* Segunda seção ocupa 1/3 da altura total */
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        .image-container img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: auto;
        }

        /* Alinhamento das imagens na seção de semanas */
        .semana-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 10px; /* Espaçamento entre as imagens */
        }

        .semana-container .semana {
            text-align: center;
        }

        .semana-container img {
            max-width: 150px;
            margin: 5px;
            display: block;
        }

        p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Primeira seção: Fundo azul escuro -->
    <div class="section-darkblue">
        <h1 style="font-size: 250px;">Portefólios</h1>
        <hr style="margin: 0;">
        <h1 style="font-size: 37px; margin-top: 20px;">Da disciplina de Aplicações Informáticas</h1>

        <div class="image-container">
            <img src="https://github.com/user-attachments/assets/d5cd1c99-8940-4f29-a446-7e3f8a1ae1a6" alt="imagem">
        </div>

        <h1 style="font-size: 100px;"></h1>

        <h1 style="font-size: 80px; margin-top: 50px;">Semanas:</h1>
    </div>

    <!-- Segunda seção: Fundo branco -->
    <div class="section-white">
        <div class="semana-container">
            <div class="semana">
                <a href="Semanas/semana1.html">
                    <img src="https://github.com/user-attachments/assets/db744e90-cdae-4769-98e6-b359f5cc4cea" alt="semana-1">
                </a>
                <p>16-20 de Setembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana2.html">
                    <img src="https://github.com/user-attachments/assets/c856b8b9-6722-4539-a944-d8e7ff1dfb65" alt="semana-2">
                </a>
                <p>23-27 de Setembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana3.html">
                    <img src="https://github.com/user-attachments/assets/ef4769ac-1a65-4584-a871-71b887daa996" alt="semana-3">
                </a>
                <p>30-04 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana4.html">
                    <img src="https://github.com/user-attachments/assets/0dbda99b-c3a2-4271-b121-f6b804405b48" alt="semana-4">
                </a>
                <p>07-11 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana5.html">
                    <img src="https://github.com/user-attachments/assets/9b993379-9f34-44d5-b9d8-0fa151ec5b58" alt="semana-5">
                </a>
                <p>14-18 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana6.html">
                    <img src="https://github.com/user-attachments/assets/2f165e7d-1b71-442d-ad9e-23928aa68cf6" alt="semana-6">
                </a>
                <p>21-25 de Outubro</p>
            </div>
        </div>

        <h1 style="font-size: 70px;"></h1>

        <div class="semana-container">
            <div class="semana">
                <a href="Semanas/semana7.html">
                    <img src="https://github.com/user-attachments/assets/7b7b20d1-9e3e-4b2e-9265-cf9cc5d84196" alt="semana-7">
                </a>
                <p>28-01 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana8.html">
                    <img src="https://github.com/user-attachments/assets/b7c4cee0-2b8d-4100-90ee-8e88025be94b" alt="semana-8">
                </a>
                <p>04-08 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana9.html">
                    <img src="https://github.com/user-attachments/assets/a0d8355f-5296-4095-af0e-9f3127956120" alt="semana-9">
                </a>
                <p>11-15 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana10.html">
                    <img src="https://github.com/user-attachments/assets/eeeb1778-e1c8-4534-a74a-4871c0743b9f" alt="semana-10">
                </a>
                <p>18-22 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana11.html">
                    <img src="https://github.com/user-attachments/assets/93ff1d02-2974-45dc-83c4-7c847f76a8a3" alt="semana-11">
                </a>
                <p>25-29 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana12.html">
                    <img src="https://github.com/user-attachments/assets/d876a77d-7d3c-4a41-a9cd-c568b8d5249a" alt="semana-12">
                </a>
                <p>02-06 de Dezembro</p>
            </div>
        </div>

    </div>
</body>
</html>
