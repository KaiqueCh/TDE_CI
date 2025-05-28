# TDE 02 - CI com GitHub Actions

Este projeto foi desenvolvido para a TDE 02. Ele consiste em uma aplicação web simples utilizando HTML, CSS e JS, com pipeline de integração contínua configurado usando GitHub Actions.

## Estrutura
- Branch `main`: versão estável.
- Branch `dev`: desenvolvimento.

## CI
- A cada push ou pull request para a branch `main`, o GitHub Actions:
  - Valida o código JavaScript com ESLint.
  - Gera o build (simples).

## Deploy
O projeto é publicado automaticamente via GitHub Pages.
