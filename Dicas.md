<p align="center"> 
<img src="https://user-images.githubusercontent.com/32847584/52163816-f2cab480-26ce-11e9-9603-3ff6c6ed3e13.png">
</p>


# Phonegap / Cordova
Dicas para uso rápido do Phonegap ou Cordova




# Sumário
1. [Istalação](#1-instalação)
2. [Fluxo de Trabalho](#2-trabalho)
3. [Links](#3-links)


## 1. Instalação
-   Instale o Node.js https://nodejs.org/en/
-   Instale o Git https://git-scm.com/downloads
-   Configure as variáveis globais do git pelo CMD

```
$ git config --global user.name "Seu Nome"
$ git config --global user.email seuemail@email.com
```

- Baixe para Windows: https://gitforwindows.org/


## 2. Fluxo de Trabalho

**Criando um novo repositório**

- Crie uma pasta e dentro dela execute:

- `$ git init`

**Obtenha um repositório**

- crie uma cópia de trabalho em um repositório local executando:

		$ git clone /caminho/para/o/repositório

**Trabalhando com git**

- Seus repositórios locais consistem em três árvores mantidas pelo git. A primeira delas é sua "Working Directory" que contém os arquivos vigentes. A segunda "Index" que funciona como uma área temportária e finalmente a `Head` que aponta para o último commit (confirmação) que você fez.

    - **Adicionar & Confirmar**

    - Você pode propor mudanças (adicioná-las ao Index) usando:
        - $git add <arquivo>
        - $git add *

    - Para realmente confirmar estas mudanças (isto é, fazer um commit), use:
        - $git commit -m "comentários das alterações"

    - Para enviar suas alterações da sua cópia de trabalho para "Head" execute:
        - $git push origin master

## 3. Links

- [git-guide](http://rogerdudler.github.io/git-guide/index.pt_BR.html)
- [tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/]()https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)

