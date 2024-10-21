## Introdução ao HTML, CSS e JavaScript
1. HTML (HyperText Markup Language)
O HTML é a linguagem base para estruturar o conteúdo de páginas web. Ele define elementos como títulos, parágrafos, imagens, links e muito mais. Cada elemento é definido por "tags" que delimitam o conteúdo.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Exemplo HTML</title>
</head>
<body>
    <h1>Título Principal</h1>
    <p>Este é um parágrafo de texto em HTML.</p>
    <a href="https://exemplo.com">Este é um link</a>
</body>
</html>


2. CSS (Cascading Style Sheets)
O CSS é usado para estilizar o HTML. Ele permite aplicar cores, layouts e ajustes de design que melhoram a aparência visual das páginas web. O CSS pode ser aplicado de forma inline, interna (dentro do HTML) ou externa (em arquivos separados).

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

h1 {
    color: blue;
    text-align: center;
}

p {
    color: gray;
    font-size: 18px;
}


3. JavaScript
O JavaScript é a linguagem de programação que permite adicionar interatividade às páginas web. Com ele, é possível criar animações, validações de formulários, manipulação de elementos HTML em tempo real, entre outras funcionalidades.

function exibirMensagem() {
    alert('Olá, esta é uma mensagem interativa!');
}


Este código pode ser chamado no HTML usando um botão:

<button onclick="exibirMensagem()">Clique aqui</button>


Resumo
*HTML: Estrutura o conteúdo da página.
*CSS: Define o estilo e a apresentação da página.
*JavaScript: Adiciona interatividade e comportamento dinâmico.
