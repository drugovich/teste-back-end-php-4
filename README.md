# Teste Back-end PHP

Desenvolver uma API RESTful utilizando Laravel ou Lumen.

## Cenário

Em nossa auto peças surgiu a demanda que nossos gerentes pudessem separar nossos clientes em grupos distintos. Nossos gerentes têm dois níveis.

## Requisitos

- Um cliente deve pertencer a apenas um grupo;
- Gerentes precisam estar autenticados;
- Gerentes de nível um pode apenas visualizar grupos, adicionar/remover clientes;
- Gerentes de nível dois é o único que pode criar, editar e excluir grupos;
- Não fazer "fork" do repositório;
- Ao finalizar, criar um repositório no github e mandar o link para o email <dep.web@drugovich.com.br>

### Modelos

- Clientes: Código Único, CNPJ, Nome, Data Fundação;
- Gerentes: Código Único, Nome, E-mail, Nível;
- Grupos: Código Único, Nome;
- Clientes e Gerentes podem ser populados automaticamente.

### Objetivo

Queremos endpoints para operar os grupos e visualizar os clientes de um grupo.

## Avaliação

Não se preocupe em terminar todo o teste. Procure finalizar cada requisito antes de seguir para o próximo.

### Será avaliado

- Padrões de projeto;
- Clean Code;
- Arquitetura da aplicação;
- Documentação;
- Modelagem do Bancos de Dados;
- Segurança;
- Tratamento de dados.

### Não será avaliado

- CRUD dos gerentes e clientes;
- Front-end.

### Diferencial

- Docker;
- Testes de integração;
- Testes unitários;
- Tratamento de erros.
