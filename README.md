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
            color: black; /* Texto padrão em preto */
            text-align: center; /* Alinha todo o texto ao centro */
            background-color: #ffffff; /* Fundo branco padrão */
        }

        /* Primeira seção: Fundo azul escuro */
        .section-darkblue {
            background-color: #2c3e50; /* Azul escuro */
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px; /* Adiciona algum espaço nas bordas */
        }

        /* Segunda seção: Fundo branco */
        .section-white {
            background-color: #ffffff; /* Branco */
            color: black;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px; /* Adiciona algum espaço nas bordas */
        }

        h1 {
            margin: 0;
            padding: 10px 0; /* Espaçamento entre os títulos */
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
    </div>

    <!-- Segunda seção: Fundo branco -->
    <div class="section-white">
        <h1 style="font-size: 80px; margin-top: 50px;">Semanas:</h1>

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
    
