<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sistema de Coleta de Leite</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="login-container">
    <h1>Sistema de Coleta de Leite</h1>

    <div id="loginForm">
      <h2>Login</h2>
      <input type="text" id="loginUser" placeholder="Usuário">
      <input type="password" id="loginPass" placeholder="Senha">
      <button onclick="login()">Entrar</button>
      <p>Não tem conta? <a href="#" onclick="showRegister()">Cadastrar</a></p>
    </div>
    <div id="registerForm" style="display:none;">
      <h2>Cadastrar</h2>
      <input type="text" id="regUser" placeholder="Usuário">
      <input type="password" id="regPass" placeholder="Senha">
      <select id="regType">
        <option value="produtor">Produtor</option>
        <option value="coletor">Coletor</option>
      </select>
      <button onclick="register()">Cadastrar</button>
      <p>Já tem conta? <a href="#" onclick="showLogin()">Fazer login</a></p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html


