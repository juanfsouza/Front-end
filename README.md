# Logica-Media
Criando logica e Media em css, html e js. Em site jsfiddle.net


### Link do site que foi utilizado > MEDIA <
 
 > https://jsfiddle.net/spzofL13/
 
 ## Var
 - Barco = E
 - Homem = H
 - Lobo = A
 - Cabra = B
 - Maço de Alfafa = C
 
### Destino = A1, B2, C3
 
### Homem tem que levar o lobo, a cabra e alfafa para o destino com o barco, so que nao pode levar um de cada vez e nao pode deixar lobo junto com a cabra e tambem nao pode deixa cabra com Alfafa.
 
### Resultado
 - Inicio;
 - Receber Primeiro numero: H + E + B = B2
 - H + E voltar;
 - Receber Primeiro numero: H + E + A = A1
 - H + E voltar;
 - Receber Primeiro numero: H + E + B = C3
 - Procesamento: Homem leva seus pertences ao destinos.
 - Fim
 
 #

### DOM

Document Object Model
Estrutura de um arquivo na web
Representa documentos HTML ou XML
Interface de programação
NÃO é uma linguagem de programação
É essencial para o JS entender o modelo de páginas web

## Para que serve?

Alterar a estrutura
Alterar o estilo
Alterar o conteúdo

## Como?

Disponibilizando API (Application Programming Interface)
Rotinas e padrões estabelecidos
Métodos (funções)
Árvore de elementos
Seletores
Objetos (nós / nodes)

## Exemplo HTML

<html>
    <head></head>
    <body></body>
</html>

## Exemplo Obj

objeto = {
    html : {
        head : {},
        body : {
            h1 : {

            }
        }
    }
}

### DOM x JS

O DOM pode ser usado por outras linguagens
Sem o DOM o JS não teria noção da página
Vantagens de usar JavaScript
Código é executado por navegadores
Tornar as páginas dinâmicas
Evitar Requisições desnecessárias (performance)
SPA (Single Page Applications)
Reagir rapidamente a ações dos usuários

## Desevantagens de usar o JavaScript

Código é executado por navegadores
O conteúdo NÃO fica visível para indexadores de busca
Alterações em tempo de execução não ficam salvas no documento

## Exemplos

Seleciona o objeto e diposinibiliza (métodos / funçõe).callback

document.getElementById(id)
document.getElementsByTagName('div')
document.createElement('div')
parentNode.appendChild(node) // html.appendChild('body')
element.innerHTML
element.style
element.setAttribute('name')
element.getAttribute('name')
element.addEventListener()
window.location
window.onload
console.log()
window.scrollTo(x, y)

## Seletores

Tipos de seletores: Tag, ID, Class, Name, Query
Callback
getElementById()
getElementsByTagName()
getElementsByName()
getElementsByClassName()
querySelectorAll() // #id | .class

## Formulários

Precisamos evitar que o usuário passe dados incorretos
Ou seja, para direcionar melhor o uso do nosso sistema
Proteger a injeção de código malicioso
Evitar erros de processamento
Formatar dados para facilitar o processamento
Filtro para o back-end
Regex (expressões regulares)

### Referências

DOM: https://dom.spec.whatwg.org/
Tecnologias JS: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/JavaScript_technologies_overview
Motores de execução: https://pt.wikipedia.org/wiki/Lista_de_motores_de_renderiza%C3%A7%C3%A3o
Expressões Regulares: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Regular_Expressions


### Bootstrap

Framework ou biblioteca desenvolvimento
Modular
Componentes ricos
CSS + JS
Grid System
Responsivo
Mobile-first
Amplamente utilizada
Cross browser

### Biblioteca x Framework

Biblioteca: oferece objetos / classes prontas para uso
Framework: oferece um conjunto de bibliotecas
Biblioteca: recurso para trabalhar
Framework: metodologia de trabalho
Biblioteca: te leva ao destino
Framework: te ensina a chegar

## Desenvolvimento ágil

Metodologias: Scrum, Kanban, XP
Entrega de valor para o negócio
Ciclos evolutivos
Não se repita
Separar grandes projetos em pequenas entregas
MVP - Mínimo Produto Viável
Estar envolvido x comprometido

## Vantagens

Uso simples
Menos código
Abstração de estilos
Documentação completa: https://getbootstrap.com/

## Desvantagens

Uso excessivo
Override de estilos (sobreposição)
Abstração de estilos
Com Bootstrap
 <a class="btn btn-lg">Botão</a>
Sem Bootstrap
 <a class="botao botao-grande">Botão</a>

 <style>
 html {
     font-size: 62.5% 
 }

 .botao {
    background-color: #ccc; 
    border-radius: 2px; 
    display: block;
    font-family: sans-serif;
    font-size: 1.6rem;
    padding: 1rem 2rem;
    margin: 5px auto;
    ...
 }

 .botao.grande {
    font-size: 2rem;
 }

 .botao:hover { ... }
 .botao:active { ... }
 .botao:visited { ... }
 
 </style>

### Componentes

Blocos / Modelos / Templates reutilizáveis https://getbootstrap.com/docs/5.1/components
Helpers
Funções básicas
Incrementos
Ajustes https://getbootstrap.com/docs/5.1/helpers
Font Awesome
Biblioteca de ícones https://fontawesome.com/start/
# Logica-Media
Criando logica e Media em css, html e js. Em site jsfiddle.net


