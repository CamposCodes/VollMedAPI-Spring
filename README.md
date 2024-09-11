# API da Clínica Médica Voll Med

Este repositório contém a API da Clínica Médica Voll Med, projetada para gerenciar informações de pacientes, agendamentos e atendimentos. A API é construída com Spring Boot, seguindo as melhores práticas de desenvolvimento e utilizando diversas habilidades do framework para garantir eficiência e robustez.

## Protótipo no Figma
[(Protótipo Voll Med no Figma)](https://www.figma.com/proto/N4CgpJqsg7gjbKuDmra3EV/Voll.med?node-id=2-1007&t=hOpvWgX2VTtVJEJP-1)  
Como o foco é a aplicação Back-end API REST, esse Figma é usado como um guia da parte Front-end.

## Funcionalidades Principais
[(Trello Funcionalidades)](https://trello.com/invite/b/66d341b6a1ab9dc0fcbad89c/ATTI7c60420992a2f7f05e8991ff09893c9486064FC7/api-voll-med)
- Gerenciamento de pacientes:
    - Cadastrar pacientes
    - Visualizar pacientes
    - Atualizar informações de pacientes
    - Remover pacientes
- Gerenciamento de médicos:
    - Cadastrar médicos
    - Visualizar médicos
    - Atualizar informações de médicos
    - Remover médicos
- Agendamento de consultas

## Habilidades Spring Utilizadas

A API utiliza uma série de habilidades do Spring para garantir um desenvolvimento ágil e eficiente:

- **Spring Boot**: Facilita a configuração e o desenvolvimento da aplicação, permitindo a criação de serviços stand-alone com um servidor embutido.

- **Spring Data JPA**: Simplifica o acesso a dados e a implementação de operações CRUD, utilizando JPA para abstrair a lógica de acesso ao banco de dados.

- **Flyway**: Utilizado como ferramenta de migrações, permitindo versionar e gerenciar as alterações no esquema do banco de dados de forma eficiente.

- **Bean Validation**: Implementa validações nos dados recebidos nas requisições, garantindo a integridade e a qualidade das informações.

- **Pagination**: Implementa a paginação dos dados retornados pela API, melhorando a performance e a experiência do usuário ao lidar com grandes volumes de dados.
