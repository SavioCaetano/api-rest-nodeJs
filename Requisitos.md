## RFs (Requisitos funcionais)

- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas as transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

## RNs (Regras de negócio)

- [x] A transação pode ser do tipo crédito e somará ou valor total ou débito que subtrairá;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só pode visualizar transações que ele criou;

## RNFs (Requisitos não-funcionais)

- [x] Os dados da aplicação precisam estar persistidos em um banco Sqlite;
- [x] O usuário deve ser identificado por cookie;