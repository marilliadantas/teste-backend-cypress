# Teste na camada backend

## Requisitos 📋
- [Node.js](https://nodejs.org/) - Certifique-se de que o Node.js esteja instalado em sua máquina.
- [Vs Code](https://code.visualstudio.com/download) - Certifique-se de que o Vs code ou a IDE que preferir esteja instalada em sua máquina. 

## Inicialize um projeto node 📥

Abra o terminal e navegue até o diretório onde deseja criar o projeto. Em seguida, execute o seguinte comando para iniciar um novo projeto Node.js:

    npm init -y

Este comando criará um arquivo package.json com as configurações padrão.


## Instale o Cypress 🤖
Para instalar uma versão mais recente: 

    npm install cypress --save-dev

Para instalar uma versão específica:

    npm install cypress@3.8.3 --save-dev

## Configure Scripts no package.json 

Abra o arquivo package.json e adicione os seguintes scripts para facilitar a execução do Cypress:

    "scripts": {
    "cypress:open": "cypress open",
    "cypress:run": "cypress run" }

## Abra o Cypress
Execute o seguinte comando para abrir o Cypress pela primeira vez. Isso criará a estrutura de diretórios necessária e abrirá a interface do usuário do Cypress.

    npm run cypress:open

## Escreva seus Testes

O Cypress cria uma estrutura de diretórios (cypress/integration) para armazenar seus testes. Escreva seus testes no formato .spec.js neste diretório.

## Execute os Testes
Você pode executar seus testes no terminal usando o seguinte comando:

    npm run cypress:run

## Recursos Adicionais
- [Documentação do Cypress](https://docs.cypress.io/guides/overview/why-cypress)
- [Exemplos de receitas](https://github.com/cypress-io/cypress-example-recipes)
- [Documentação HTTP request methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
- [Documentação HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)


<p align="center">Prontinho!!<br>Agora, você pode simplesmente apreciar a mágica do Cypress. 🚀😊</p>