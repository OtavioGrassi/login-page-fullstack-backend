# Login Page - Backend (Java)

## Imagens da Aplicação:

<img width="1920" height="919" alt="FireShot Capture 008 - LoginPageFrontend -  login-page-frontend-otaviograssi netlify app" src="https://github.com/user-attachments/assets/563357ec-fee5-499a-96e5-57d959f3d737" />
<img width="1920" height="919" alt="FireShot Capture 006 - LoginPageFrontend -  localhost" src="https://github.com/user-attachments/assets/5590dfff-a3ce-45ec-9136-3da6254f18d3" />


Este é o repositório do **Backend** da aplicação de Login com autenticação **Full Stack**. O projeto foi desenvolvido utilizando **Java**, **JWT** e **Bearer Token**.

## Funcionalidade

O backend é responsável por autenticar o usuário e gerar um **JWT (JSON Web Token)**, que será retornado ao frontend para ser utilizado em requisições subsequentes.

## Pré-requisitos

Antes de rodar o backend, certifique-se de ter as seguintes ferramentas instaladas:

- **Java JDK 11 ou superior** - [Baixar Java](https://adoptopenjdk.net/)
- **Maven** - [Baixar Maven](https://maven.apache.org/)
- **Git** - [Baixar Git](https://git-scm.com/)

## Clonando o repositório

Primeiro, clone este repositório para a sua máquina local:

git clone https://github.com/OtavioGrassi/login-page-fullstack-backend.git
cd login-page-fullstack-backend

## Instalação

Após clonar o repositório, certifique-se de que todas as dependências estão configuradas corretamente no Maven.

## Execução
Para rodar a aplicação, basta executar o comando Maven:

mvn spring-boot:run

O backend estará disponível no endpoint:

URL Base: http://localhost:8080

## Testes de API com Postman

O backend possui endpoints que podem ser testados via Postman.

POST /login - Realiza a autenticação do usuário e retorna um JWT.

GET /user-info - Requer o JWT para retornar informações do usuário autenticado.

Certifique-se de realizar os testes de autenticação usando o Postman com o token JWT gerado.

## Conectando o Backend com o Frontend

A aplicação Frontend interage com este backend via requisições HTTP. Para ver o repositório do Frontend, consulte o repositório [Frontend](https://github.com/OtavioGrassi/login-page-fullstack-frontend) para as instruções de configuração e execução do lado cliente.
