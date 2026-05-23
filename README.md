<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Base HTML</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
    }

    header {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
      font-size: 24px;
      border-bottom: 2px solid #333;
    }

    main {
      padding: 20px;
    }

    .card {
      background: #222;
      padding: 20px;
      border-radius: 12px;
      margin-top: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
    }

    button {
      background: #00aaff;
      border: none;
      padding: 10px 18px;
      border-radius: 8px;
      color: white;
      cursor: pointer;
      font-size: 16px;
      transition: 0.2s;
    }

    button:hover {
      background: #0088cc;
      transform: scale(1.05);
    }
  </style>
</head>

<body>

  <header>
    🚀 Minha Página
  </header>

  <main>
    <h1>Olá, mundo!</h1>

    <div class="card">
      <p>Essa é uma base HTML simples para começar qualquer projeto.</p>

      <button onclick="mostrarMensagem()">
        Clique aqui
      </button>
    </div>
  </main>

  <script>
    function mostrarMensagem() {
      alert("✨ Você clicou no botão!");
    }
  </script>

</body>
</html>
