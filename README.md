# Agente OpenAI Treino

Este projeto é um agente simples de perguntas e respostas utilizando a API da OpenAI e Streamlit para a interface de usuário.

## Pré-requisitos

- Docker
- Docker Compose

## Configuração

1. Clone o repositório:

    ```sh
    git clone https://github.com/seu-usuario/agente-openai-treino.git
    cd agente-openai-treino
    ```

2. Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API da OpenAI:

    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

## Construção e Execução

1. Construa e inicie o contêiner Docker usando Docker Compose:

    ```sh
    docker compose up --build
    ```

2. Acesse a aplicação no seu navegador em `http://localhost:8501`.

## Uso

Digite sua pergunta na caixa de texto e clique em "Enviar". O agente responderá utilizando o modelo GPT-4 da OpenAI.

## Estrutura do Projeto

- `Dockerfile`: Define a imagem Docker para o projeto.
- `compose.yaml`: Configuração do Docker Compose.
- `requirements.txt`: Lista de dependências do Python.
- `app.py`: Código principal da aplicação Streamlit.
- `README.md`: Este arquivo de documentação.

