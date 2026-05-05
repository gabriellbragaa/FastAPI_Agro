# FastAPI_CoopAgroBrasil

API para gerenciamento de Cooperativas com operações CRUD completas.

## Pré-requisitos

- Python 3.8+
- Git
- Pip
- PostgreSQL (ou outro banco de dados configurado)

## Configuração do Ambiente Linux

1. **Clone o repositório**:
  ```bash
   git clone [https://github.com/seu-usuario/seu-projeto.git](https://github.com/gabriellbragaa/FastAPI_CoopAgroBrasil.git)

2. **Configurando ambiente e rodando o FastAPI junto ao banco**

    cd FastAPI_Agrolink

-- Utilizei o Postgre

    # verificar o banco 
    sudo systemctl status postgresql

    # ativar o banco
    sudo systemctl start postgresql

    # para criar o ambiente virtual 
    python3 -m venv venv

    # para ativar 
    source venv/bin/activate

    # para desativar
    deactivate

    python -m uvicorn main:app --reload --port 8001 # para rodar o projeto


   
