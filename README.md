# Django JS Start

Projeto de start para o treinamento de Django + JS no WeHub.

## Como desenvolver?

1. Clone o repositório.
2. Crie um virtualenv com Python 3.6
3. Ative o virtualenv.
4. Instale as dependências
5. Configure a instância com o .env
6. Execute as migrações
7. Inicie o servidor

```console
git clone git@github.com:/klebercode/django-js-start.git myproject
cd myproject
python -m venv .venv
source .venv/bin/activate
pip install -r requirements-dev.txt
cp .env.sample .env
python manage.py migrate
python manage.py runserver
```
