# __Estudos_FRONT-END__.
---
## __HTML__.
---
#### __Módulo 02__.
- __0201 Tag__ - Explicação de o que é uma Tag.
- __0202 Tags Iniciais__ - Explicação das tags mais comuns.
- __0203 Estrutura HTML__ - Tags de informação para os navegadores.
- __0204 Editor de Plugins__ - Instalando o Live Server, Prettier e ajustando o settings.json do vscode.
- __0205 Editor Atalhos__ - Alguns atalhos que vão me ajudar no decorrer dos estudos.
- __0206 Link Caminhos__ - Diferença de link relativo e absoluto.
- __0207 CSS Básico__ - Explicação do CSS e uso Básico.
- __0208 CSS Seletores__ - Algumas distinções entre classes e ids.
- __0209 HTML Exercício__ - Exercício Cinema.
- __0210 Background e Cores__ - Mostrando o atributo de background e background-color.
- __0211 Box Model 1__ - Explicação do que é um box model e como isso é usado para sites.
- __0211 Box Model 2__ - Apresentação da div ou caixa comumente chamada.
- __0212 Estilos do Browser__ - Mostrando que alguns navegadores já vem com stylos básicos ativos por padrão.
- __0213 Display__ - explicação sobre o posicionamento.
- __0214 Display Exercício__ - Um bom exercício para começar com os posicionamento de algumas estruturas básicas.
- __0216 Imagens 1__ - Testando a tag de imagem.
- __0216 Imagens 2__ - Mostrando dois sites para ajudar com imagens.
---
#### __Módulo 03__
- __0301 Top, Right, Bottom, Left__ - Mostra como podemos usar esses atributos em css e usar ao nosso favor. podemos usar no `padding` e no `margin`, mas sem esquecer de colocar o atributo `display: inline-block` se não não vai funcionar as margens externas.
- __0302 Grid Columns 1__ - preparando as informações como html e css para uso do `grid`.
- __0302 Grid Columns 2__ - Com o uso do `grid` podemos dividir a tela de várias formas.
- __0303 Align e Justify Content__ - O uso do grip e justify content para ajustar os itens.
- __0304 Grid Column 1 e 2__ - Aprendendo a dividir o grid layout.
- __0305 Grid Column 1 + Grid Column 2__ - Posicionamento o grid layout com align e justify itemns. Com isso eu consigo posicionar os itens dentro do grid, como por exemplo: `grid-column: 1 / 3` que vai ocupar a coluna 1 e 2.
- __0306 Grid Template Rows__ - Aprendendo a controlar as linhas do grid com `grid-template-rows`, definindo quantas linhas o grid terá e o tamanho de cada uma.  
  Com `grid-template-columns` você define quantas colunas o grid terá e o tamanho de cada coluna.  
  Usando `place-items: start` é possível alinhar todos os itens ao início do grid.  
  Também é possível posicionar elementos em locais específicos do grid usando `grid-column` e `grid-row`, por exemplo:  
  - Definir que um elemento ocupe todas as colunas,
  - Que outro fique apenas em uma coluna específica,
  - Ou que um elemento ocupe várias linhas dentro de uma coluna.
  __No arquivo 0306_2.html__ A div com a classe `.info` foi configurada como um novo grid dentro do grid principal.  
  - `display: grid;` faz com que os elementos internos da `.info` também sejam organizados em grid.
  - `place-items: start;` alinha todos os itens ao início tanto na horizontal quanto na vertical.
  - `gap: 20px;` adiciona um espaçamento de 20px entre os itens internos.
  - `place-self: start;` faz com que a própria `.info` fique alinhada ao início da célula do grid principal onde ela está.

  Isso permite um controle mais preciso do alinhamento e espaçamento dos elementos dentro da `.info`, deixando o layout mais organizado.
---
## CSS. 
---
#### __Módulo 02__.
- __0207 CSS Básico__ - color: mudar a cor do texto, `text-decoration none` tira o underline dos links, `font-size`: mudar o tamanho da fonte.
- __0208 CSS Seletores__ - Em css a diferença entre `id="teste_1"` e `class="teste_1"`, `#teste_1 e .teste_1`.
- __0210 Background e Cores__ - Mostrando o atributo de `background` e `background-color`, mudar a cor de fundo.
- __0211 Box Model 1__ - `width`: é a largura do conteúdo da caixa, `padding`: é a distância entre o conteúdo e a borda, `border`: é a borda da caixa, margin: é a distância entre a borda e o elemento vizinho.
- __0213 Display__ - `display: inline-block` Não inicia uma nova linha, permitindo que outros elementos fiquem ao lado dele, como um elemento inline.
- __0214 Display Exercício__ - `text-align: center` centralizar textos de acorco com o pretendido. `border-radius`: para aredondar as informações.
- __0216 Imagens 1__ - o atributo `max-width: 100%` repsita o elemento pai, `width: 100px` numa div, a img vai respeitar isso.
---
#### __Módulo 03__.
- __0301 Top, Right, Bottom, Left__ - Podemos usar esses quatro atributos tanto com `padding` e com `margin` mesclando seus nomes exemplo: `padding-top`.
- __0302 Grid Columns 1 e 2__ - A nova pripriedade `grid`, usando os atributos `diplay: grid` -> `grid-template-columns: 1fr 2fr` ele difvide a tela proporcionale `grid-gap` é o espaçamento entre os elementos que queremos separar.
- __0303 Grid columns__ - Aprendemos a dividir o grid de tela em vários, usando `display: grid;` e `grid-template_columns: 1fr 1fr 1fr 1fr`(4) no *css*. 
 __0304 Grid Column 1 e 2__ - Posso fazer algo semelhante a aula 0303, porém eu posos posicionar dentro do grid, como indo nas classes e alterando o grid column.
---
## JavaScript.
