## Requisitos do modelo de API

Projeto desenvolvido durante a primeira parte do Curso Ignite node.js da Rocketseat. Este projeto tem como finalidade simular didaticamente os conceitos usados nas construções de API financeiras profissionais utilizando o Node.
<br> Foram usados vários conceitos de aplicação web: 
* Criação de um servidor http com uso da biblioteca express.
* Utilização da dependência de desenvolvimento nodemon.
* Construção de scrips de comandos no arquivo package.json.
* Familiarização com as rotas express.
* Utilização do software insomnia para testes do funcionamento das rotas.
* Utilização e familiarização com os status http code.
* Utilização dos métodos http: GET, DEL, PUT, POST.


### Abaixo segue o check list de requisitos e limitações do modelo de api.

## Requisitos da API
[x] Deve ser possível criar uma conta.<br>
[x] Deve ser possível buscar o extrato bancário do cliente.<br>
[x] Deve ser possível realizar um depósito.<br>
[x] Deve ser possível realizar um saque.<br>
[x] Deve ser possível buscar o extrato bancário do cliente por data.<br>
[x] Deve ser possível obter dados da conta do cliente.<br>
[x] Deve ser possível deletar uma conta.<br>
[x] Deve ser possível retornar o balance da conta.<br>


## Regras de negócio

[x] Não deve ser possível cadastrar uma conta com o cpf já existente.<br>
[x] Não deve ser possível fazer depósito em uma conta não existente.<br>
[x] Não deve ser possível buscar extrato em uma conta não existente.<br>
[x] Não deve ser possível excluir uma conta não existente.<br>
[x] Não deve ser possivel fazer saque quando o saldo for insuficiente.<br>
[x] Não deve ser possivel excluir uma conta não existente.<br>