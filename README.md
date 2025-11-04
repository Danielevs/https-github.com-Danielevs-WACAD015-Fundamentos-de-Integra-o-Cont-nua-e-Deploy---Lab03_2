# 💻 Laboratório 03 – Exercício 01: Aplicando o conceito de testes utilizando Jest com uma biblioteca externa para análise de cobertura


Este repositório contém os arquivos e configurações do exercício 01 do Laboratório 02 da Web Academy. O objetivo é aprender a configurar e utilizar **GitHub Actions** para automatizar tarefas em projetos de desenvolvimento.

## 📌 Objetivos do exercício

- Consolidar o uso de pipelines através da configuração de etapas de teste (usando o Jest) e com o uso de Containers.

## 🛠️ Estrutura do projeto
.github/ └── workflows/ └── teste.yml

## Pré-Requisitos:
- Ter uma conta no GitHub
- Máquina com Linux / Windows instalado e Git já configurado com a conta do GitHub
- Ter uma conta no Docker Hub
- Arquivos disponíveis no Colabweb para o Laboratório (caso necessário)

## 🚀 Como funciona o workflow:

O arquivo `build.yml` define um fluxo de trabalho que é executado automaticamente quando há um `push` ou `pull request` no branch `main`. Ele pode incluir etapas como:

- Instalar dependências
- Rodar testes
- Gerar builds

## 📂 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Danielevs/WACAD015-Fundamentos-de-Integracao-Continua-e-Deploy---Lab02---Exercicio-2

2. Faça alterações e envie para o GitHub

git add .

git commit -m "Atualiza workflow"

git push

