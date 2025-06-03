# TDE 02 - CI com GitHub Actions

Este projeto foi desenvolvido para a TDE 02. Ele consiste em uma aplicação web simples utilizando HTML, CSS e JS, com pipeline de integração contínua configurado usando GitHub Actions.

## Estrutura
- Branch `main`: versão estável.
- Branch `dev`: desenvolvimento.

## CI
- A cada push ou pull request para a branch `main`, o GitHub Actions:
  - Valida o código JavaScript com ESLint.
  - Gera o build (simples).

## Estrutura de Dados
📁 projeto/
├── index.html
├── style.css
├── script.js
├── package.json
├── .github/
│ └── workflows/
│ └── ci.yml
└── README.md

## Deploy
O projeto é publicado automaticamente via GitHub Pages.


## Integrantes
Kaique Chaves Silva,
Rodolfo Sousa da Macena,
Maria Eduarda Pinto Ramos,
Camila Costney de Moura Silva, 
Winicius Lira Passaia.
