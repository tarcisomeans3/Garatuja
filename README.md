##WEBDESIGN INTRODUÇÃO A MATERIA##

Foco da disciplina

A disciplina de Web Design aborda linguagens fundamentais para o desenvolvimento web, como HTML, CSS e JavaScript. Ao longo do curso, o aluno aprende a estruturar páginas, organizar conteúdos e aplicar estilos visuais, construindo sites funcionais e bem apresentados.


Objetivo

O objetivo é capacitar o aluno a criar sites bem estruturados, organizados e com identidade visual própria. A proposta é sair do nível básico e desenvolver páginas que funcionem corretamente, com um design limpo e eficiente.


Pré-requisitos

Não é necessário conhecimento prévio em programação, pois a disciplina é introdutória.

No entanto, é recomendável possuir um ambiente básico de desenvolvimento, como um editor de código (ex: Visual Studio Code), um navegador (ex: Google Chrome) e uma conta no GitHub para armazenar os projetos.


HTML – HyperText Markup Language

O HTML é uma linguagem de marcação utilizada para estruturar o conteúdo de páginas web. Ele não realiza lógica de programação, mas organiza os elementos da página e define o significado de cada parte.

Além disso, o uso correto do HTML contribui para acessibilidade e melhor interpretação do conteúdo pelos navegadores.


Tags HTML

O HTML utiliza tags, que funcionam como identificadores dos elementos da página.

Exemplos:
<p> → define um parágrafo
<h1> → define um título
<a> → cria um link
<img> → exibe uma imagem


Funcionamento das tags

A maioria das tags possui abertura e fechamento.

Exemplo:
<p>Isso é um parágrafo</p>

Texto:
A tag <p> define um parágrafo. Todo o conteúdo entre a abertura e o fechamento será exibido como texto na página.


Semântica e formatação

Algumas tags possuem significado semântico, indicando a importância do conteúdo.

Exemplo:
<strong>texto importante</strong>
<em>texto em destaque</em>

Texto:
A tag <strong> indica que o conteúdo é importante.
A tag <em> indica ênfase no texto.

Já as tags <b> e <i> apenas alteram o visual, sem acrescentar significado.


Estrutura básica do HTML

Exemplo:
<!DOCTYPE html>
<html lang=“pt-BR”>
<head>
<meta charset=“UTF-8”>
<title>Título da Página</title>
</head>
<body>
</body>
</html>

Texto:
Essa é a estrutura padrão de um documento HTML.
A declaração <!DOCTYPE html> define o uso do HTML5.
A tag <html> envolve todo o conteúdo.
O <head> contém informações da página que não são exibidas.
O <body> contém tudo o que será visível ao usuário.


Atributos HTML

Os atributos fornecem informações adicionais às tags e controlam seu comportamento.

Exemplo de link:
<a href=“https://www.google.com”>Visite o Google</a>

Texto:
A tag <a> cria um link.
O atributo href define o destino do link.


Exemplo de imagem:
<img src=“imagem.png”>

Texto:
A tag <img> exibe uma imagem.
O atributo src indica o caminho do arquivo.


CSS – Cascading Style Sheets

O CSS é responsável pela aparência visual do site, permitindo alterar cores, fontes, tamanhos, espaçamentos e organização dos elementos na tela.

Sem o CSS, a página utiliza apenas o estilo padrão do navegador.


Aplicando CSS

Exemplo:
<link rel=“stylesheet” href=“styles.css”>

Texto:
Esse comando conecta um arquivo CSS ao HTML, permitindo aplicar estilos à página.


Sintaxe do CSS

Exemplo:
p { color: red; }

Texto:
O seletor define quais elementos serão estilizados.
A propriedade indica o que será alterado, e o valor define como será a alteração.

Seletores CSS

Os seletores permitem aplicar estilos de forma específica.

Tipos principais:
p → todos os parágrafos
.classe → elementos com determinada classe
#id → elemento específico
[atributo] → elementos com determinado atributo
:pseudo → estados ou posições

Hierarquia no CSS

Exemplo:
main section p { }

Texto:
Esse seletor aplica estilos apenas aos parágrafos que estão dentro de uma section, que por sua vez está dentro de main.

Importância do HTML e CSS

O HTML é responsável pela estrutura da página, enquanto o CSS define sua aparência.

Juntos, formam a base essencial para o desenvolvimento de qualquer site.