<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil GitHub - Killian</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f0f0f;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      flex-direction: column;
      text-align: center;
    }

    .container {
      animation: fadeIn 2s ease-in-out;
      max-width: 600px;
      padding: 20px;
      border: 2px solid #ffdd00;
      border-radius: 20px;
      background-color: #1a1a1a;
      box-shadow: 0 0 15px #ffdd00aa;
    }

    h1 {
      color: #ffdd00;
      margin-bottom: 10px;
    }

    .btn {
      margin: 10px;
      padding: 10px 20px;
      border: none;
      border-radius: 12px;
      background-color: #ffdd00;
      color: #0f0f0f;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .btn:hover {
      background-color: #e6c800;
    }

    #email {
      margin-top: 10px;
      font-weight: bold;
      display: none;
      animation: fadeIn 1s forwards;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li::before {
      content: "⚡ ";
      color: #ffdd00;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>🚀 Bienvenue sur mon GitHub !</h1>
    <p>👋 Moi c’est <strong>@GithubofKillian</strong></p>
    <p>🔐 Futur ingénieur en système d'information, option cyber</p>
    <p>💡 Passionné par la sécurité informatique et le développement</p>

    <h2>🛠️ Technologies & Compétences</h2>
    <ul>
      <li>JavaScript, Python, SQL</li>
      <li>React.js</li>
      <li>Sécurité Web, Cryptographie</li>
      <li>Requêtes REST</li>
    </ul>

    <h2>🌱 En apprentissage</h2>
    <p>🤖 Automatisation et scripts en Python</p>

    <h2>🎯 À quoi s’attendre ici ?</h2>
    <p>🚧 Projets, expérimentations et partage de connaissances</p>

    <div>
      <button class="btn" onclick="showEmail()">📫 Contact</button>
      <button class="btn" onclick="window.open('https://www.root-me.org/Jonneaux?lang=en#d2b782cfd22c3598f427f99aac0a81ef','_blank')">🧠 Root Me</button>
    </div>

    <div id="email">💌 killian.jonneaux@gmail.com</div>

    <p style="margin-top: 20px;">⚡ Fun fact : Toujours à la recherche d’un petit CTF à réaliser ! 😄</p>
  </div>

  <script>
    function showEmail() {
      document.getElementById("email").style.display = "block";
    }
  </script>

</body>
</html>
