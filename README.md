# Agentics Workflow

Este projeto é uma implementação de um fluxo de trabalho de agentes para geração e revisão de relatórios de negócios.

## Estrutura do Projeto

- src/ - Código fonte
- tests/ - Testes
- Dockerfile - Configuração do Docker
- docker-compose.yml - Orquestração dos contêineres

## Estrutura do Diretório 
agentics-workflow/
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── README.md
├── src/
│ ├── init.py
│ ├── main.py
│ ├── state.py
│ ├── nodes.py
│ ├── prompts.py
│ ├── tavily_client.py
│ ├── document_reader.py
│ └── utils.py
└── tests/
    ├── init.py
    └── test_nodes.py


## Como Rodar

1. **Construa a Imagem Docker**
    ```bash
    docker-compose build
    ```
2. **Inicie o Contêiner**
    ```bash
    docker-compose up
    ```

## Como Contribuir

1. **Clone o Repositório**
    ```bash
    git clone https://github.com/yourusername/agentics-workflow.git
    ```
2. **Crie uma Branch**
    ```bash
    git checkout -b nome-da-branch
    ```
3. **Faça as Alterações e Commit**
    ```bash
    git add .
    git commit -m "Descrição das alterações"
    ```
4. **Envie para o Repositório**
    ```bash
    git push origin nome-da-branch
    ```

