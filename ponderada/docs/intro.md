---
sidebar_position: 1
---

# Ponderada

Let's discover **Docusaurus in less than 5 minutes**.

## Ponderada

O primeiro passo da ponderada é criar um ambiente usando o framework Docussaurus

Claro, antes disse é necessário instalar as dependências, que são o Node.js que é o nosso motor de JavaScript e o npm (Node Package Manager), que tem a função de manipular os pacotes do Node.

Depois disso criamos um diretório padrão do github:
.github/worflows/deploy.yml

Esse arquivo é necessário para a automação do Deploy no Github Pages, ele serve para empurrar os conteúdos da pasta build/ do Docussaurus para a branch gh-pages, que será utilizada para o Deploy.

É nessários também, mudar nas configurações do repositório para comportar o GithubPages e avisar qual branch será utilizada.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
