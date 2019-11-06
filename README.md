# django-smile
Exemplo de um projeto simples com Django

##Como rodar o projeto
*Clone esse repositorio
*Crie um virtualenv com python3
*Ative o virtualenv
*Instale as dependências
*Rode as migrações

git clone https://github.com/db-tec/django-smile.git
cd django-smile
python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
python manage.py runserver