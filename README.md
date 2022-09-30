<p>O projeto foi desenvolvido por <a href="https://github.com/Istvanoliva">Istvan Oliva</a> enquanto estudava na <a href="https://www.betrybe.com/">Trybe</a> :rocket:</p>

# O que será desenvolvido

Nesse projeto vocês farão um **carrinho de compras** totalmente dinâmico! E o melhor: consumindo dados diretamente de uma **API!** Isso mesmo. Da sigla em inglês _Application Programming Interface_, uma API é um ponto de contato na internet com determinado serviço. Através de **requisições HTTP** a essa API é possível interagir com ela da forma como quem a criou planejou. Aqui usaremos a API do Mercado Livre para buscarmos produtos à venda.

### Protótipo do projeto

Seu projeto deve ter o comportamento parecido com o do gif abaixo quando finalizado, **não se preocupe em replicar o visual, o gif so ilustra o comportamento**:

![Project Gif](./prototipo.gif)

---

## Requisitos do projeto
  - [API Shopping Cart](#api-shopping-cart)
  - [Observações técnicas](#observações-técnicas)
    - [1. Crie uma listagem de produtos](#1-crie-uma-listagem-de-produtos)
    - [2. Adicione o produto ao carrinho de compras](#2-adicione-o-produto-ao-carrinho-de-compras)
    - [3. Remova o item do carrinho de compras ao clicar nele](#3-remova-o-item-do-carrinho-de-compras-ao-clicar-nele)
    - [4. Carregue o carrinho de compras através do **LocalStorage** ao iniciar a página](#4-carregue-o-carrinho-de-compras-através-do-localstorage-ao-iniciar-a-página)
    - [5. Some o valor total dos itens do carrinho de compras](#5-some-o-valor-total-dos-itens-do-carrinho-de-compras)
    - [6. Crie um botão para limpar o carrinho de compras](#6-crie-um-botão-para-limpar-o-carrinho-de-compras)
    - [7. Adicione um texto de "carregando" durante uma requisição à API](#7-adicione-um-texto-de-carregando-durante-uma-requisição-à-api)
    - [8. Desenvolva testes para atingir 40% de cobertura](#8-desenvolva-testes-para-atingir-40-de-cobertura)
    - [9. Desenvolva testes para atingir 60% de cobertura](#9-desenvolva-testes-para-atingir-60-de-cobertura)
    - [10. Desenvolva testes para atingir 80% de cobertura](#10-desenvolva-testes-para-atingir-80-de-cobertura)
    - [11. Desenvolva testes para atingir 100% de cobertura](#11-desenvolva-testes-para-atingir-100-de-cobertura)
---

## Habilidades

Nesse projeto, você será capaz de:

- Fazer requisições a uma API *(Application Programming Interface)* do Mercado Livre;
- Utilizar os seus conhecimentos sobre JavaScript, CSS e HTML;
- Trabalhar com funções assíncronas;
- Implementar testes unitários.
