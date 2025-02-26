# Airflow local

## Sobre
O Airflow é uma plataform open-source para criar, agendar e monitorar workflows.

Este projeto tem o objetivo de facilitar a execução dos componentes do Airflow, como webserver, triggerer e  worker, em um ambiente local com docker e docker-compose.

## Requisitos
1. Instalar o Docker Community Edition(CE) - https://docs.docker.com/engine/installation/
2. Instalar o Docker Compose na versão 2.14.0 ou mais recente - https://docs.docker.com/compose/install/

## Inicialização
1. Inicie o Docker na sua estação local
2. Inicie o compose conforme abaixo:
    ```
    # docker-compose up
    ```

## Acesso
Após os passos de inicialização serem executados, a interface web do airflow ficará disponível no endereço http://localhost:8080 e pode ser acessada com o usuário e senha padrão airflow/airflow.