# Friendly Dev Backend

Repositório do backend para o projeto **Friendly Dev**, construído com **Strapi**. Ele gerencia o conteúdo e fornece a API para a aplicação.

## 🚀 Tecnologias Utilizadas

- **[Strapi v5](https://strapi.io/)**: Headless CMS para gerenciamento de conteúdo.
- **PostgreSQL**: Banco de dados relacional (configurado como dependência).
- **Cloudinary**: Provedor para upload e gerenciamento de mídia.

## 🛠️ Instalação e Configuração

Siga os passos abaixo para rodar o projeto localmente:

1.  **Clone o repositório e acesse a pasta:**

    ```bash
    git clone <url-do-repositorio>
    cd friendly-dev-backend
    ```

2.  **Instale as dependências:**

    ```bash
    npm install

    # ou

    yarn install
    ```

3.  **Configure as variáveis de ambiente:**

    - Crie um arquivo `.env` na raiz do projeto.
    - Copie o conteúdo de `.env.example` para o `.env`.
    - Preencha as chaves necessárias (chaves de banco de dados, chaves do Cloudinary, secrets do Strapi).

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run develop
    # ou
    yarn develop
    ```

O painel administrativo estará disponível em: [http://localhost:1337/admin](http://localhost:1337/admin)
A API estará disponível em: [http://localhost:1337](http://localhost:1337)

## 📜 Scripts Disponíveis

- `npm run develop`: Inicia o servidor em modo de desenvolvimento (com auto-reload).
- `npm run start`: Inicia o servidor em modo de produção.
- `npm run build`: Constrói o painel administrativo.
- `npm run deploy`: Script para deploy (se configurado).

## 📂 Estrutura Importante

- `/config`: Configurações do servidor, banco de dados e plugins.
- `/src/api`: Definições das APIs (Controllers, Services, Routes, Models).
- `/public`: Arquivos estáticos públicos.
