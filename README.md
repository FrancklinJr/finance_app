# Aplicativo de Controle Financeiro Pessoal

Este projeto é um aplicativo de controle financeiro pessoal que permite aos usuários registrar e visualizar suas despesas e receitas. O aplicativo é implementado usando Flask para a interface web e SQLite para o banco de dados.

## Estrutura do Projeto

- `app.py`: Script principal que configura e inicia o servidor Flask.
- `models.py`: Contém os modelos do banco de dados definidos com SQLAlchemy.
- `templates/`
  - `index.html`: Interface para visualizar transações.
  - `add.html`: Interface para adicionar novas transações.
- `README.md`: Arquivo de documentação do projeto.

## Requisitos

- Python 3.6+
- Bibliotecas Python:
  - flask
  - sqlalchemy
  - flask_sqlalchemy

## Instalação

1. Clone o repositório para o seu ambiente local:

    ```bash
    git clone https://github.com/seu-usuario/finance_app.git
    cd finance_app
    ```

2. Crie um ambiente virtual e ative-o:

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:

    ```bash
    pip install flask sqlalchemy flask_sqlalchemy
    ```

## Como Executar

1. Execute o aplicativo Flask:

    ```bash
    python app.py
    ```

2. Abra o seu navegador e vá para `http://127.0.0.1:5000/` para acessar o aplicativo.

## Uso

- **Adicionar Transação**: Clique no botão "Adicionar Transação" na página inicial e preencha o formulário para adicionar uma nova transação.
- **Visualizar Transações**: A página inicial exibe uma tabela com todas as transações registradas.

## Estrutura dos Arquivos

finance_app/
│
├── venv/
├── app.py
├── models.py
├── templates/
│ ├── add.html
│ └── index.html
└── README.md