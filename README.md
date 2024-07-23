# Sistema de Gerenciamento de Clientes em Laravel

Este projeto é um sistema de gerenciamento de clientes construído com o framework Laravel. Ele permite que você visualize uma lista de clientes, adicione novos clientes e veja os detalhes de cada cliente. A interface é estilizada com TailwindCSS para garantir uma boa aparência e responsividade.

## Funcionalidades

- Listagem de clientes
- Criação de novos clientes
- Validação de formulários

## Requisitos

- PHP >= 7.3
- Composer
- Laravel 8.x
- Node.js (para compilar os assets do frontend)
- Banco de dados (MySQL, PostgreSQL, etc.)

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/Elieverton6/Gerenciamento_de_Clientes-Fundamentos_TreinaWeb
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```
3. Instale as dependências do PHP:
    ```bash
    composer install
    ```
4. Instale as dependências do Node.js:
    ```bash
    npm install
    ```
5. Compile os assets do frontend:
    ```bash
    npm run dev
    ```
6. Configure o arquivo `.env` com suas credenciais do banco de dados.
7. Execute as migrações do banco de dados:
    ```bash
    php artisan migrate
    ```
8. Inicie o servidor de desenvolvimento:
    ```bash
    php artisan serve
    ```

## Uso

### Listar Clientes
Acesse a URL `/clientes` para ver a lista de clientes cadastrados.

### Criar Cliente
Acesse a URL `/clientes/create` para acessar o formulário de criação de um novo cliente. Preencha os dados e envie o formulário para adicionar um novo cliente à lista.

## Estrutura do Projeto

- **Controllers**: Localizados em `app/Http/Controllers`, são responsáveis por lidar com as requisições HTTP e manipular os dados.
- **Models**: Localizados em `app/Models`, representam as tabelas do banco de dados.
- **Views**: Localizadas em `resources/views`, contêm os arquivos Blade que renderizam o HTML.
