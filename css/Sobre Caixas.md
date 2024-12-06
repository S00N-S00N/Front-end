Todos os elementos dentro do html são cercados por caixas que definem seus espaçamento, logo, no css a gente é capaz de alterar esse espaçamento de forma simples, mas para outros, de forma confusa. Então estarei como funciona o posicionamento de caixas, útil para a construção de layouts.
## Como funciona :

Qualquer elemento de uma parte do html tem essa estrutura de caixa:

![[Pasted image 20241205204126.webp|695]]

* **1366x70** : É dentro desse espaço onde está demarcado a resolução, onde fica o conteúdo, o 1366x70 informa a resolução do conteúdo e que pode ser mudada com o `height` e `width`.
* **padding**: É todo espaçamento externo do elemento e que pode ser visível com o `background-color` e alterado com o `padding`.
* **border**: É todo o contorno do conteúdo principal do elemento.
* **margin**: Essa é a parte que ocupa toda a área de fora, criando um espaçamento entro os demais itens e que não é visível ao usuário
___
## Padding:

Existem comandos específicos para a alteração do padding, que são eles

* `padding-top`: Aumenta ou diminui o padding da parte de cima 
* `padding-left`: Aumenta ou diminui o padding da parte esquerda
* `padding-bottom`: Aumenta ou diminui o padding da parte de baixo
* `padding-right`: Aumenta ou diminui o padding da parte esquerda

* `padding`: Aumenta ou diminui todas as áreas do patting. Exemplo:

```
padding: 10px 10px 10px 10px;
```
## Margin:

Existem comandos específicos para a alteração do margin, que são eles

* `margin-top`: Aumenta ou diminui o margin da parte de cima 
* `margin-left`: Aumenta ou diminui o margin da parte esquerda
* `margin-bottom`: Aumenta ou diminui o margin da parte de baixo
* `margin-right`: Aumenta ou diminui o margin da parte esquerda

* `margin`: Aumenta ou diminui todas as áreas do patting. Exemplo:

```
margin: 10px 10px 10px 10px;
```
