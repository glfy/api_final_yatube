## Как запустить проект

1. Клонировать репозиторий и перейти в него в командной строке:

   ```bash
   git clone git@github.com:glfy/api_final_yatube.git
   cd api_final_yatube
<<<<<<< Updated upstream
   
2. Cоздать и активировать виртуальное окружение:

   ```bash
   python3 -m venv env
   source env/bin/activate

3. Установить зависимости из файла requirements.txt:
   ```bash
   python3 -m pip install --upgrade pip
   pip install -r requirements.txt
   
4. Выполнить миграции:
   ```bash
   python3 manage.py migrate
   
5. Запустить проект:
=======

2. Cоздать и активировать виртуальное окружение:

   ```bash
   python3 -m venv env
   source env/bin/activate

3. Установить зависимости из файла requirements.txt:

   ```bash
   python3 -m pip install --upgrade pip
   pip install -r requirements.txt

4. Выполнить миграции:

   ```bash
   python3 manage.py migrate

5. Запустить проект:

>>>>>>> Stashed changes
   ```bash
   python3 manage.py runserver
