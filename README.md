# GoBarber

Aplicação básica para agendamento de barbeiro, elaborada no segundo módulo sobre NodeJS, do bootcamp da Rocketseat.

Este projeto foi criado para aprender sobre o funcionamento das rotas de uma aplicação, e também para entender a importância de separar o projeto utilizando o padrão [MVC](https://www.devmedia.com.br/introducao-ao-padrao-mvc/29308).
Para a renderização das views, foi utilizado o [Nunjucks](https://mozilla.github.io/nunjucks/).

A etapa de autenticação de usuários foi criada usando-se o [Sequelize](http://docs.sequelizejs.com/), que facilita muito esta etapa.

## Instalação

Recomendo que seja utilizado o [Yarn](https://yarnpkg.com/pt-BR/) para configurar o projeto. Com ele, basta executar os passos abaixo:

- Instalar o [MySQL](https://dev.mysql.com/downloads/)
- Criar uma database com nome "gonodemodulo2"
- Dentro do diretório do projeto, executar o comando "yarn install" no terminal para que o Yarn configure todas as dependencias do projeto
- Dentro do arquivo "\src\config\database.js", informar o seu usuário e senha do banco de dados
- Em seguida, executar o comando "npx sequelize db:migrate" para que o Sequelize crie as tabelas necessárias dentro do database
- Iniciar a aplicação com o comando "yarn start"
- Acessa-lo pelo browser no caminho: http://localhost:3000/
