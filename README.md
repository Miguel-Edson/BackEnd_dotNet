# Meus Projetos de Estudo .NET

Este repositório contém uma coleção de projetos desenvolvidos para aprofundar meus conhecimentos em desenvolvimento back-end com .NET e na integração com front-ends modernos.

---

### Estrutura do Repositório

O repositório é organizado em pastas, onde cada uma representa um projeto de estudo.

-   `/PizzaStore`: O projeto atual de API e front-end.
-   `/[NovoProjeto]`: Futuros projetos de estudo.

---

## Projeto 1: Pizza Store API & Frontend

Este é um projeto simples que demonstra o desenvolvimento de uma **Minimal API** em .NET 8.0 e um cliente front-end para consumi-la, utilizando Next.js.

### Tecnologias Utilizadas

**Back-end:**
-   **C#**
-   **.NET 8.0**
-   **ASP.NET Core** (Minimal APIs)
-   **Swagger** (para documentação da API)

**Front-end:**
-   **React**
-   **Next.js**
-   **TypeScript**
-   **Tailwind CSS**

### Funcionalidades da Aplicação

-   **CRUD de Pizzas:** Permite criar, ler, atualizar e deletar pizzas.
-   **Interface Reativa:** A lista de pizzas é atualizada em tempo real após cada ação.
-   **Busca por Nome:** Permite filtrar as pizzas listadas.

---

## Como Rodar o Projeto

Para executar a aplicação completa, você precisa rodar o back-end e o front-end em terminais separados.

### Pré-requisitos

Certifique-se de que você tem as seguintes ferramentas instaladas:
-   **.NET 8.0 SDK**
-   **Node.js & npm**

### 1. Rodar o Back-end (API)

Abra um terminal e navegue até a pasta do projeto back-end.

```bash
cd PizzaStore
```
Em seguida, execute o comando para rodar a API.
```bash
dotnet run
```
A API estará rodando em um endereço local, provavelmente em http://localhost:5289 (verifique a porta no seu terminal).

### 2. Rodar o Front-end (Next.js)
Abra um novo terminal e navegue até a pasta do projeto front-end.
```bash
cd pizza-store-frontend
```
Primeiro, instale as dependências.
```bash
npm install
```
Depois, inicie a aplicação.
```bash
npm run dev
```
A aplicação front-end estará disponível no seu navegador em http://localhost:3000.
