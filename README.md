# modern-data-stack

Tarefas:

Infraestrutura:

- Setup do ambiente de desenvolvimento (hardware, software - Linux, python, Docker, curl, pip, git, npm, etc....)
- Setar as permissões do Gitpod ao Repositorio no Github
- Subir o Airbyte via docker
- Subir o Airflow via docker
- Subir o Metabase via docker
- Criar o script de execução
- Testar a Execução
- Snowflake Data Warehouse:

    - Criar a conta no SnowFlake
    - Verificar a existência das tabelas
    - Obter os links de conexão e nome da conta

Extração:

- No Airbyte
    
    - Conectar com as origens baseadas nos Csvs
    - Criar as entidades no snowflake através do script base da documentação
    - Conectar o destino no snowflake
    - Criar as conexões do airbyte associando as origens ao destino
    - Testar as conexões

Preparação:

- No Airbyte(Destination Loading Method):
    
    - Local Staging (Ambiente de Desenvolvimento)
    - Cloud Staging (Ambiente de Produção)

Transformação: