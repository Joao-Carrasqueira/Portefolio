<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portefólios</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        /* Definições básicas */
        body {
            margin: 0;
            font-family: "roboto", "Merriweather", sans-serif
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Primeira seção: Fundo azul escuro até a primeira imagem */
        .section-darkblue {
            background-color: #425664; /* Azul escuro */
            color: #f6f4f2;
            padding-bottom: 20px; /* Para garantir que o fundo azul cubra até a imagem */
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            flex-direction: column;
        }

        h1 {
            margin: 0;
        }

        /* Estilos para a imagem */
        .image-container img {
            max-width: 25%;
            height: auto;
            display: block;
            margin: auto;
        }

        /* Estilo para o título "Semanas" */
        .semanas-text {
            font-size: 80px;
            color: black;
            margin-top: 30px; /* Espaço entre a imagem e o texto "Semanas" */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* Para centralizar verticalmente */
            text-align: center;
        }

        /* Estilo para o conteúdo após o fundo azul */
        .section-white {
            background-color: white;
            padding: 20px;
        }

        .semana-container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .semana-container .semana {
            text-align: center;
            width: 30%; /* Para garantir que as semanas fiquem em linhas de 3 */
            margin: 10px;
        }

        .semana-container .semana img {
            width: 100%;
            max-width: 150px;
            display: block;
            margin: 5px auto;
        }
    </style>
</head>
<body>
    <!-- Primeira seção: Fundo azul escuro -->
    <div class="section-darkblue">
        <h1 style="font-size: 230px; margin-bottom: 0;">Portefólios</h1>
        <hr style="margin: 0;">
        <h1 style="font-size: 37px; margin-top: 20px;">Da disciplina de Aplicações Informáticas</h1>

        <div class="image-container">
            <img src="https://github.com/user-attachments/assets/58a620b8-7f86-488f-aab6-ae7441fed7de" alt="imagem">
        </div>
    </div>

    <!-- Texto "Semanas" centralizado -->
    <h1 class="semanas-text">Semanas:</h1>

    <!-- Segunda seção: Fundo branco -->
    <div class="section-white">
        <div class="semana-container">
            <!-- Primeira linha com 6 semanas -->
            <div class="semana">
                <a href="Semanas/semana1.html">
                    <img src="https://github.com/user-attachments/assets/db744e90-cdae-4769-98e6-b359f5cc4cea" alt="semana-1">
                </a>
                <p style="margin: 0;">16-20 de Setembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana2.html">
                    <img src="https://github.com/user-attachments/assets/c856b8b9-6722-4539-a944-d8e7ff1dfb65" alt="semana-2">
                </a>
                <p style="margin: 0;">23-27 de Setembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana3.html">
                    <img src="https://github.com/user-attachments/assets/ef4769ac-1a65-4584-a871-71b887daa996" alt="semana-3">
                </a>
                <p style="margin: 0;">30-04 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana4.html">
                    <img src="https://github.com/user-attachments/assets/0dbda99b-c3a2-4271-b121-f6b804405b48" alt="semana-4">
                </a>
                <p style="margin: 0;">07-11 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana5.html">
                    <img src="https://github.com/user-attachments/assets/9b993379-9f34-44d5-b9d8-0fa151ec5b58" alt="semana-5">
                </a>
                <p style="margin: 0;">14-18 de Outubro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana6.html">
                    <img src="https://github.com/user-attachments/assets/2f165e7d-1b71-442d-ad9e-23928aa68cf6" alt="semana-6">
                </a>
                <p style="margin: 0;">21-25 de Outubro</p>
            </div>
        </div>

        <div class="semana-container">
            <!-- Segunda linha com as próximas 6 semanas -->
            <div class="semana">
                <a href="Semanas/semana7.html">
                    <img src="https://github.com/user-attachments/assets/7b7b20d1-9e3e-4b2e-9265-cf9cc5d84196" alt="semana-7">
                </a>
                <p style="margin: 0;">28-01 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana8.html">
                    <img src="https://github.com/user-attachments/assets/b7c4cee0-2b8d-4100-90ee-8e88025be94b" alt="semana-8">
                </a>
                <p style="margin: 0;">04-08 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana9.html">
                    <img src="https://github.com/user-attachments/assets/a0d8355f-5296-4095-af0e-9f3127956120" alt="semana-9">
                </a>
                <p style="margin: 0;">11-15 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana10.html">
                    <img src="https://github.com/user-attachments/assets/eeeb1778-e1c8-4534-a74a-4871c0743b9f" alt="semana-10">
                </a>
                <p style="margin: 0;">18-22 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana11.html">
                    <img src="https://github.com/user-attachments/assets/93ff1d02-2974-45dc-83c4-7c847f76a8a3" alt="semana-11">
                </a>
                <p style="margin: 0;">25-29 de Novembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana12.html">
                    <img src="https://github.com/user-attachments/assets/d876a77d-7d3c-4a41-a9cd-c568b8d5249a" alt="semana-12">
                </a>
                <p style="margin: 0;">02-06 de Dezembro</p>
            </div>
        </div>

        <div class="semana-container">
            <!-- Terceira linha com 6 semanas adicionais -->
            <div class="semana">
                <a href="Semanas/semana13.html">
                    <img src="https://github.com/user-attachments/assets/57f90e58-e3cb-495d-a1c3-7d43d160d8e5" alt="semana-13">
                </a>
                <p style="margin: 0;">09-13 de Dezembro</p>
            </div>
            <div class="semana">
                <a href="Semanas/semana14.html">
                    <img src="https://github.com/user-attachments/assets/8558f04c-7aef-4923-9149-0443de76120a" alt="semana-14">
                </a>
                <p style="margin: 0;">06-10 de Janeiro</p>
            </div>
           
    <div class="semana-container">
        <div class="semana">
            <a href="Semanas/semana15.html">
                <img src="https://github.com/user-attachments/assets/ade4c663-8ab6-4a50-af52-ccc36552c07d" alt="semana-15">
            </a>
            <p>13-17 de Janeiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana16.html">
                <img src="https://github.com/user-attachments/assets/3b162a23-3924-42ea-9c6a-6b7cbefd048e" alt="semana-16">
            </a>
            <p>20-24 de Janeiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana17.html">
                <img src="https://github.com/user-attachments/assets/0f17af60-26ea-4d1e-b880-336a55d83165" alt="semana-17">
            </a>
            <p>27-31 de Janeiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana18.html">
                <img src="https://github.com/user-attachments/assets/7e8977be-ef02-4c32-b118-b94140ce9dcf" alt="semana-18">
            </a>
            <p>03-07 de Fevereiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana19.html">
                <img src="https://github.com/user-attachments/assets/fe5921e7-c428-4985-b9b3-0cf3221fb82f" alt="semana-19">
            </a>
            <p>10-14 de Fevereiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana20.html">
                <img src="https://github.com/user-attachments/assets/17e973b9-ec09-4316-95ad-7be2297100f7" alt="semana-20">
            </a>
            <p>17-21 de Fevereiro</p>
        </div>
    </div>

    <div class="semana-container">
        <div class="semana">
            <a href="Semanas/semana21.html">
                <img src="https://github.com/user-attachments/assets/17fa98b6-bba8-47b4-b8b9-b719a5c0c567" alt="semana-21">
            </a>
            <p>24-28 de Fevereiro</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana22.html">
                <img src="https://github.com/user-attachments/assets/706ee17e-e423-4272-916f-2948ec50964e" alt="semana-22">
            </a>
            <p>03-07 de Março</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana23.html">
                <img src="https://github.com/user-attachments/assets/7ba04507-3687-4efe-bc1a-af128e3d62dd" alt="semana-23">
            </a>
            <p>10-14 de Março</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana24.html">
                <img src="https://github.com/user-attachments/assets/41dc49e4-61be-424b-b68f-e70d0c1834c7" alt="semana-24">
            </a>
            <p>17-21 de Março</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana25.html">
                <img src="https://github.com/user-attachments/assets/74f91fd2-47b1-4ffe-9a21-f0bcf5a84e13" alt="semana-25">
            </a>
            <p>24-28 de Março</p>
        </div>
        <div class="semana">
            <a href="Semanas/semana26.html">
                <img src="https://github.com/user-attachments/assets/7cf841fd-20bc-4734-ac95-4f7bebf8bd46" alt="semana-26">
            </a>
            <p>31-4 de Abril</p>
        </div>
    </div>

                   
