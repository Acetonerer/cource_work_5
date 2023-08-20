# cource_work_5
В рамках проекта необходимо получить данные о компаниях и вакансиях с сайта hh.ru, 
спроектировать таблицы в БД PostgreSQL и загрузить полученные данные в созданные таблицы.
Установка: Перед началом установки убедитесь, 
что у вас установлен Python 3.11 и Virtualenv.
Активируйте виртуальное окружение, выполнив в консоли venv/Scripts/activate.bat
Платформа для сбора вакансий: 
hh.ru (ссылка на API: https://github.com/hhru/api/blob/master/docs/general.md)
Словарь с данными для подключения к БД мы получаем из функции config() в одноимённом файле.
В файл database.ini вводится конфигурация данных. 
Например, 
[postgresql] 
host=localhost 
user=postgres 
password=psw 
port=5555
Активация
Запустите скрипт в файле main.py.
Скрипт создаст новую базу данных.
Исходя из количества компаний в списке, создаст таблицы. 
Для каждого работодателя заполнит таблицы данными с hh.ru и выведет в консоль.









