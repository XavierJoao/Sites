<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sites</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #333;
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
    }
    .link-btn {
      display: inline-flex;
      align-items: center;
      padding: 10px 20px;
      background-color: #007bff;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }
    .link-btn:hover {
      background-color: #0056b3;
    }
    .link-btn i {
      margin-right: 8px;
    }
  </style>
</head>
<body>

  <h1>Sites</h1>

  <div class="container">
    <a href="https://colegiofeliz.com.br/" class="link-btn">
      <i class="fas fa-globe"></i> Colégio Feliz
    </a>
    <a href="https://jogo-ochre-three-42.vercel.app/" class="link-btn">
      <i class="fas fa-globe"></i> Jogo do Número Secreto
    </a>
    <a href="https://amigo-secreto-fawn-eight.vercel.app/" class="link-btn">
      <i class="fas fa-globe"></i> Sorteador para Amigo Secreto
    </a>
  </div>

  <!-- Link para o FontAwesome -->
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
  
</body>
</html>
