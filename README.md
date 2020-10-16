# Jmeter Script Sample
Escrito para suportar o artigo: https://medium.com/beyondtest/testes-de-performance-com-jmeter-influxdb-e-grafana-317ce86fa840

Utilitário para subir a infraestrutura necessária e assim realizar todos os passos do artigo acima.

## Pré requisitos

* Node
* NPM
* Docker

Para executar:

> npm run start

O comando acima ira baixar as dependências do projeto, baixar as imagens Docker necessárias e rodar uma API REST Fake que será utilizada no teste de performance descrito no artigo.
