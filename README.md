# Gerenciador de Tarefas

#### Você precisa criar um banco no mysql
##### user root
##### pass root
```
CREATE DATABASE gerenciador_tarefas;
```

#### Ou você pode mudar o settings.py

```
source ../venv/bin/activate

python manage.py migrate

python manage.py makemigrations

```
