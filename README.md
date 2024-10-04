# ProjetoLanceArt

ProjetoLanceArt é uma aplicação desenvolvida para a disciplina de Programação Web 1 do Instituto Federal da Paraíba (IFPB). O projeto simula um e-commerce de galeria de arte, onde os usuários podem cadastrar, editar, remover e visualizar obras de arte, com a funcionalidade de autenticação de usuários. O sistema está dividido em dois principais componentes:

- **Frontend**: Desenvolvido em Angular, onde os usuários interagem com o sistema.
- **Backend**: Implementado em Java com Spring Boot, gerenciando a lógica de negócios e a persistência dos dados.

## Funcionalidades

### Autenticação de Usuários

- O sistema utiliza o **Firestore** como banco de dados para gerenciar a autenticação de usuários.

**Usuário:** - Nome - Email - Senha

### Cadastro de Artes

- Cada obra de arte cadastrada está associada ao ID do usuário autenticado, gerado pelo Firestore.
- As informações sobre as artes, como título, artista e preço, são salvas no banco de dados **PostgreSQL**, junto com o ID do usuário, simulando um relacionamento entre os dados da arte e o usuário que a cadastrou.

### Edição e Remoção de Artes

- Os usuários podem editar e remover suas próprias artes. As alterações são refletidas tanto no banco **PostgreSQL**.

### Listagem de Artes

- O sistema permite a visualização de todas as obras cadastradas, exibindo as informações da obra, bem como o autor (usuário) correspondente.

## Tecnologias Utilizadas

- **Angular**: Framework para desenvolvimento do frontend e gerenciamento de estado.
- **Angular Material**: Biblioteca de componentes UI para Angular, utilizada para criar uma interface amigável e responsiva.
- **Java com Spring Boot**: Usado para o backend, oferecendo serviços REST para o frontend e integração com o banco de dados.
- **Firestore**: Banco de dados NoSQL utilizado para simular a autenticação de usuários.
- **PostgreSQL**: Banco de dados relacional utilizado para armazenar as informações das obras de arte.

## Estrutura do Projeto

O projeto está dividido em dois principais repositórios:

1. **Frontend (Angular)**: Responsável pela interface com o usuário, permitindo cadastro, edição, remoção e listagem de artes.
2. **Backend (Spring Boot)**: API responsável pela comunicação entre o frontend e o banco de dados, gerenciando a lógica de negócio.

## Links dos Repositórios

- [Projeto_LanceArt](https://github.com/Laviniarm/Projeto_LanceArt)
- [APILanceArt](https://github.com/Laviniarm/APILanceArt)

## Alunos Envolvidos

- [Lavínia Rodrigues](https://github.com/Laviniarm)
- [Raiza Andrade](https://github.com/raizaft)
- [Rafael Limeira](https://github.com/buenorafa)
