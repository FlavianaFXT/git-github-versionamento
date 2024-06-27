# git-github-versionamento

## INDICE 
### PROCESSO PARA SUBIR NO GITHUB
### Como criar meu Pull Request? 🤔
### checklist


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


# checklist

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Dentro da pasta "projeto-casa" criei uma pasta "meu-nome".
- [ ] Resolvi o exercício proposto no projeto dentro da minha pasta "meu-nome".
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
- [ ] Criei um Pull Request seguindo as orientaçoes que estao nesse [documento](https://github.com/mflilian/repo-example/blob/main/exercicios/projeto-casa/instrucoes-pull-request.md).
- [ ] Aguardei a prof mergiar

