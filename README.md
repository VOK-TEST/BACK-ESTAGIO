# Teste Prático de Seleção para Estagiário Back-end (Laravel/PHP) 🔧

Olá candidato(a)!

Seja bem-vindo(a) ao desafio de desenvolvimento Back-end da VOKERÊ. Estamos em busca de um talento para a vaga de Estagiário de Back-end com conhecimentos em Laravel e PHP. Este desafio visa avaliar suas habilidades técnicas no desenvolvimento de aplicações web, bem como sua capacidade de trabalhar com banco de dados e integração com APIs externas.

## Tarefa: 📋

Desenvolva um sistema de gerenciamento de clientes com as seguintes funcionalidades principais:

### Funcionalidades Gerais
- **Autenticação e Autorização**: Registro e login de usuários.
- **Cadastro de Endereços**: Permitir o cadastro de endereços utilizando busca por CEP via API fornecida.
- **Listagem de Clientes**: Listar clientes com opções de busca por nome.

### Detalhamento das Funcionalidades

#### Dados dos Usuários
- Nome
- CPF (Deve validar CPF e garantir unicidade)
- Email
- Senha
- Data de Nascimento (Deve ser formatada)
- CEP (Consulta automática de endereço via API)
- Endereço Completo (Preenchido automaticamente pelo CEP)
- Foto (Opcional)

#### Funcionalidades por Nível de Acesso

**Cliente**
- Atualização de Dados Pessoais (incluindo foto)
- Visualização de Informações

**Gestor**
- Cadastro, Edição e Exclusão de Clientes
- Listagem de Clientes com Filtro por Nome e Data de Cadastro

**Administrador**
- Todas as funcionalidades de um Gestor
- Cadastro e Gestão de Endereços (com busca por CEP via API)

#### Listagem de Clientes
- Filtros: Nome e Data de Cadastro
- Colunas: ID, Nome, Data de Nascimento, Data de Cadastro

## Requisitos Técnicos: 🛠️

- Todos os métodos que utilizam banco de dados devem ser implementados utilizando Eloquent.
- A busca por CEP deve ser feita utilizando a API de exemplo: `https://viacep.com.br/ws/{cep}/json/`.
- As datas devem ser formatadas apropriadamente para exibição.

## Critérios de Avaliação: 📝

- Qualidade do código: organização, legibilidade e boas práticas.
- Funcionalidade: a aplicação deve cumprir os requisitos propostos.
- Integração com API: a busca por CEP deve funcionar corretamente.
- Uso de Eloquent: deve ser utilizado para todas as operações com banco de dados.

## Entrega: 📦

1. **Código Versionado**: O código deve ser versionado no GitHub ou BitBucket e o repositório compartilhado com o usuário `hedleydarsh`.
2. **Commits**: Realize commits separados para possibilitar o acompanhamento da evolução do projeto.
3. **Dump do Banco de Dados**: Inclua um dump do banco de dados, populado e com estrutura de criação de tabelas, índices, e relacionamentos (`BANCODEDADOS.sql`).

## Observações: 📌

Envie o teste finalizado para o email hedley.ti@gmail.com ou adicione o usuário `hedleydarsh` ao repositório.

Estamos ansiosos para ver o seu trabalho e desejamos boa sorte neste desafio!

Atenciosamente,  
VOKERÊ Equipe de Recrutamento
