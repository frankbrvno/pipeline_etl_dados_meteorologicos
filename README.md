# 🌤️ Pipeline ETL - Dados Climáticos de São Paulo

> Pipeline ETL automatizado para coleta, transformação e armazenamento de dados meteorológicos em tempo real da cidade de São Paulo.
 O pipeline coleta dados meteorológicos da API OpenWeatherMap a cada hora, transforma os dados para um formato estruturado e os armazena em um banco de dados PostgreSQL para análises futuras.
>
> ## 🛠️ Stack Tecnológica

### Core
- **Python 3.14+** - Linguagem principal
- **Apache Airflow 3.1.7** - Orquestração do pipeline
- **PostgreSQL 14** - Banco de dados relacional
- **Docker & Docker Compose** - Containerização

### Bibliotecas Python
- **pandas** - Manipulação e transformação de dados
- **requests** - Requisições HTTP para a API
- **SQLAlchemy** - ORM para interação com o banco de dados
- **psycopg2** - Driver PostgreSQL
- **python-dotenv** - Gerenciamento de variáveis de ambiente

### Outras Ferramentas
- **Redis** - Message broker para Celery
- **Jupyter Notebook** - Análise exploratória de dados
- **UV** - Gerenciador de pacotes Python rápido
