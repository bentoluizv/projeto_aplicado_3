# PROJETO APLICADO 3

Esse é um projeto desenvolvido para o 4º semestre do curso de Análise e Desenvolvimento de Sistemas no SENAI SC. O objetivo é criar uma API utilizando FastAPI, PostgreSQL, Redis e Devbox para isolar o ambiente de desenvolvimento. A aplicação visa demonstrar a integração de diferentes tecnologias e boas práticas no desenvolvimento de software.

## Instalando Ambiente

1. Clone o repositório:

    ```sh
    git clone <URL_DO_REPOSITORIO>
    ```

2. Instale as dependências da infra com o Devbox:

    ```sh
    devbox install
    ```

3. Entre no shell do ambiente de desenvolvimento com Devbox:

    ```sh
    devbox shell
    ```

4. Inicie os serviços com Devbox:

    ```sh
    devbox services up
    ```

5. Inicie o banco de dados com o comando:

    ```sh
    initdb
    ```

6. Por padrão, é criado um usuário com o nome do usuário do sistema, porém você pode criar outro com o comando:

    ```sh
    createuser --interactive
    ```

7. Acesse o PostgreSQL com:

    ```sh
    psql -U <usuario> postgres
    ```

8. Altere sua senha para acessar o banco de dados com o comando:

    ```sql
    ALTER USER <usuario> WITH PASSWORD '<senha>';
    ```

9. Conecte-se ao banco através da string de conexão:

    ```sh
    postgresql://[usuário]:[sua_senha]@localhost:5432/postgres
    ```
