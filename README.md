# amigosecreto-back-end
API - Sorteio de Amigo Secreto com envio de e-mail e CRUD completo, utilizando NodeJS, Express, Sequelize e MySQL.

CRUD Completo - Amigo Secreto com Sorteio e Envio de E-mail
---------------------------------------------------
API em NodeJS com Express, Sequelize(ORM) e MySQL.
---------------------------------------------------

Passos realizados no terminal e configurações INICIAIS do projeto:

npm install para instalar as dependências.

npm start para rodar a API.

---------------------------------------------------
Utilizando o SEQUELIZE:
---------------------------------------------------

Criando a tabela Pessoas referente ao modelo.
npx sequelize-cli db:migrate

Criando um arquivo Seed, para alimentar o banco com usuários para testes durante o desenvolvimento.
npx sequelize-cli seed:generate --name demo-pessoa

Após alimentar o arquivo de seed gerado, executar o comando para criar os dados na tabela do banco.
npx sequelize-cli db:seed:all

**
Caso tenha rodado o comando de migração antes de fazer alguma alteração importante em algum modelo
 e agora as tabelas do banco não estão como deveriam, através do comando a seguir você pode voltar o banco a um
estado anterior à última alteração.
npx sequelize-cli db:migrate:undo

Para desfazer o Seed:
npx sequelize db:seed:undo
**

