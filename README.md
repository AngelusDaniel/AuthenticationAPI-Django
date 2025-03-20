# Django Auth API

Este projeto é uma API de autenticação baseada em Django. Ele fornece endpoints para registro de usuários, login e gerenciamento de tokens.

## Funcionalidades

- Registro de usuários
- Login de usuários
- Autenticação baseada em token
- Redefinição de senha

## Requisitos

- Python 3.8+
- Django 3.2+
- djangorestframework 3.12+

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seuusuario/Django_Auth_API.git
    cd Django_Auth_API
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale os pacotes necessários:
    ```bash
    pip install -r requirements.txt
    ```

4. Aplique as migrações:
    ```bash
    python manage.py migrate
    ```

5. Execute o servidor de desenvolvimento:
    ```bash
    python manage.py runserver
    ```

## Uso

- Registrar um novo usuário:
    ```
    POST /api/register/
    ```

- Login de um usuário:
    ```
    POST /api/login/
    ```

- Obter detalhes do usuário:
    ```
    GET /api/user/
    ```
