<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portefólios</title>
    <style>
        /* Inicializando o fundo como azul escuro */
        body {
            background-color: #2c3e50; /* Azul escuro */
            transition: background-color 0.3s ease; /* Transição suave para a mudança de fundo */
        }

        /* Estilos adicionais */
h1 {
    text-align: center;
    margin-bottom: 0;
        }

        /* Estilo para a imagem */
.image-container img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: auto;
        }

        /* Estilo para o conteúdo */
.content {
    text-align: center;
        }

.semana-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
        }

.semana-container .semana {
    text-align: center;
        }

/* Mudança de fundo para branco após o scroll */
body.bg-white {
    background-color: #ffffff; /* Fundo branco */
        }
    </style>
</head>
<body>

  <h1 style="font-size: 250px; margin-bottom: 0;">Portefólios</h1>
    <hr style="margin: 0;">
    <h1 style="font-size: 37px; margin-top: 20px;">Da disciplina de Aplicações Informáticas</h1>

 <div class="image-container">
        <img src="https://github.com/user-attachments/assets/d5cd1c99-8940-4f29-a446-7e3f8a1ae1a6" alt="imagem">
     </div>

<h1 style="font-size: 100px;"></h1>

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
        <!-- Adicione as outras semanas aqui -->
    </div>

<h1 style="font-size: 150px;"></h1>

<h1 style="text-align:right; fonr-size: 10px;">Realizados por: Manuel Alberto, nº28, 12º5</h1>

 <script>
        // Evento de scroll para alterar o fundo da página
        window.addEventListener('scroll', function() {
            // Verifica se a posição do scroll passou de 50px
            if (window.scrollY > 50) {
                document.body.style.backgroundColor = "#ffffff"; // Altera para fundo branco
            } else {
                document.body.style.backgroundColor = "#2c3e50"; // Restaura o fundo azul escuro
            }
        });
    </script>

</body>
</html>


