# Упражнение на чтение кода. Фильмы с TMDB

Сервис предназначен для создания собственной базы данных, содержащей информацию о фильмах.
Информация загружается с сайта https://themoviedb.org

## Создание файла данных

Для создания файла данных необходимо запустить файл make_own_db.py. В появившейся строке ввода нужно
ввести api_key, раннее полученный на сайте. Информация загрузится в файл MyFilmDB.json.

## Поиск фильмов

Для поиска информации о фильме нужно запустить файл search_in_db.py. После запуска необходимо
ввести путь к файлу данных и затем указать название искомого фильма. Если информация о фильме есть в базе
данных, она выведется на экран.

## Поиск рекомендованных фильмов

Для выдачи списка рекомендованных фильмов запускается файл find_similar.py. После указания фильма, на основе которого необходимо
выдать рекомендации, выводится на экран список рекомендованных фильмов.
