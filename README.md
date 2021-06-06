**Markdown é uma sintaxe de extensão .md que é suportado por repositórios como GitHub, Bitbucket e GitLab. Ele é basicamente um arquivo de texto que pode ser escrito a partir de tags HTML ou Markdown.** Pessoalmente costumo misturar os dois pois usando HTML consigo centralizar os elementos. 

## Índice
   - [1) Títulos](#1-títulos)
   - [2) Linhas em Branco](#2-linhas-em-branco)
   - [3) Negrito](#3-negrito)
   - [4) Itálico](#4-itálico)
   - [5) Combinação de marcações](#5-combinação-de-marcações)
   - [6) Listas](#6-listas)
   - [7) Marcadores especiais](#7-marcadores-especiais)
   - [8) Citações(Quotes)](#8-citações-quotes)
   - [9) Links](#9-links)
   - [10) Código (Code Highlight)](#10-código-code-highlight)
   - [11) Imagens e Gifs](#11-imagens-e-gifs)
   - [12) Tabelas](#12-tabelas)
   - [13) Comentar linhas do markdown](#13-comentar-linhas-do-markdown)
  - [Fontes](#fontes)
  - [Ferramentas para Markdown](#ferramentas-para-markdown)
  - [Mais sobre Markdown](#mais-sobre-markdown)


### 1) Headings e Parágrafo 
Para marcar um Heading usa-se o # ou <hnumero> --> Quando usa o # tem que ter o espaço entre o # e o texto:
   
````
# Heading 1  ou  <h1 align="center">Título</h1>
## Heading 2  ou  <h2>Título</h2>
### Heading 3  ou  <h3>Título</h3>
#### Heading 4  ou  <h4>Título</h4>
##### Heading 5  ou  <h5>Título</h5>
###### Heading 6  ou  <h6>Título</h6>
<h6 align="center">Título</h6>
````
Exemplo de Titulação
# Heading 1
## Heading 2
### Heading 3
#### Heading 4 
##### Heading 5
###### Heading 6
<h6 align="center">Título</h6>

#### Parágrafo
````
<p align="justify"> Escrever descrição, que ficará com texto justificado</p> 
````
<p align="justify"> Escrever descrição, que ficará com texto justificado</p> 

A tag align é usada para alinhar os elementos e assume left por padrão. 

:book: [Índice](#índice)

### 2) Linhas em Branco
Para deixar uma Linha em branco usa-se a marcação ````<br>```` conforme abaixo:**
````  
<br></br>
````
Exemplo de Linha em branco
<br></br>
:book: [Índice](#índice)

### 3) Negrito
Para fazer negrito usa-se o duplo asterisco ou traço-baixo antes e depois da palavra sem espaço:**
````
**negrito**
__negrito__
````
Exemplo de Negrito
Aqui usou-se **negrito** com duplo asteriscos.
Aqui usou-se __negrito__ com traço-baixo(underscore).
:book: [Índice](#índice)

Equivalente no HTML
````
<b>Negrito</b>  ou  <strong>Negrito</strong>
````
<b>Negrito</b>  ou  <strong>Negrito</strong>

### 4) Itálico
Para fazer itálico usa-se o asterisco ou traço-baixo antes e depois da palavra sem espaço:**
````
*italico* 
_italico_
````
Exemplo de Itálico
Aqui usou-se *itálico com asteriscos*.
Aqui usou-se _itálico com traço-baixo_(underscore).

Equivalente no HTML
````
<i>Itálico</i>
````
Itálico esta em <i>Itálico</i>.

:book: [Índice](#índice)

### 5) Combinação de marcações
````
_You **can** combine them_
````
Exemplo de combinação
_You **can** combine them_

:book: [Índice](#índice)

### 6) Listas
Listas são marcadas com asterisco ou hifen e deve ter espaço simples entre o símbolo e o texto:**
Para sublistas deve ter espaço duplo entre símbolo e texto.

##### 6.1) Lista não Ordenada
````
* Item 1
  * sub item 1
* Item 2
- Item 3
  - sub Item 3
````
Exemplo de Lista
* Item 1
  * sub item 1
* Item 2
- Item 3
  - sub Item 3 

Equivalente em HTML
<ul>
 <li>aa</li>
 <li>bb</li>
</ul>

##### 6.2) Lista Ordenada
````
1. aaaa
2. bbbb
````
1. aaaa
2. bbbb

Equivalente em HTML
<ol>
 <li>aaaa</li>
 <li>bbbb</li>
</ol>

##### 6.3) Task List
````
- [x] Implementar x
- [ ] Implementar y
````
- [x] Implementar x
- [ ] Implementar y


:book: [Índice](#índice)

### 7) Marcadores especiais
````:small_blue_diamond:````  :small_blue_diamond: Tópico com inicio de Diamante Azul

````:heavy_check_mark:````      :heavy_check_mark:

````:warning:````   :warning:

````:dash:````   :dash:

````:arrow_forward:````   :arrow_forward:

````:floppy_disk:````   :floppy_disk:

````:books:````   :books:

````:memo: Tarefa 1````  :memo: Tarefa 1

````:copyright:````  :copyright: 


:book: [Índice](#índice)

### 8) Citações (Quotes)
Uma Citação é visualizada com uma linha vertical cinza e para isto usa-se o símbolo de maior:**
````>Citação````
Exemplo de Citação
>Citação

>Primeiro nível da citação
>>Segundo nível da citação
>>>Terceiro nível da citação

Mais em https://stackoverflow.com/questions/6046263/how-to-indent-a-few-lines-in-markdown-markup 

Equivalente em HTML:
````
<blockquote>Citação em HTML</blockquote>
````
<blockquote>Citação em HTML</blockquote>

:book: [Índice](#índice)

### 9) Links
- **Texto-âncora**: utilize os caracteres [](), adicionando entre chaves o texto que você quer que apareça, e entre os parênteses, o endereço de destino, no formato:
   ````[Site do Terra](https://www.terra.com.br)````
   [Site do Terra](https://www.terra.com.br)
<br></br>
- **Link direto**: envolva o endereço da web em chaves <>. O endereço ficará visível e será clicável pelo usuário. O endereço em forma de link direto tem o formato: ````https://www.link.com.br/ ````
Exemplo link visivel
https://www.terra.com.br/<br></br>

- **Link dentro do arquivo .md - Bookmark links**
  ```
  [Texto para clicar](#9-links)
  texto para clicar: é somente o texto que aparece para o usário
  #link: todos as linhas de um arquivo md marcadas como Títulos utilizando o # para títulos de segundo nível(##) até o de sexto nível(######) são elegíveis para serem links. Somente o Título principal(#) não se consegue colocar link
  ```
  [Texto para clicar](#9-links)
  Este exemplo leva o usuario para o título que tem o texto 9) Links. No VScode ao digitar o [](# ele já dá as opções de autocompletar. Neste exemplo ao digitar [](#) ele já oferece as seguintes opções de destino:
 
  ![](/images/LinksDentroDoArquivo.png)

      Github Flavored Markdown for a while and can summarize with four rules:

      1.punctuation marks will be dropped
      2.leading white spaces will be dropped
      3.upper case will be converted to lower
      4.spaces between letters will be converted to -

      For example, if your section is named this:

          ## 1.1 Hello World


      Create a link to it this way:

          [Link](#11-hello-world)

  <br>
    Equivalente em HTML:<br>

    - **Interno** -  Redirecionará ao elemento âncora contato.
      ```
      <a href="#contato">Contato</a>
      ````
      <a href="#contato">Contato</a>
      <br>

   - **Local** - Redirecionará ao arquivo pagina2.html pertencente à pasta pages.
     ````
     <a href="../pages/pagina2.html">Pagina 2</a>
     ````
     <a href="../pages/pagina2.html">Pagina 2</a>
    <a href="/images/EliseuDoisMonitoresPequena.jpg">Foto Eliseu</a>
    <a href="/images/EliseuDoisMonitoresPequena.jpg">Foto Eliseu</a>
    <img src="/images/EliseuDoisMonitoresPequena.jpg">
    <a href="../README.md">README</a>
    <br>

    - **Global** - Redirecionará à link na web
      ````
      <a href="https://www.terra.com.br">Site do Terra</a>
      ````

      <a href="https://www.terra.com.br">Site do Terra</a>

      Seja redirecionado para o <a href="http://www.google.com/">Google</a>
      <br>
     
    Mais em https://www.homehost.com.br/blog/tutoriais/links-html/
    <br></br>

templateReadmeMarkdown.md  (O uso do .md no final da sentença coloca em azul o texto em forma de link)

Mais informações em:

https://docs.microsoft.com/en-us/contribute/how-to-write-links
https://stackoverflow.com/questions/6695439/how-to-link-to-a-named-anchor-in-multimarkdown

:book: [Índice](#índice)

### 10) Código (Code Highlight)

Há três modos de adicionar trechos de código ao Markdown:

- Código em linha (inline) com adição um acento grave ˋ no início e no final do código.
  ~~~~
  `inline`
  ~~~~
  Esta é uma linha que contém um `código`
<br>
- Código em linha (inline) com a adição de um < no início e um > no final do código.
  I think you should use an`<addr>` element here instead
<br>
- Múltiplas linhas de código: envolva as linhas de código com três acentos graves ˋˋˋ ou três tils ~~~.
  ```
    Esta é uma linha de código
    Esta é outra linha de código
  ```

Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o ˋˋˋ ou ~~~, por exemplo ~~~javascript ou ~~~ruby. Veja nos exemplos abaixo:

~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~Java
Esta é uma linha de código em Java.
~~~

Obs.: Em alguns casos ele cria uma linha extra de erro <p data ........
![](/images/ErroMarcacaoJava.png)
https://stackoverflow.com/questions/65026124/p-data-line-line-number-class-sync-line-style-margin0-p 

:book: [Índice](#índice)

### 11) Imagens e Gifs

O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação ! no início do código, como no exemplo abaixo:
````
![Alt ou título da imagem](URL da imagem)

![GitHub Logo](/images/logo.png) 
````

* Imagem dentro de uma pasta onde esta o arquivo README.md<br>
![LocaldaPasta](/images/LocalPasta.png)
  ````
  ![MarkdownPequena](/images/NiceImagePequena.jpg)
  ````
  ![MarkdownPequena](/images/NiceImagePequena.jpg)
<br></br>

* Imagem dentro em um endereço na internet<br>
    
    * Exemplo dentro de uma página www
    ````
    ![Amazon](https://images-na.ssl-images-amazon.com/images/I/41oAtDLsOEL._SX327_BO1,204,203,200_.jpg)
    ````
    ![Amazon](https://images-na.ssl-images-amazon.com/images/I/41oAtDLsOEL._SX327_BO1,204,203,200_.jpg)<br></br>

  * Exemplo dentro de uma repositorio github

     ````
    ![GitHubPequena](https://github.com/eliseusbrito/LearnedAboutMarkdown/blob/cd929d7b42149d66c79df0ea1dfb41b46b820688/images/GitHubPequena.png) 
      ````
     ![GitHubPequena](https://github.com/eliseusbrito/LearnedAboutMarkdown/blob/cd929d7b42149d66c79df0ea1dfb41b46b820688/images/GitHubPequena.png)   

  * Exemplo de quando o link é protegido ou não existe
  ````
  ![Processo](https://git.cwi.com.br/eliseu.brito/documentacaoOmnichannel/raw/master/documents/pictures/VisaoGeralOmnichannel.jpg)
  ````
  ![Processo](https://git.cwi.com.br/eliseu.brito/documentacaoOmnichannel/raw/master/documents/pictures/VisaoGeralOmnichannel.jpg)


**Obs.: Também tem a maneira “espertinha” (não recomendado): 
Vai em New Issue e joga-se a imagem lá, o GitHub hospeda e já converte em um link certinho, basta copiarmos e jogarmos no README.md.**



Equivalente em HTML:

```
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
```
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
<br></br>
````
<img src="/images/EliseuDoisMonitoresPequena.jpg">
````
<img src="/images/EliseuDoisMonitoresPequena.jpg">
<br></br>

:book: [Índice](#índice)
### 12) Tabelas

Tabela conforme próximas três linhas: 
````
|cabeçalho1|cabeçalho2| 
|-|-| 
|texto1|texto2| 
|texto3|texto4| 
````
|cabeçalho1|cabeçalho2| 
|-|-| 
|texto1|texto2| 
|texto3|texto4| 
<br>

|name|email|git|linkedin|avatar| 
|-|-|-|-|-|
| Eliseu Brito | eliseubritoep@gmail.com | https://github.com/eliseusbrito | https://www.linkedin.cn/in/eliseusilveirabrito |![](/images/EliseuDoisMonitoresPequena.jpg)| 

Em markdown temos que basicamente desenhar a tabela, porém existe um gerador de tabelas que facilita a nossa vida:  https://www.tablesgenerator.com/markdown_tables  
Basta copiar o que o gerador criar e colar no arquivo .md. 

Equivalente em HTML:
~~~~
<table> 
 <thead>
  <th>cabeçalho1</th>
  <th>cabeçalho2</th>
 <thead>
 <tbody>
  <tr>
   <td>texto1</td>
   <td>texto2</td>
  </tr>
  <tr>
   <td>texto3</td>
   <td>texto4</td>
  </tr>
 </tbody>
 </thead>
</table>  
~~~~
<table> 
 <thead>
  <th>cabeçalho1</th>
  <th>cabeçalho2</th>
 <thead>
 <tbody>
  <tr>
   <td>texto1</td>
   <td>texto2</td>
  </tr>
  <tr>
   <td>texto3</td>
   <td>texto4</td>
  </tr>
 </tbody>
 </thead>
</table>

:book: [Índice](#índice)

### 13) Comentar linhas do markdown
````
[//]: # (**negrito** **negrito**)
[//]: <> (fdsaf afs d)
[comment]: <> (f**dsa**fda )
[//]: # (This may be the most platform independent comment)
````
Mais em:
https://qastack.com.br/programming/4823468/comments-in-markdown
https://www.ti-enxame.com/pt/syntax/comentarios-em-markdown/972100416/

:book: [Índice](#índice)

## Fontes

:smile:**Emojis:**<br>
:one: https://www.webfx.com/tools/emoji-cheat-sheet/<br>
:two:  https://gist.github.com/rxaviers/7360908<br> 
:three: https://www.webfx.com/tools/emoji-cheat-sheet/<br>
:four: https://gist.github.com/rxaviers/7360908<br>

:link: **Templates:**

https://gist.github.com/PurpleBooth/109311bb0361f32d87a2 
https://gist.github.com/reginadiana/e044fe93ed81aa04a10361cb841c0409
https://github.com/dbader/readme-template (Este inclusive em inglês, português e espanhol)

:school:**Sites Oficiais**

https://commonmark.org/

https://www.markdownguide.org/

[GitHub Flavored Markdown (GFM)](https://help.github.com/categories/writing-on-github/)

 
:book: [Índice](#índice)

## Ferramentas para Markdown

https://www.markdownguide.org/tools/

http://markdownpad.com/

https://markdownmonster.west-wind.com/


:book: [Índice](#índice)

## Mais sobre Markdown

- Resumo de Comandos
  - https://commonmark.org/help/
  - https://www.markdownguide.org/basic-syntax/
  - https://www.markdownguide.org/extended-syntax/
  - https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_pt-BR.md 

- Sintaxe com seu equivalente em HTML 
  - https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8 

- https://dev.to/reginadiana/como-escrever-um-readme-md-sensacional-no-github-4509 

- https://guides.github.com/features/mastering-markdown/ 

- https://docs.gitlab.com/ee/user/markdown.html 

- Formatting text with Markdown
  - https://support.zendesk.com/hc/pt-br/articles/203691016-Formata%C3%A7%C3%A3o-de-texto-com-Markdown 

- Guia básico de Markdown
  - https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open

- Ajuda do markdown
  - https://pt.stackoverflow.com/editing-help


- Veja alguns problemas que surgiram no desenvolvimento deste projeto e como os resolvi em [issues](https://github.com/Diana-ops/treina-dev-turma-3/issues) 
https://github.com/reginadiana

:book: [Índice](#índice)
