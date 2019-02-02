<p align="center"> 
<img src="https://user-images.githubusercontent.com/32847584/52164306-7340e380-26d6-11e9-99de-74f657312ea4.png">
</p>

# Phonegap / Cordova
Dicas para uso rápido do Phonegap ou Cordova

# Sumário
1. [Istalação](#1-instalação)
2. [Fluxo de Trabalho](#2-fluxo-de-trabalho)
3. [Links](#3-links)

## 1. Instalação
-   Instale o Node.js https://nodejs.org/en/
-   Instale o Git https://git-scm.com/downloads
-   Configure as variáveis globais do git pelo CMD
-   Instale o Java https://www.oracle.com/technetwork/java/javase/downloads/index.html
-   Instale o Android Studio https://developer.android.com/studio/#download

```
    $git config --global user.name "Seu Nome"
    $git config --global user.email seuemail@email.com
```
-   **Instale o Phonegap**
```
    $npm install -g phonegap
```

-   **Configure o Path do Windows**
    -   Adicione o path \sdk\tools e \sdk\platform-tools do Android Studio (ADT)
    -   Crie um nova variável de ambiente chamada **JAVA_HOME** e coloque o caminho para o JDK (*C:\Program Files\Java\jdk1.8.0_05*)
    -   Crie uma nova variável de ambiente chamada **ANT_HOME** e coloque o caminho da pasta ANT que você descompactou(*caso necessário*).

## 2. Fluxo de Trabalho

- **NPM**
É importante manter o NPM atualizado
    -   Instalar o módulo de atualização para windows:
```
    $npm install -g npm-windows-upgrade
```
-   Atualizar o NPM:
```
    $npm-windows-upgrade -p -v latest
```
Caso ocorra um erro: "Scripts cannot be executed on this system." abra o windows powershell como administrador e execute:
```
    $Set-ExecutionPolicy RemoteSigned
```

Informe S, atualize o NPM  "b" depois execute o item "1" e informe N.
**Observações**: É possível dar erros de plugs por falhas de conexao, insista varias vezes antes de optar por remover ou atualizar um plugin listado em erros.


## 3. Links
- **Guia Markdown GitHub**:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- http://rogerdudler.github.io/git-guide/index.pt_BR.html
- https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/
