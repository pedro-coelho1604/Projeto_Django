# Projto em django
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

Instalar django
```
pip install django
```

# Comandos Django

Iniciar projeto 
```
django-admin startproject setup .
```

Rodar o projeto
```
python manage.py runserver
```

Guardar a secret key
```
pip install python-dotenv
