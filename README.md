
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Porta Lógica OR Interativa</title>
    <style>
        /* Estilos para a porta lógica OR */
        .or-gate {
            width: 120px;
            height: 80px;
            background-color: #3498db;
            border: 2px solid #2980b9;
            border-radius: 10px;
            position: relative;
            cursor: pointer; /* Adiciona uma mãozinha ao passar o mouse para indicar que é clicável */
            transition: background-color 0.3s; /* Transição suave da cor de fundo */
        }

        /* Texto dentro da porta lógica */
        .or-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #fff;
        }

        /* Adiciona um efeito de sombra quando a porta está ativa */
        .active {
            box-shadow: 0 0 10px rgba(0, 255, 0, 0.7);
        }
    </style>
</head>
<body>
    <!-- A porta lógica OR -->
    <div class="or-gate" onclick="toggleGate(this)">
        <div class="or-text">OR</div>
    </div>

    <script>
        // Função para alternar entre os estados ativo e inativo da porta
        function toggleGate(element) {
            element.classList.toggle('active');
        }
    </script>
</body>
</html>

