# ![git logo](../imgs/Git.png) Workflow

![](https://img.shields.io/badge/documenta%C3%A7%C3%A3o-em%20desenvolvimento-informational.svg)
<br/>
## Conteúdo
1. [Repositórios](#reposit-rios)<br/>
 *  [Definição](#defini-o)<br/>
 *  [Ciclo de projeto](#ciclo-de-projeto)<br/>
 *  [Setup inicial](#setup-inicial)<br/>
2. [git status]()<br/>
3. [git commit](#git-commit)<br/>
4. [git push]()<br/>
5. [git pull]()<br/>
6. [pull request]()<br/>

## Repositórios

### Definição
Repositórios são pastas que possuem gerenciamento de versão através do git, ou seja, diretórios com git inicializado.

### Setup inicial
No início de cada projeto, há tarefas importantíssimas a serem feitas 

### Ciclo de projeto
<p align="center">
   <img src="../imgs/repos.png">
</p>

<p align="center">
    O fluxo do código nos repositórios é o mesmo em todo projeto.
</p>

- Primeiramente, os arquivos alterados são transferidos da máquina local do desenvolvedor(a) ao seu repositório remoto pelo comando [git push](#git-push). (seu repositório remoto fica localizado em https://github.com/{username}/{projeto})
- Após isso, o desenvolvedor precisa criar um [pull request](#pull-request), referenciando **infojr/{projeto} branch ⬅ username/{projeto} branch**, como exibido na imagem abaixo, para que a alteração existente em seu repositório remoto seja transferida também ao repositório central de forma com que todos os membros consigam baixar a atualização em seus repositórios locais.
<p align="center">
   <img src="../imgs/branchtobranch.png">
</p>
- Com o repositório central atualizado, qualquer membro pode baixar as atualizações com o comando [git pull](#git-pull) e continuar o desenvolvimento do projeto e dando início a esse ciclo novamente.


## git commit

