# Projeto em django
Curso da Alura usando django, com fco em template

## Ambiente virtual

Instalar
```
python -m venv .venv
```

Ativar
```
.\.venv\Scripts\activate
```

Criar requirements.txt e atualizar o mesmo
```
pip freeze > requirements.txt
```

Desativar
```
deactivate
```

## Comandos Django
Instalar django
```
pip install django
```

Iniciar projeto - configurações do app
```
django-admin startproject setup .
```

Iniciar app
```
python manage.py startapp nome
```

Rodar o projeto
```
python manage.py runserver
```

Guardar a secret key
```
pip install python-dotenv
```

Manipular os arquivos estáticos
```
python manage.py collectstatic
```

## Gitignore

Tem um site que permite criar gitignore baseado no programa que você vai utilizar, ele já ignora arquivos que por boa prática, não é bom mandar para o github. O link dele é https://www.toptal.com/developers/gitignore

