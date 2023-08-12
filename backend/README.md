Данный проект создан для того, чтоб выставить фото своего котика в социальную сеть. 
 
Технологии: 
1. Python 3 
2. Django 3 
### Как запустить проект: 
 
 
Клонировать репозиторий и перейти в него в командной строке: 
 
``` 
git clone https://github.com/paltus3/kittygram_final.git 
``` 
 
``` 
cd kittygram 
``` 
 
Cоздать и активировать виртуальное окружение: 
 
``` 
python3 -m venv env 
``` 
 
``` 
source env/bin/activate 
``` 
 
Установить зависимости из файла requirements.txt: 
 
``` 
python3 -m pip install --upgrade pip 
``` 
 
``` 
pip install -r requirements.txt 
``` 
 
Выполнить миграции: 
 
``` 
python3 manage.py migrate 
``` 
 
Запустить проект: 
 
``` 
python3 manage.py runserver 
``` 
Автор paltus3 
https://github.com/paltus3 
