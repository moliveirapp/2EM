# Guia Básico de Git e GitHub

Este é um guia básico para começar a usar o Git e o GitHub via linha de comando.

##Alguns comandos que iremos trabalhar:
### Commit

Um `commit` no Git representa uma confirmação de alterações em um repositório. Cada commit registra uma versão específica dos arquivos do projeto, juntamente com uma mensagem descritiva que resume as alterações realizadas.

### Exemplo de Commit:

Para realizar um commit no Git:

```bash
git add arquivo.txt      # Adiciona arquivo ao stage (área de preparação)
git commit -m "Adicionando arquivo.txt"   # Cria um commit com uma mensagem descritiva

## Instalação do Git

Certifique-se de ter o Git instalado em seu sistema. Você pode baixá-lo em [git-scm.com](https://git-scm.com/).

## Configuração Inicial do Git

Configure seu nome de usuário e endereço de e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu_email@example.com"


Este guia fornece uma introdução simples ao Git, abordando os conceitos básicos e os comandos mais comuns.

## Criar um Repositório

Para criar um novo repositório Git localmente:

1. **Inicialize um novo repositório:**

   ```bash
   mkdir novo-repositorio
   cd novo-repositorio
   git init

echo "# Meu Novo Repositório" >> README.md
git add README.md
git commit -m "Primeiro commit - adicionando README.md"
git remote add origin https://github.com/seu-usuario/novo-repositorio.git
git push -u origin main


### Arquivos .MD
Um arquivo .MD é um arquivo de texto formatado usando a linguagem de marcação Markdown. O Markdown é uma linguagem simples de formatação de texto que permite adicionar formatação básica, como títulos, listas, links e ênfase, usando uma sintaxe fácil de ler e escrever. Os arquivos .MD são comumente usados para escrever documentação, READMEs, wikis, e-mails formatados e até mesmo livros.

A extensão .MD é uma abreviação de "Markdown", e os arquivos .MD geralmente contêm texto formatado com Markdown, que pode ser renderizado em HTML para exibição em navegadores da web, editores de texto e outras ferramentas que suportam Markdown.

Markdown é popular entre desenvolvedores, escritores técnicos e qualquer pessoa que precise escrever documentos simples e bem formatados de forma rápida e eficiente.

Há muitos recursos online disponíveis para aprender Markdown e usar arquivos .MD. Alguns dos sites de documentação úteis incluem:

Markdown Guide: Um guia abrangente para a sintaxe Markdown, com exemplos e explicações detalhadas.
Link: Markdown Guide
GitHub Markdown Guide: O GitHub possui seu próprio guia Markdown, que fornece instruções detalhadas sobre como usar Markdown em repositórios do GitHub.
Link: GitHub Markdown Guide


Esse README.md fornece uma visão geral simples dos conceitos de Git, incluindo como criar um repositório, clonar um repositório existente e explicar os comandos `commit`, `push` e `pull`. Os exemplos de comandos fornecidos demonstram como usar essas operações básicas no Git para gerenciar seus projetos de desenvolvimento de software.
