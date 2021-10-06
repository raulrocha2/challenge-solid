## Desafio Ignit Trilha Node.js chapter 2 
***
## Desafio SOLID e Swagger - Sobre o desafio
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no Node.js!
Essa será uma aplicação de listagem e cadastro de usuários. Para que a listagem de usuários funcione, o usuário que solicita a listagem deve ser um admin. Realize a documentação das rotas com o Swagger

### Rotas da aplicação:
- POST/users: A rota deve receber name, e email dentro do corpo da requisição para que seja possível cadastrar um usuário;
- PATCH /users/:user_id/admin: A rota deve receber, nos parâmetros da rota, o id de um usuário e transformar esse usuário em admin;
- GET /users/:user_id: A rota deve receber, nos parâmetros da rota, o id de um usuário e devolver as informações do usuário encontrado pelo corpo da resposta;
- GET /users: A rota deve receber, pelo header da requisição, uma propriedade user_id contendo o id do usuário e retornar uma lista com todos os usuários cadastrados. O id deverá ser usado para validar se o usuário que está solicitando a listagem é um admin. O retorno da lista deve ser feito apenas se o usuário for admin; 

Específicação dos testes
Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.