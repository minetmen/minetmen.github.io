# minetmen.github.io
Teste Cemig web
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Redirecionamento de URL</title>
</head>
<body>
  <h1>Redirecionamento de URL</h1>

  <p>Este exemplo irá redirecionar o usuário para as URL <strong>https://www.globo.com/</strong> e <strong>https://www.google.com/</strong>.</p>

  <script>
    // Define um cookie com o valor da URL atual
    let currentUrl = window.location.href;
    setcookie('current_url', currentUrl, time() + (30 * 24 * 3600));

    // Redireciona o usuário para a URL https://www.globo.com/
    setTimeout(() => {
      window.location.href = "https://www.globo.com/";
    }, 3000);

    // Redireciona o usuário para a URL https://www.google.com/
    setTimeout(() => {
      window.location.href = "https://www.google.com/";
    }, 6000);
  </script>
</body>
</html>
