# Git/GitHub

## Anotações das aulas

### Comandos para criar chaves SSH E token

  1 - Entrar na sua maquina e abrir o Git bash

O Git bash é um terminal extendido para otimizar o uso do Git.

  2 - Código: $ ssh -keygen -t ed25519 -C "seu email" 
   obs = o (-C) de ser em letra maiúscula e de preferência usar o email que usou para criar sua conta no GitHub.

### Alguns códigos usaveis no terminal Git

  1 - cd (nome da pasta):  entra na pasta desajada.
  2 - ls: cria uma lista do que tem na pasta.
  3 - cd ..: voltar um nível.
  4 - Ctrl + l: limpar terminal
  5 - ls -a: mostrar arquivos ocultos
  6 - git status: olhar a situação que se encontra os arquivos presentes na pasta
  7 - git clone ( cole a web URL): faz um clone do repositório escolhido.

### Commitar arquivo

  1 - Git add* 
  2 - (tirar do modo stage) git commit -m "menssagem"

### Puxar arquivo da maquina

  1 - git remote add origin (link do repositório)
  2 - git puch origin main
