<script>
    let message = "Bem-vindo à nossa página de introdução, Aqui iremos te mostrar os melhores cartões para se ter!";

  </script>
  
  <style>
    .nav-link {
      text-decoration: none;
      color: #008cba;
      font-weight: bold;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }
  
    .nav-link:hover {
      background-color: #005f75;
      color: #ffffff;
    }
  
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
  
    .container {
      text-align: center;
      background: white;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      border-radius: 8px;
    }
  
    h1 {
      color: #333;
    }
  
    p {
      color: #555;
    }
  
    .button {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #008cba;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  
    .button:hover {
      background-color: #005f75;
    }
  </style>
  
  <main>
    <div class="container">
      <h1>{message}</h1>
      <p>Estou feliz de te ver por aqui. Explore nosso site e descubra tudo o que temos a oferecer!</p>
      <button class="button" on:click={() => alert('Seja bem-vindo!')}>Clique aqui</button>
      <nav>
        <a class="nav-link" href="/sobre">Cartões</a>
        <a class="nav-link" href="/cartao">Bandeiras</a>
      </nav>
    </div>
  </main>
  