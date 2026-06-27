# teste-devops-ivory

## Sobre o projeto

Este projeto foi desenvolvido como parte do teste técnico DevOps da IVORY.

O objetivo foi criar um fluxo completo utilizando Git, CI/CD, análise de qualidade de código e deploy em nuvem.

---

# Estratégia de Branches

Foi utilizado o fluxo:

feature - develop - homolog - main

Branches utilizadas:

- main: produção
- homolog: validação
- develop: desenvolvimento
- feature/site-inicial: implementação inicial

---

# CI/CD

Foi criado um pipeline utilizando GitHub Actions.

O pipeline executa:

- checkout do código;
- análise de qualidade utilizando SonarCloud.

---
