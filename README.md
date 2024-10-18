# SGP

## Descrição
SGP (Sistema de Gerenciamento de Projetos) é uma aplicação desenvolvida em Java e Angular que visa facilitar a gestão e acompanhamento de projetos.

## Estrutura do Projeto
O projeto é dividido em duas partes principais: a API backend, responsável pela lógica do sistema, e o cliente frontend, que oferece a interface de usuário.

### Estrutura do Backend
- **Controle**: Gerencia as requisições e lógica de negócios.
- **Modelo**: Define as entidades do sistema.
- **Repositório**: Interage com o banco de dados.

### Estrutura do Frontend
- **Componentes**: Contém a lógica e estrutura da interface de usuário.
- **Serviços**: Gerencia a comunicação com a API backend.
- **Rotas**: Define as diferentes páginas da aplicação.

## Tecnologias Utilizadas
- **Java**: Linguagem principal do backend.
- **Spring Boot**: Framework utilizado para construir a API.
- **SQLite/MySQL**: Sistema de gerenciamento de banco de dados.
- **Angular**: Framework para construção do frontend.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/francovinicius/SGP.git
2. Navegue até o diretório do projeto:
   ```bash
   cd SGP
3. Execute o backend com Maven:
   ```bash
   mvn spring-boot:run
4. Navegue até o diretório do frontend (caso esteja em um repositório separado) e execute:
   ```bash
   ng serve
