# Projeto Dices

Este é um projeto simples de um rolador de dados virtual, criado com HTML, CSS e JavaScript. Ele permite ao usuário simular a rolagem de dados poliédricos comuns (como D20, D12, D10, etc.) e também um dado personalizado.

##  Funcionalidades

* **Rolagem de Dados Padrão:** Botões dedicados para rolar os dados mais comuns:
    * D4
    * D6
    * D8
    * D10
    * D12
    * D20
    * D100
* **Rolagem de Dado Personalizado:** O usuário pode inserir um número em um campo de entrada e clicar em "Enter" para rolar um dado com esse número de lados (ex: D50, D7, etc.).
* **Exibição de Resultado:** O resultado da última rolagem é exibido dinamicamente na página.

## Tecnologias Utilizadas

* **HTML5**
* **CSS3** (Estilização interna no arquivo `index.html`)
* **JavaScript** (ES6+)

## Como Usar

1.  Abra o arquivo `index.html` em qualquer navegador web.
2.  A página exibirá o título "SELECIONE O SEU DADO".
3.  Clique em um dos botões (D4, D20, etc.) para rolar o dado correspondente.
4.  Para um dado personalizado, digite o número máximo desejado no campo de texto (`id="perdice"`) e clique no botão "Enter".
5.  O resultado aparecerá na parte inferior, dentro da `div` com `id="result"`.