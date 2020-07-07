# Ecoleta :recycle::put_litter_in_its_place:
 - Waste collection application created during Next Level Week # 01
 
## Learnings
 - NodeJS
 - Typescript
 - Database (KnexJS)
 - React
 - React Native
 - Expo
 - Data validation (Celebrate)
 - Image upload (Multer)
 
 ### Notes made during the NLW #01
  #### Conceitos
  - Cors: Define quais endereços externos terão acesso a aplicação.
  - JSX: Sintaxe de XML dentro do JavaScript.
  - Sempre que criamos um estado para um array ou objeto, é necessário informar manualmente o tipo da variável que vai ser armazenada ali. Representação Interface, number, etc.
  - Rota: Endereço completo da requisição 
  - Recurso: Qual entidade estamos acessando do sistema

  #### Verbos HTTP
  - GET: Buscar uma ou mais informações do back-end
  - POST: Criar uma nova informação no back-end 
  - PUT: Atualizar uma informação existente no back-end
  - DELETE: Remover uma informação do back-end

  - POST http://localhost:3333/users = Criar um usuário
  - GET http://localhost:3333/users = Listar usuários
  - GET http://localhost:3333/users/5 = Buscar dados do usuário com ID 5

  #### Parâmetros
  - Request Param: Parâmetros que vem na própria rota que identificam um recurso.
  - Query Param: Parâmetros que vem na própria rota geralmente opcionais para filtros, paginação, etc.
  - Request Body: Parâmetros para criação/atualização de informações.

  #### Banco de Dados e KnexJS
  - Migrations: "Histórico" do banco de dados. Controle da criação e/ou remoção de tabelas e dados.
  - Seeds: Usado quando precisamos que uma aplicação já suba com alguns valores "padrão", usamos as seeds para popular uma tabela com valores.

  #### Padrões
  - Padrões de Controller: index, show, create/store, update, delete/destroy.
