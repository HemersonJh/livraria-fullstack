# Livraria CRUD – Angular + Spring Boot

Este é um sistema de cadastro de Livros, Autores e Usuários, com autenticação, desenvolvido em Angular (frontend) e Spring Boot (backend).

---

## **Como rodar o projeto**

### **Pré-requisitos**

- Java 17+ instalado
- Node.js e Angular CLI instalados
- Banco de dados configurado (MySQL ou H2)
- (Opcional) Maven para rodar o backend

### **Backend (Spring Boot)**

1. Acesse a pasta do backend:
    ```sh
    cd spring_livraria  # ou o nome do seu projeto backend
    ```
2. Instale as dependências e rode:
    ```sh
    mvn spring-boot:run
    ```
3. O backend ficará disponível em: [http://localhost:8080](http://localhost:8080)

### **Frontend (Angular)**

1. Acesse a pasta do frontend:
    ```sh
    cd frontend-livraria
    ```
2. Instale as dependências:
    ```sh
    npm install
    ```
3. Rode o servidor Angular:
    ```sh
    ng serve
    ```
4. O frontend ficará disponível em: [http://localhost:4200](http://localhost:4200)

---

## **Login de acesso**

> **Usuário de exemplo:**
> - **E-mail:** admin@email.com
> - **Senha:** 1234

*(Se quiser cadastrar mais usuários, utilize o CRUD de usuários no sistema ou insira diretamente no banco.)*

---

## **Funcionalidades**

- Login e logout de usuário
- CRUD completo de Usuários
- CRUD completo de Autores
- CRUD completo de Livros (com seleção do autor)
- Rotas protegidas (acesso só após login)
- Navegação simples pelo header

---

## **Documentação básica das telas**

- **Login:** autenticação do usuário.
- **Usuários:** listar, cadastrar, editar, excluir usuários.
- **Autores:** listar, cadastrar, editar, excluir autores.
- **Livros:** listar, cadastrar, editar, excluir livros (escolha o autor no cadastro).
- **Header:** barra de navegação com botão de logout.

---

## **Observações**

- O sistema só permite acesso às funcionalidades após login.
- Após o login, você será redirecionado automaticamente para a tela de Livros.
- Caso queira testar com outro usuário, cadastre pelo CRUD de Usuários.
- O sistema pode ser facilmente adaptado para utilizar JWT no futuro.

---

## **Contato**

Qualquer dúvida, entre em contato:  
Hemerson Jhonatan  
