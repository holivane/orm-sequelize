# ORM SEQUELIZE

## Descrição do Projeto
<p align="justify">Este projeto tem como função auxiliar na aprendizagem do funcionamento de uma ORM. <br>
Utiliza o Sequelize para fazer operações em banco de sem usar SQL. Organizado no modelo MVC</p>

### Ferramentas
- SQL (neste projeto foi utilizado o MySQL)
- Conhecimento de rotas
- MySQL Workbench
- Node
- NPM
- Postman (para testes)

##

### Passo a passo da preparação do ambiente
Criar pasta orm-sequelize:
Demtro da pasta criar o projeto usando npm com o comando abaixo
```bash
$ npm init -y
```
Baixar o express e o body-parser
```bash
$ npm i express body-parser 
```
Criar uma pasta api e dentro dela criar o arquivo 'index.js'. Dentro do package.json mudar o caminho da "main" para './api/index.js'. <br>
Baixar o nodemon para auxiliar na atualização de projeto sem precisar derrubar a aplicação para atualizar manualmente.

```bash
$ npm i --save-dev nodemon
```
Com isso, dentro do package.json pode ser adicionado o script:<br>
"start": "nodemon ./api/index.js" <br> <br>
Agora pra rodar a api é só digitar:<br>
npm run start
##
