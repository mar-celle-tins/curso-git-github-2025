# Curso TMW Git e GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub. 

Além disso, vamos trabalhar com GitFlow ao final do curso e VS Code. 

Confira tudo o que temos no Youtube. É de graça! 

[Curso Git 2025]

Além do nosso canal no Youtube, se ligue no nosso site e agenda para ficar por dentro de tudo o que vai rolar em 2025. 

[site]

## Fluxo de trabalho Git local

    git checkout -b
    cria ou atualiza arquivos
    git status
    git add arquivos
    git status
    git commit -m "minha mensagem"
    git checkout main
    git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

    git clone
    git checkout -b <nova_branch>
    alterações de arquivos
    git status
    git add arquivos
    git status
    git commit -m "nova mensagem"
    git push origin <nova_branch>
    abrir Pull request no GitHub para main
    excluir <nova_branch> origin
    git checkout main
    git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

    Fork do projeto para seu próprio github
    git clone
    git checkout -b <nova_branch>
    alterações de arquivos
    git status
    git add arquivos
    git status
    git commit -m "nova mensagem"
    git push origin <nova_branch>
    abrir Pull request no GitHub da branch fork para a main do projeto original
    excluir <nova_branch> origin
    git checkout main
    git branch -D <nova_branch>

## Pessoas participantes:

    Igor Dammous
    Infoslack
    Leo Medeiros
    Mateus Dantas
    Tales
    Téo Calvo
