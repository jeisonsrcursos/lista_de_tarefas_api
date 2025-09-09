# Comandos Python & DJango:

## Criação do ambiente de desenvolvimento python:

 ```bash
 python3 -m venv venv
 ```

## Inicializar o ambiente criado:

 ```bash
 source venv/bin/activate
 ```

## Instalação do Django e seus complementos:

 ```bash
 pip install django pillow
 ```

## Testando a verificação da instlação do django:

 ```bash
 django-admin --version
 ```

## Instalação do Django Rest Framework:

```bash
pip install djangorestframework
```

## Criação do arquivo de "requisitos" do projeto:

```bash
pip freeze >> requirements.txt
```

## Criação do projeto:

```bash
django-admin startproject [nome] .
```
 - Obs.: o ponto indica que o projeto deve ser criado na pasta corrente,
   e não criar uma subpasta com o nome do projeto e coloca-lá como o projeto.

## Executando o servidor "django" para testes:

```bash
python manage.py runserver
```

## Criação do super usuário:

```bash
python manage.py createsuperuser [enter]
```

## Criando um APP:

```bash
python manage.py startapp [nome]
```

## Configure o Projeto e o APP.

## Criação das migrações:

```bash
python manage.py makemigrations
```

## Aplicando as migrações:

```bash
python manage.py migrate
```

## Registrando um "model" em "app/admin.py":

```bash
admin.site.register(model)
```