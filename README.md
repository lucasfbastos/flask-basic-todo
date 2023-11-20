Comandos utilizados para criar o projeto:

Criação de ambiente virtual: py -3 -m venv venv

Ativação do ambiente virtual: venv\Scripts\Activate.ps1

Instalação do flask: pip install Flask

Execução do servidor de desenvolvinmento: flask run --reload

Instalação do bootstrap: pip install flask-bootstrap

Instalação do SQLAlchemy e do wrapper Alembic: pip install flask-sqlalchemy flask-migrate

Após configuracao do db no app.py:
Para inicializar o db no projeto: flask db init  
Para criar a migraçao: flask db migrate -m "initial migration"    
Para aplicar a migraçao: flask db upgrade    


Para instalar todos os requisitos e rodar o projeto em uma determinada pasta:

git clone https://github.com/lucasfbastos/flask-basic-todo.git

cd flask-basic-todo

py -3 -m venv venv

venv\Scripts\Activate.ps1

pip install -r requirements.txt

flask run --reload