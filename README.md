Passsos para criação do projeto Django

1. django-admin startproject usuario

2. Acessar a pasta do projeto:
	cd usuario

3. Verificar se esta na pasta que possui o arquivo manage.py utilizando o comando DIR que irá listar os arquivos do diretório

4. Criar o app Login
	python manage.py startapp Login

5. Abrir o o projeto no Visual Studio

6. Abrir o arquivo Settings e adicionar no final da lista INSTALLED_APPS o APP Login
	INSTALLED_APPS = [
    		'django.contrib.admin',
		'django.contrib.auth',
    		'django.contrib.contenttypes',
    		'django.contrib.sessions',
    		'django.contrib.messages',
    		'django.contrib.staticfiles',
    		'Login.apps.LoginConfig',
		]

7. No arquivo Settings, modificar o Time_Zone
	TIME_ZONE = 'America/Fortaleza'

8. Abrir o arquivo URLs.py e copiar o conteúdo do mesmo arquivo que está no GitHub.

9. Criar o arquivo urls.py dentro da pasta do APP Login e copiar o conteúdo do mesmo arquivo que está no GitHub

10. Abrir o arquivo Views.py e subtituir o seu conteúdo pelo que está no mesmo arquivo no GitHub

11. Dentro do diretório(pasta) Login, criar um diretório(pasta) chamada templates.

12. Dentro do diretório templates, criar o arquivo index.html

13. Abrir o arquivo index.html e copiar o conteúdo do mesmo arquivo presente no Github.

14. No terminal do Visual Studio, executar o comando python manage.py runserver.

15. Clicar no endereço e verificar se a pagina Login será exibida.
	
