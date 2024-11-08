<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QR Code para Pagamento Pix</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #e0e5ec;
            perspective: 1000px;
        }
        .container {
            text-align: center;
            background-color: #ffffff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1), 0 6px 6px rgba(0, 0, 0, 0.1);
            transform: translateZ(30px);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .container:hover {
            transform: translateZ(50px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2), 0 8px 12px rgba(0, 0, 0, 0.15);
        }
        .container img {
            width: 250px;
            height: auto;
            margin-top: 15px;
            border: 5px solid #f0f0f0;
            border-radius: 10px;
        }
        .container p {
            font-size: 1.1em;
            color: #333;
            margin: 10px 0;
        }
        .container p:first-of-type {
            font-weight: 600;
            font-size: 1.3em;
            color: #444;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <p>Escaneie o QR Code abaixo para fazer o pagamento via Pix:</p>
        <img src="pix.jpeg" alt="QR Code de Pagamento Pix">
        <p>Obrigado pela preferência!</p>
    </div>
</body>
</html>

