## Descrição do Projeto
Este projeto é uma API REST desenvolvida com Node.js, Express e Sequelize, que permite a gestão de um conjunto de recursos, como itens ou produtos. A API implementa funcionalidades de CRUD (Criar, Ler, Atualizar e Deletar) e inclui a técnica de soft delete, que permite a exclusão lógica dos registros, mantendo-os no banco de dados para futuras referências. O objetivo é fornecer uma interface robusta e eficiente para manipulação de dados, facilitando a integração com aplicações front-end e outros serviços.


## Tecnologias Utilizadas
- Node.js: Ambiente de execução para JavaScript no lado do servidor.
- Express: Framework para construir APIs de forma rápida e fácil.
- Sequelize: ORM para Node.js que facilita a interação com bancos de dados SQL.

## Funcionalidades
- CRUD Completo: Permite criar, ler, atualizar e deletar registros.
- Soft Delete: Implementação de exclusão lógica, onde os registros não são removidos do banco, mas marcados como inativos.
- Consultas Avançadas: Utilização de métodos do Sequelize para realizar consultas específicas.
