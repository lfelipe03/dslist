# 🎮 DSList - Sistema de Coleção de Jogos

DSList é uma aplicação backend desenvolvida em Java com Spring Boot, que permite o gerenciamento de uma coleção de jogos. Ideal para quem deseja organizar, listar e manter o controle dos seus jogos favoritos de forma simples e eficiente.

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- Banco de Dados H2 

## 📦 Funcionalidades

- Cadastro de jogos com informações como título, gênero e posição na lista.
- Criação de múltiplas listas de jogos.
- Ordenação e movimentação de jogos dentro de listas.
- API REST com endpoints para integração com frontend ou sistemas externos.

## 📁 Estrutura do Projeto

src/
├── main/
│ ├── java/
│ │ └── com.example.dslist/ # Pacotes com controllers, services, entities e repositories
│ └── resources/
│ ├── application.properties # Configurações da aplicação
│ └── data.sql # Dados iniciais para popular o banco

## ▶️ Como Executar

1. Clone o repositório:
   git clone https://github.com/lfelipe03/dslist.git
   cd dslist
   
2.Execute a aplicação:

./mvnw spring-boot:run

3.Acesse a API em:

http://localhost:8080
