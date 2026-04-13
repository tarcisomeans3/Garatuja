Agora sim, peguei teu texto e converti pra Markdown limpinho pra copiar direto 👇

⸻

Foco da disciplina

A disciplina de web design trabalha com linguagens de marcação como (html), de estilização (css) e de programação (java script). Basicamente, você vai aprender a montar um site, organizar tudo direito e depois deixar ele bonito.

⸻

Objetivo

O objetivo dessa disciplina é fazer o aluno conseguir criar sites bem estruturados e com um design próprio. A ideia é sair do básico e já conseguir montar páginas organizadas, que funcionam e que não fiquem uma bagunça.

⸻

Pré-requisitos

Não precisa saber programar antes, porque a disciplina é introdutória.

Mas é bom já ter um ambiente pronto, tipo usar o Visual Studio Code pra escrever o código, o Google Chrome pra testar e ter uma conta no GitHub pra salvar os projetos.

⸻

HTML - HyperText Markup Language

Quando você estuda html, você não tá aprendendo programação de verdade, e sim uma linguagem de marcação.

Isso quer dizer que o html não faz lógica nem “pensa”, ele só organiza o site.

Ele é o responsável por estruturar tudo e deixar o conteúdo organizado pra funcionar direito.

⸻

O html usa tags, que são tipo etiquetas que você coloca nas coisas.

Essas tags servem pra dizer o que cada parte do site é, e também podem ter funções tipo ação, classe e outras coisas.

Exemplos:
	•	<p> → cria um parágrafo
	•	<h1> → cria um título
	•	<a> → cria link
	•	<img> → coloca imagem

⸻

Além de organizar, o html também ajuda na acessibilidade, porque deixa claro o que cada coisa significa dentro da página.

⸻

Funcionamento das tags

As tags normalmente têm abertura e fechamento.

Ex:

<p>Isso é um parágrafo</p>

Você abre a tag, coloca o conteúdo dentro e depois fecha. Tudo que estiver dentro vira aquele tipo de elemento.

⸻

Exemplo de formatação

Dá pra formatar texto usando tags também.

Ex:

<strong>texto importante</strong>
<em>texto em destaque</em>

A <strong> mostra que o texto é importante, enquanto <b> só deixa em negrito.

<em>texto</em>
<i>texto</i>

A <em> indica ênfase, enquanto <i> só muda o visual.

⸻

Isso é importante principalmente pra acessibilidade e pra entender melhor o conteúdo.

⸻

Estrutura básica do HTML

Todo site segue uma estrutura padrão:

<!DOCTYPE html>
<html lang="pt-BR">
<head>
   <meta charset="UTF-8">
   <title>Título da Página</title>
</head>
<body>
</body>
</html>

O <!DOCTYPE html> fala pro navegador que é HTML5.

A <html> é onde tudo fica dentro.

O lang="pt-BR" define o idioma.

⸻

O <head> guarda informações da página, tipo título, css e scripts. Isso não aparece no site.

⸻

O <body> é onde fica tudo que o usuário vê, tipo texto, imagem, link e etc.

⸻

Atributos HTML

Os atributos servem pra dar informações extras pras tags.

Eles ficam na parte de abertura da tag.

⸻

Exemplo de link

<a href="https://www.google.com">Visite o Google</a>

O href diz pra onde o link vai.

⸻

Exemplo de imagem

<img src="imagem.png">

O src diz de onde vem a imagem.

⸻

Eles são importantes porque controlam o comportamento dos elementos.

⸻

CSS - Cascading Style Sheets

O css é a parte que deixa o site bonito.

Com ele você muda cor, fonte, tamanho, espaçamento e organiza melhor tudo na tela.

⸻

Sem css, o site fica com aquele estilo padrão feio do navegador.

⸻

Aplicando CSS

Você conecta o css no html usando:

<link rel="stylesheet" href="styles.css">


⸻

Sintaxe do CSS

O css funciona com regras:

seletor {
  propriedade: valor;
}

O seletor escolhe o que vai mudar.

A propriedade diz o que vai mudar.

O valor diz como vai ficar.

⸻

Exemplo

p {
  color: red;
}

Todos os parágrafos ficam vermelhos.

⸻

Seletores CSS

Os seletores servem pra escolher exatamente o que você quer mudar.

⸻

Seletor de tipo:

p {
}

Pega todos os parágrafos.

⸻

Seletor de classe:

.titulo {
}

Pega quem tiver aquela classe.

⸻

Seletor de ID:

#paragrafo1 {
}

Pega um elemento específico.

⸻

Seletor de atributo:

a[href="#"] {
}

Pega elementos com aquele atributo.

⸻

Pseudo-classes

p:first-child {
}

Pega elementos pela posição.

⸻

Hierarquia no CSS

O css também segue a estrutura do html.

main section p {
}

Isso pega parágrafos dentro de section dentro de main.

⸻

Isso ajuda a aplicar estilos de forma mais específica.

⸻

Tipos de seletores (resumo)
	•	p → todos
	•	.classe → por classe
	•	#id → específico
	•	[atributo] → por atributo
	•	:pseudo → posição/estado

⸻

Importância do HTML e CSS

O html organiza e estrutura o site.

O css cuida da aparência.

Os dois juntos são a base pra criar qualquer página web.

⸻

Agora tá 100% pronto pra colar, sem bug, sem gambiarra 🙏💀