### Link do site que foi utilizado > MEDIA <
 
 > https://jsfiddle.net/spzofL13/
 
 ## Var
 - Barco = E
 - Homem = H
 - Lobo = A
 - Cabra = B
 - Maço de Alfafa = C
 
### Destino = A1, B2, C3
 
### Homem tem que levar o lobo, a cabra e alfafa para o destino com o barco, so que nao pode levar um de cada vez e nao pode deixar lobo junto com a cabra e tambem nao pode deixa cabra com Alfafa.
 
### Resultado
 - Inicio;
 - Receber Primeiro numero: H + E + B = B2
 - H + E voltar;
 - Receber Primeiro numero: H + E + A = A1
 - H + E voltar;
 - Receber Primeiro numero: H + E + B = C3
 - Procesamento: Homem leva seus pertences ao destinos.
 - Fim
 
 #

### DOM

Document Object Model
Estrutura de um arquivo na web
Representa documentos HTML ou XML
Interface de programação
NÃO é uma linguagem de programação
É essencial para o JS entender o modelo de páginas web

## Para que serve?

Alterar a estrutura
Alterar o estilo
Alterar o conteúdo

## Como?

Disponibilizando API (Application Programming Interface)
Rotinas e padrões estabelecidos
Métodos (funções)
Árvore de elementos
Seletores
Objetos (nós / nodes)

## Exemplo HTML

<html>
    <head></head>
    <body></body>
</html>

## Exemplo Obj

objeto = {
    html : {
        head : {},
        body : {
            h1 : {

            }
        }
    }
}

### DOM x JS

O DOM pode ser usado por outras linguagens
Sem o DOM o JS não teria noção da página
Vantagens de usar JavaScript
Código é executado por navegadores
Tornar as páginas dinâmicas
Evitar Requisições desnecessárias (performance)
SPA (Single Page Applications)
Reagir rapidamente a ações dos usuários

## Desevantagens de usar o JavaScript

Código é executado por navegadores
O conteúdo NÃO fica visível para indexadores de busca
Alterações em tempo de execução não ficam salvas no documento

## Exemplos

Seleciona o objeto e diposinibiliza (métodos / funçõe).callback

document.getElementById(id)
document.getElementsByTagName('div')
document.createElement('div')
parentNode.appendChild(node) // html.appendChild('body')
element.innerHTML
element.style
element.setAttribute('name')
element.getAttribute('name')
element.addEventListener()
window.location
window.onload
console.log()
window.scrollTo(x, y)

## Seletores

Tipos de seletores: Tag, ID, Class, Name, Query
Callback
getElementById()
getElementsByTagName()
getElementsByName()
getElementsByClassName()
querySelectorAll() // #id | .class

## Formulários

Precisamos evitar que o usuário passe dados incorretos
Ou seja, para direcionar melhor o uso do nosso sistema
Proteger a injeção de código malicioso
Evitar erros de processamento
Formatar dados para facilitar o processamento
Filtro para o back-end
Regex (expressões regulares)

### Referências

DOM: https://dom.spec.whatwg.org/
Tecnologias JS: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/JavaScript_technologies_overview
Motores de execução: https://pt.wikipedia.org/wiki/Lista_de_motores_de_renderiza%C3%A7%C3%A3o
Expressões Regulares: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Regular_Expressions


### Bootstrap

Framework ou biblioteca desenvolvimento
Modular
Componentes ricos
CSS + JS
Grid System
Responsivo
Mobile-first
Amplamente utilizada
Cross browser

### Biblioteca x Framework

Biblioteca: oferece objetos / classes prontas para uso
Framework: oferece um conjunto de bibliotecas
Biblioteca: recurso para trabalhar
Framework: metodologia de trabalho
Biblioteca: te leva ao destino
Framework: te ensina a chegar

## Desenvolvimento ágil

Metodologias: Scrum, Kanban, XP
Entrega de valor para o negócio
Ciclos evolutivos
Não se repita
Separar grandes projetos em pequenas entregas
MVP - Mínimo Produto Viável
Estar envolvido x comprometido

## Vantagens

Uso simples
Menos código
Abstração de estilos
Documentação completa: https://getbootstrap.com/

## Desvantagens

Uso excessivo
Override de estilos (sobreposição)
Abstração de estilos
Com Bootstrap
 <a class="btn btn-lg">Botão</a>
Sem Bootstrap
 <a class="botao botao-grande">Botão</a>

 <style>
 html {
     font-size: 62.5% 
 }

 .botao {
    background-color: #ccc; 
    border-radius: 2px; 
    display: block;
    font-family: sans-serif;
    font-size: 1.6rem;
    padding: 1rem 2rem;
    margin: 5px auto;
    ...
 }

 .botao.grande {
    font-size: 2rem;
 }

 .botao:hover { ... }
 .botao:active { ... }
 .botao:visited { ... }
 
 </style>

### Componentes

Blocos / Modelos / Templates reutilizáveis https://getbootstrap.com/docs/5.1/components
Helpers
Funções básicas
Incrementos
Ajustes https://getbootstrap.com/docs/5.1/helpers
Font Awesome
Biblioteca de ícones https://fontawesome.com/start/
