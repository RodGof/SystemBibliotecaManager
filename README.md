# SystemBibliotecaManager

## Descrição
Este projeto é um sistema de gerenciamento de biblioteca desenvolvido em Java com Spring Boot. Ele permite gerenciar livros, usuários e empréstimos de forma eficiente.

## Tecnologias Utilizadas
- **Java 11**: Linguagem de programação.
- **Spring Boot 2.4.2**: Framework principal.
- **Maven**: Gerenciamento de dependências e construção do projeto.
- **MySQL**: Banco de dados relacional para armazenamento de dados.
- **Thymeleaf**: Motor de templates para renderização de páginas HTML.

## Pré-requisitos
- **Java 11** instalado
- **Maven** instalado
- **MySQL** instalado e configurado

## Como Executar o Projeto
Clone o repositório:
   ```sh
   git clone https://github.com/usuario/repositorio.git
   cd repositorio

## Configure o banco de dados MySQL:

Crie um banco de dados chamado biblioteca.

Atualize as credenciais do banco de dados no arquivo src/main/resources/application.properties

## Execute o projeto usando Maven:
mvn spring-boot:run

## A aplicação estará disponível em:
http://localhost:8080

## Estrutura do Projeto
```
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── exemplo
│   │   │           └── biblioteca
│   │   │               └── Application.java
│   │   ├── resources
│   │   │   ├── application.properties
│   │   │   └── templates
│   │   │       ├── index.html
│   │   │       └── livros.html
│   ├── test
│   │   └── java
│   │       └── com
│   │           └── exemplo
│   │               └── biblioteca
│   │                   └── ApplicationTests.java

## Funcionalidades
Gerenciamento de livros (adicionar, editar, excluir)

Gerenciamento de usuários (adicionar, editar, excluir)

Empréstimo e devolução de livros

Relatórios de empréstimos

## Contribuição
Para contribuir com este projeto, siga os passos abaixo:

Faça um fork do projeto

Crie um branch para sua feature (git checkout -b feature/MinhaFeature)

Commit suas mudanças (git commit -m 'Adiciona MinhaFeature')

Faça o push para o branch (git push origin feature/MinhaFeature)

Abra um Pull Request

## Licença
Este projeto é licenciado sob a MIT License.
