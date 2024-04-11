# App

SIGESCON - Sistema de Gestão de Contratos

## RFs (Requisitos Funcionais)
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível o usuário administrador criar novos usuários;
- [ ] Deve ser possível a visualização dos contratos sem estar logado;
- [ ] Deve ser possível o usuário perfil (fiscal) visualizar todos os contratos que estão associados ao seu nome;
- [ ] Deve ser possível realizar alertas de vencimentos de contratos;
- [ ] Deve ser possível cadastrar um contrato;
- [ ] Deve ser possível associar um contrato para o usuário fiscal do contrato;

## RNs (Regras de Negócio)
- [ ] O usuário não pode ser cadastrado com um e-mail e matrícula duplicados;
- [ ] O contrato só pode ser cadastrado por administradores;
- [ ] Novos usuários só podem ser cadastrados por administradores;
- [ ] O contrato só pode ser associado para o usuário fiscal por administradores;

## RNFs (Requisitos Não-Funcionais)
- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco de dados PostgreSQL;
- [ ] Todas as listas de dados precisam estar paginadas  com 20 items por páginas;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);