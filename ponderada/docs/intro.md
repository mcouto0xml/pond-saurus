---
sidebar_position: 1
---

# Ponderada

Let's discover **Docusaurus in less than 5 minutes**.

## Ponderada

O primeiro passo da ponderada é criar um ambiente usando o framework Docussaurus

Antes disso, é necessário instalar as dependências, que são o Node.js (o motor de JavaScript que executa o código) e o npm (Node Package Manager), que é o gerenciador de pacotes para o Node.js. O npm será utilizado para instalar as bibliotecas e pacotes necessários para o Docusaurus e outros componentes do projeto.

Depois disso, criamos um diretório padrão no repositório do GitHub: .github/workflows/deploy.yml.

Este arquivo deploy.yml é necessário para a automação do deploy no GitHub Pages. Ele é responsável por executar um conjunto de ações automáticas sempre que há alterações no código, isto é, ao acionado o trigger (push na main), ele instala as dependências, constroi o site do docussaurus utilizando o diretório build/ e empurra os conteúdos dessa pasta para a branch gh-pages, que posteriormente será utilizado pelo GitHub Pages para deploy

Além disso, é necessário configurar o repositório no GitHub para permitir o uso do GitHub Pages. Nas configurações do repositório, você deve indicar que o GitHub Pages usará a branch gh-pages para o deploy.

Dessa forma, é garantido que toda alteração feita na documentação seja atualizada, e feita o deploy sem trabalho manual.
