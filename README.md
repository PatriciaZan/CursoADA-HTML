# HTML - (Hypertext markup Language)

* Hipertexto.
Pode conter referências navegáveis para outros textos.
Essas referências são os **LINKS**.
Linguagem de marcação, que possui símbolos especias que indicans metainformações.
Referência a forma hierarquica, ordem e semântica.

**Marcação -> tags (elementos)**.
```
<div>
<p>
<button>
```

Os elementos podem conter **atributos** ex.
`<div>class="nomeClasse"</div>`.

`<html>`    // Conteudo HTML.
`<head>`   // Cabeçalho do Documento.
`<title>` // Titulo da página HTML.
`</head>`.

`<body>` // Corpo do documento.
`<p></p></br>` // Parágrafo com quebra de linha.
`</body>`.

`<a></a>`           // Link.
`<span></span>`    // Conteúdo genérico em linha.
`<table></table>` // Tabela.
`<ul></ul>`      // Lista não numerada.
`<ol></ol>`     // Lista numerada.
`<li></li>`    // Elemento da lista .
`<img/>`      // Imagem.

* Principais Tags.

`<h1>`      // Titulos.
`<p>`      // Paragrafo.
`<br>`    // Quebra linha.
`<hr>`   // Horisontal Row.
`<a>`   // Link -> target="_blank" (Utiliza nova Tab).
`<img>`// Imagem -> src="fonte" alt="descrição alternativa".

`<ul>`  // Lista não numerada.
`<ol>` // Lista numerada.
`<li>`// Lista .

`<span>` // Inline.
`<div>` // Block.

* Tags de Formatação de Texto.
`<b>`         // Negrito.
`<strong>`   // Forte, buscas.
`<i>`       // Italico.
`<em>`     // Emfase.
`<s>`     // Texto riscado.
`<mark>` // Texto marcado.
`<pre>` // Texto em codigo.

`<code>` // Texto em codigo inline.

`<blockquote>` // texto em citação.
`<sup>`       // 2 elavado a 10 etc... H2O.

## Elementos semanticos HTML5
`<header>`   // Cabeçalho.
`<main>`    // Conteudo principal.
`<footer>` // Rodapé.

`<nav>`    // Navegação.
`<aside>` // Barra lateral.

`<section>`        // Seções 'sobre' 'blog'.
`<article>`       // Artigo.
`<figure>`       // Incluir figuras.
`<figcaption>`  // Legenda da imagem figure.


## Criando a navBar

`<a ref="/">` //leva para a pagina raiz.

## Criando Tabelas

`<table>`   // Tag tabela.
`<thead>`  // Cabeçalho da Tabela.
`<tbody>` // Corpo da tabela.
`<tr>`   // Linha.
`<th>`  // Celula para o HEAD da Tabela -> negrito e centralização.
`<td>` // Celula para o BODY da Tabela.

Para mesclar duas linhas que possuam o mesmo dado, tal como datas/id/valor pode utilzia o atributo `rowspan="2"`. Porém deve apagar o primeiro elemento que deseja mesclar.

Para mesclar duas colunas utiliza `colspan="2"`. Assim irá ocupar duas colunas.

## Formulários

`<form>` // Cria o Formulário.
-> action="".
-> method="get". // POST

* Tags e atributos.
`<input type="">` // O input para o usuário.
-> type="Text" | password | email | date | time | number | file | url | color | range | checkbox | radio | reset | submit.
-> placeholder="Texto interno".
-> value="Valor interno inicial".
-> name="nome do input". JS identificará o campo.

`<label>` // É o enunciado do input.
-> for="id do input". 

`<textarea>` // Permite a digitação de texto.
-> name="".
-> id="".
-> cols="".
-> rows="".

`<select>` // Um drop menu com opções.
-> name="".
-> id="".

`<option>` // As opções contidas no <select>.
-> value="valor da seleção e envio ao formulário".
-> disable   // Torna opção não selecionavél.
-> selected // Começa selecionada.

## Class e Id

'class' // utiliza várias vezes.
'id'   // utiliza apenas uma vez.


