<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>G SO 25 - Android Fake</title>
<style>
  body {
    margin: 0;
    font-family: "Roboto", sans-serif;
    background: #121212;
    color: #eee;
    display: flex;
    flex-direction: column;
    height: 100vh;
  }
  header {
    background: #1f1f1f;
    padding: 1rem;
    text-align: center;
    font-weight: bold;
    font-size: 1.2rem;
  }
  main {
    flex: 1;
    display: flex;
    flex-wrap: wrap;
    padding: 1rem;
    gap: 1rem;
    justify-content: center;
    align-content: flex-start;
  }
  .app {
    background: #2a2a2a;
    width: 90px;
    height: 90px;
    border-radius: 18px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    user-select: none;
    transition: background 0.2s;
  }
  .app:hover {
    background: #3a3a3a;
  }
  .app-icon {
    font-size: 2.5rem;
    margin-bottom: 0.3rem;
  }
  .app-name {
    font-size: 0.8rem;
  }
  footer {
    background: #1f1f1f;
    padding: 0.5rem;
    text-align: center;
    font-size: 0.75rem;
  }
</style>
</head>
<body>
<header>G SO 25 - Android Fake</header>
<main>
  <div class="app" onclick="alert('Abrindo Configurações...')">
    <div class="app-icon">⚙️</div>
    <div class="app-name">Config</div>
  </div>
  <div class="app" onclick="alert('Abrindo Música...')">
    <div class="app-icon">🎵</div>
    <div class="app-name">Música</div>
  </div>
  <div class="app" onclick="alert('Abrindo Câmera...')">
    <div class="app-icon">📸</div>
    <div class="app-name">Câmera</div>
  </div>
  <div class="app" onclick="alert('Abrindo Mensagens...')">
    <div class="app-icon">💬</div>
    <div class="app-name">Mensagens</div>
  </div>
</main>
<footer>feito por miguel | 2025</footer>
</body>
</html>
