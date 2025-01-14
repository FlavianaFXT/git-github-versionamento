# git-github-versionamento
Resumo de conteudo proveniente dos cursos realizados nas seguintes comunidades:
![image](https://github.com/FlavianaFXT/git-github-versionamento/assets/113718720/a03f44e1-94a3-4472-aeb4-1808056ab088)


## INDICE 
### ENTENDENDO O QUE È O GIT E SUA IMPROTÂNCIA
### PROCESSO PARA SUBIR NO GITHUB
### Como criar meu Pull Request? 🤔
### checklist

# ENTENDENDO O QUE È O GIT E SUA IMPORTÂNCIA

Git --> Open source, criado em 2005 por Linus Torvalds, software colaborativo

## Navegação via commad line interface (CLI) e instalação

### Comandos Básicos para um bom desempenho no terminal

| windows | Unix |   |
| cd  |  cd |   |
| dir | ls |   |
| mkdir  | mkdir |  cria uma pasta |
|  del/rmdir |  rm -rf |   |
| ls | dir + Enter  |   traz uma lista de diretórios |
| cd/ |  | leva para a base do diretório |
| cd:: |   |  volta para o diretório C: |
| cls |   | limpar a tela |
| tab |   |   autocompleta |
| cd NOME DA PASTA + ENTER |   | Acessa a pasta |
| del NOME DA PASTA |   |  deleta o que tem na pasta |
| rmdir NOME DA PASTA /S /Q |   |  deleta a pasta |


### Realizando a instalação do Git

1) baixa o Git no [site](https://git-scm.com/downloads) e isntala no computador


# COMO FAZER FORK DE UM PORJETO NO GITHUB

* Fork esse repositório 
* Clique no botão "code"
* Copie o endereço do repositório
* Abra o seu Gitbash

* Entre no seu desktop:
```
     cd desktop
```
* Clone o fork na sua máquina: basta abrir o seu terminal e digitar:
  
```
     git clone url-do-seu-repositorio-forkado
```
* Digite o comando  ls para encontrar o seu repositório:
  
```
     ls
```
* Copie o nome do repositorio e entre na pasta clonada:
  
```
     cd on23-tet-s2-html-css
```
* Crie uma branch com o seu nome:
  
```
     git checkout -b seu-nome
```
* Digite o comando para abrir o projeto no vscode:
  
```
     code .
```



#  PROCESSO PARA SUBIR NO GITHUB:

* Adicione as mudanças. (git add . para adicionar todos os arquivos, ou git add nome_do_arquivo para adicionar um arquivo específico)
* Commite a cada mudança significativa ou na finalização do exercício (git commit -m "Mensagem do commit")
* De Push nos commits da branch de voces (git push origin nome-da-branch)
* Crie um Pull Request seguindo as orientações que estão nesse documento. (Aqui: https://github.com/mflilian/onX-tet-sX-temaX/blob/main/exercicios/projeto-casa/instrucoes-pull-request.md)


# Como criar meu Pull Request? 🤔

Olá, meninas! <br>
O checklist da atividade ta todo preenchido? Entao agora tá na hora de fazer nosso pull request para o repositório original. <br>
Você deverá navegar até o seu repositório onde você fez o fork e pressionar o botão “New pull request” no lado esquerdo da página. <br> <br>
![alt](https://assets.digitalocean.com/articles/eng_python/PullRequest/PRButton.png)

Você poderá modificar a branch na próxima tela. 

Depois de ter escolhido a branch main do repositório original no lado esquerdo, e a nova-branch do seu fork do lado direito, você deve ver uma tela assim:

![alt](https://assets.digitalocean.com/articles/eng_python/PullRequest/PullRequest.png)
<br> <br>
O GitHub vai lhe alertar de que é possível mesclar as duas branches porque não há código concorrente. Você deve adicionar um título, e um comentário descrevendo o seu PR. <br> <br>
DICAS: <br>
1. Você pode seguir esse modelo para o título do seu PR: 
``` 
Nome da Atividade - Seu nome. 
```
2. Você pode seguir esse modelo para a descrição do seu PR: 
``` 
O que?
Resolução dos exercícios de lógica.

Como?
* Adicionei um arquivo para resolver a atividade 1 utilizando os métodos slice e split;
* Adicionei casos de testes unitários para cada um dos exercícios utilizando jest;
* Outro ponto que você queira adicionar.
```
Feito isso, é so clicar em “Create pull request”. <br> <br>


# LINKS ÚTEIS


[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)


