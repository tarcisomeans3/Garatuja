# WEBDESIGN #

 ### FOCO DA DISCIPLINA ###

A disciplina de Web Design trabalha com linguagens de marcação como HTML, de estilização como CSS e de programação como JavaScript. Basicamente, o aluno aprende a montar um site, organizar corretamente os elementos e aplicar estilos para melhorar a aparência.

---

### OBJETIVO ###

O objetivo da disciplina é capacitar o aluno a criar sites bem estruturados e com um design próprio. A proposta é sair do básico e desenvolver páginas organizadas, funcionais e visualmente agradáveis.

---

### PRÉ-REQUISITOS ###

Não é necessário conhecimento prévio em programação, pois a disciplina é introdutória.

No entanto, é recomendável ter um ambiente preparado, como o uso do Visual Studio Code para escrever o código, o Google Chrome para testar e uma conta no GitHub para armazenar os projetos.

---

### HTML - HYPERTEXT MARKUP LANGUAGE ###

O HTML é uma linguagem de marcação utilizada para estruturar páginas web. Ele não realiza lógica de programação, mas organiza o conteúdo e define o significado de cada elemento.

Sua função é estruturar o site e garantir que o conteúdo seja exibido corretamente.

---

### TAGS HTML ###

O HTML utiliza tags, que funcionam como identificadores dos elementos da página. A tag precisa estar sempre dentro desses caracteres "<>".

Exemplos:

``<p> - cria um parágrafo``

``<h1> - cria um título``

``<a> - cria um link``

``<img> - exibe uma imagem``

Além de organizar o conteúdo, o HTML também contribui para a acessibilidade, pois define claramente o significado de cada elemento na página.

---

### FUNCIONAMENTO DAS TAGS ###

As tags normalmente possuem abertura e fechamento.

Exemplo:

``<p>Isso é um parágrafo</p>``

Você abre a tag, insere o conteúdo e depois fecha. Tudo que estiver dentro será interpretado como aquele tipo de elemento.

---

### FORMATAÇÃO DE TEXTO ###

É possível formatar textos utilizando tags.

Exemplo:

``<strong> text importante </strong> ``

``<em> text em destaque </em>``

A tag `<strong>` indica que o text é importante, enquanto ``<b>`` apenas altera o visual para negrito.

A tag ``<em>`` indica ênfase, enquanto ``<i>`` apenas altera o estilo visual.

Essas diferenças são importantes para acessibilidade e compreensão do conteúdo.

---

### ESTRUTURA BÁSICA DO HTML ###

Todo site segue uma estrutura padrão.

Exemplo:

```
<!DOCTYPE html>
<html lang=“pt-BR”>
<head>
<meta charset=“UTF-8”>
<title>Título da Página</title>
</head>
<body>
</body>
</html>
```

O ``<!DOCTYPE html>`` informa que o documento utiliza HTML5.
A tag ``<html>`` envolve todo o conteúdo da página.
O atributo lang define o idioma.

O ``<head>`` contém informações internas da página, como título e configurações.
O ``<body>`` contém todo o conteúdo visível ao usuário.

---

### ATRIBUTOS HTML ###

Os atributos fornecem informações adicionais às tags e controlam seu comportamento.

Exemplo de imagem:
``<img src=“imagem.png”>``

O atributo src indica o caminho da imagem.

Eles são essenciais para o funcionamento correto dos elementos.

---

### CSS - CASCADING STYLE SHEETS ###

O CSS é responsável pela aparência visual do site.

Com ele, é possível alterar cores, fontes, tamanhos, espaçamentos e organizar melhor os elementos na página.

Sem o CSS, o site apresenta apenas o estilo padrão do navegador.

---

### APLICANDO CSS ###

O CSS pode ser conectado ao HTML da seguinte forma:

Exemplo:
``<link rel=“stylesheet” href=“styles.css”>``

Esse comando permite aplicar estilos à página.

---

### SINTAXE DO CSS ###

O CSS funciona por meio de regras.

Exemplo:
``p { color: red; }``

O seletor define o elemento que será estilizado.
A propriedade indica o que será alterado.
O valor define como será a alteração.

Nesse caso, todos os parágrafos terão a cor vermelha.

---

### SELETORES CSS ###

Os seletores permitem escolher quais elementos serão modificados.

Seletor de tipo:
``p { }``
Seleciona todos os parágrafos.

Seletor de classe:
``.titulo { }``
Seleciona elementos com determinada classe.

Seletor de ID:
``#paragrafo1 { }``
Seleciona um elemento específico.

Seletor de atributo:
``a[href=”#”] { }``
Seleciona elementos com determinado atributo.

Pseudo-classes:
``p:first-child { }``
Seleciona elementos com base em posição ou estado.

---

### HIERARQUIA NO CSS ###

O CSS segue a estrutura do HTML.

Exemplo:
``main section p { }``

Esse seletor aplica estilos apenas aos parágrafos dentro de section, que está dentro de main.

Isso permite aplicar estilos de forma mais específica.

---

### TIPOS DE SELETORES ###

```
p : seleciona todos os elementos do tipo

.classe : seleciona por classe

#id : seleciona um elemento específico

[atributo] : seleciona por atributo

:pseudo : seleciona por estado ou posição
```

---

### IMPORTÂNCIA DO HTML E CSS ###

O HTML é responsável por estruturar o conteúdo da página.

O CSS define a aparência visual.

Juntos, formam a base essencial para o desenvolvimento de qualquer site.
