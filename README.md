# django-simples

Projeto simples feito em Python utilizando Django.

## Como rodar o projeto?

* Clone esse repositório
* Crie um virtualenv com Python 3.x.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/JacksonOsvaldo/django-simples.git
cd django-simples
virtualenv -p python3 env
source env/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```