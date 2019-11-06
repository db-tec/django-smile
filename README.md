#django-smile<br>
Exemplo de um projeto simples com Django
<br>
#Como rodar o projeto
<br>
*Clone esse repositorio
<br>
*Crie um virtualenv com python3
<br>
*Ative o virtualenv
<br>
*Instale as dependências
<br>
*Rode as migrações
<br><br>

git clone https://github.com/db-tec/django-smile.git
<br>
cd django-smile
<br>
python3 -m venv .env
<br>
source .env/bin/activate
<br>
pip install -r requirements.txt
<br>
python contrib/env_gen.py
<br>
python manage.py migrate
<br>
python manage.py runserver
