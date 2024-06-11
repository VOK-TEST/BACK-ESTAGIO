# Teste Prático de Seleção para Estagiário Back-end - VOKERÊ

## Objetivo
O objetivo deste teste é identificar como você realiza sua codificação, lógica de programação e criatividade para resolver problemas do dia a dia.

## Requisitos do Projeto

1. **Framework**: Última versão do Laravel (https://laravel.com/)
2. **Banco de Dados**: Última versão do MySQL (Banco com Engine INNODB e índices corretamente relacionados). Utilização das Migrations do Laravel é um diferencial!

## Escopo do Sistema

Você deverá desenvolver um sistema de gerenciamento de clientes com as seguintes funcionalidades:

### Funcionalidades Gerais
- **Autenticação e Autorização**: Registro e login de usuários.
- **Cadastro de Endereços**: Permitir o cadastro de endereços utilizando busca por CEP via API fornecida.
- **Listagem de Clientes**: Listar clientes com opções de busca por nome.

## Detalhamento das Funcionalidades

### Dados dos Usuários
- Nome
- CPF (Deve validar CPF e garantir unicidade)
- Email
- Senha
- Data de Nascimento (Deve ser formatada)
- CEP (Consulta automática de endereço via API)
- Endereço Completo (Preenchido automaticamente pelo CEP)

### Funcionalidades
- Atualização de Dados Pessoais
- Cadastro, Edição e Exclusão de Clientes
- Listagem de Clientes com Filtro por Nome

## Requisitos Técnicos

- Todos os métodos que utilizam banco de dados devem ser implementados utilizando Eloquent.
- A busca por CEP deve ser feita utilizando a API de exemplo: `https://viacep.com.br/ws/{cep}/json/`.
- As datas devem ser formatadas apropriadamente para exibição.

## Entrega

1. **Código Versionado**: O código deve ser versionado no GitHub ou BitBucket e o repositório compartilhado com o usuário `hedleydarsh`.
2. **Commits**: Commits separados para possibilitar o acompanhamento da evolução do projeto.
3. **Dump do Banco de Dados**: Um dump do banco de dados, populado e com estrutura de criação de tabelas, índices, e relacionamentos (`BANCODEDADOS.sql`).

## Considerações Finais

Envie o teste finalizado para o email hedley.ti@gmail.com ou adicione o usuário `hedleydarsh` ao repositório.
