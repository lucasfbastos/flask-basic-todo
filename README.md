Comandos utilizados para criar o projeto

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

Para instalar todos os requisitos e rodar o projeto:
pip install -r requirements.txt
flask run