# VidjayaStiven-IS-Lab
Intelligent System laboratory work
Виджая Стивен 932001 2022

## Предметная область: ЭС по выбору автомобиля
## Команда:
Андрюшина Мария 932001

Виджая Стивен 932001

Танумихарджя Рафаэл Мэтью 932001

Цурова Тамара 932001

## Ссылка на наше веб-приложение
https://car-picker-is-lab1.herokuapp.com/
<img width="1434" alt="image" src="https://user-images.githubusercontent.com/80201768/160253382-e3e4b0ed-b692-4e93-b916-b9724c6a9449.png">

## Как использовать наше веб-приложение через локальный порт:
1. Склонируйте репозиторий. / Clone Repository.
2. Откройте консоль / Open terminal
3. Установите библиотеку flask `pip install flask`
4. Установите библиотеку pymongo `pip install pymongo`
5. Запустите питонский файл `main.py` / Start debugging `main.py` file.
6. Нажмите ctrl (в Windows) / cmd (в Mac) и нажмите ссылку из консоли. / Press ctrl (on Windows) / cmd (on Mac) and click on the link from the console.
7. В вашем браузере вы можете начать использовать наше веб-приложение. / You can start use our web application in your browser.

## Видео нашей программы
Backend Version: **1.0.0**

Video: https://disk.yandex.com/d/B-rylhY4VN4_aw

Frontend Version: **1.0.2**

Video: https://disk.yandex.com/i/YfWNNcAgIFYLJQ

## Тестирование
Пользователь хочет найти варианты автомобилей со следующим характеристиками:

1. **Цена**: От 3.000.000 До 5.000.000
2. **Стиль**: SUV или Sedan
3. **Тип топлива**: Бензин
4. **Тип передачи**: Механическая или Автоматическая
5. **Бренд**: Mazda или Mercedes-Benz или BMW или Honda или Kia
6. **Цвет**: Чёрная, Красная
7. **Год производства**: Не позднее 2015
8. **Размер**: Средняя
9. **Категория**: Экономичная

## Результаты
Наша ЭС возвращает все самые подходящие варианты, а также другие подходящие варианты соответственно Базе Знаний: 

1. Те же цена, стиль, тип топлива, тип передачи, год производства, размер и категория
2. Не принимая во внимание Бренды и Цвета

Все результаты пока находятся внутри папки Car_API и папки Test_Result_File.

Файл *test_best_match.txt* - это результаты всех подходящих вариантов машин

Файл *test_close_match.txt* - это результаты всех других подходящих вариантов машин

##ССылки
https://docs.google.com/presentation/d/1-xpkclYRNiPtcmTC4hpJCS_f7ghH0wduSFtyukv3Mps/edit?usp=sharing - презентация этой лабораторной работы
https://docs.google.com/document/d/1znRnR_GB6eHqEc-o18EReNOY-FJe7k7Y/edit?usp=sharing&ouid=110887638286919699679&rtpof=true&sd=true - Отчет
https://docs.google.com/presentation/d/1tdRL1cBAZ6X7kFrnIw1cMGXzmBQ-Onf9/edit?usp=sharing&ouid=110887638286919699679&rtpof=true&sd=true - презентация с различными наглядными моделями

## Как добавить данные в Базу Данных
1. Добавьте ваши данные в файле `data_placeholder.xlsx`, потом сохраните его и назовите его как `.csv` файл с одинаковым именем файла `data_placeholder.csv`
2. Откройте питонский файл `db_insert.py` и запустите его. Посмотрите вывод подтверждения в консоль, что ваши данные успешны добавлены в БД.
3. Если вдруг ваши данные не добавлены, то обновите их, так как они уже есть в БД. Можете сделать это и с помощью приложения MongoDB Compass / сайта MongoDB.

## Стек технологий
1. Язык программирования: 
   * Фронтенд/Интерфейс: HTML, CSS
   * Бэкенд/Сервер: Python
2. Базы Данных: MongoDB
3. Веб-фреймворк: Flask
4. Хостинг: Heroku
