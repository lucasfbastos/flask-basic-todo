comandos 

py -3 -m venv venv

venv\Scripts\Activate.ps1

pip install Flask

flask run

pip install flask-bootstrap

pip install flask-sqlalchemy flask-migrate

#após configuracao do db no app.py
flask db init   #para inicializar o db no projeto
flask db migrate -m "initial migration"    #para criar a migraçao
flask db upgrade        #para aplicar a migraçao