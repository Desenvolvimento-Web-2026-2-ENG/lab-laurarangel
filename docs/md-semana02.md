<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Exemplo de págima ">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de HTML </title>
</head>
<body>
    <header>
        <div class="titulo">Área de Contato do Cliente</div>
        <nav>
            <a href="#">Ajuda</a> | <a href="#">Sair</a>
        </nav>
   </header>

    <main>
        <h1> Envie sua mensagem para a nossa equipe de suporte backend</h1>
        
        <form action="/enviar" method="POST">
             <label for="nome">Nome:</label>
             <input type="text" id="nome" name="nome" required minlength="3"><br><br>
             <label for="email">Email:</label>
             <input type="email" id="email" name="email" required minlength="5"><br><br>
             <label for="celular">Telefone Celular:</label>
             <input type="text" id="celular" name="celular" pattern="[0-9]{11}" required><br><br>
             <label for="msg">Mensagem:</label>
             <textarea id="msg" name="msg"></textarea><br><br>

            <input type="button" value="Disparar Dados">
        </form>
   </main>

   <footer>
        Suporte Tech 2026
    </footer>
</body>
</html>
