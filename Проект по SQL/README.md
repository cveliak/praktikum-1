# Проект по SQL
**(Данный проект является частью выпускного проекта)**

## Данные
В наличии была база данных сервиса для чтения книг по подписке. В ней содержится информация о книгах, издательствах, авторах, а также пользовательские обзоры книг:

Данные о книгах:
* идентификатор книги;
* идентификатор автора;
* название книги;
* количество страниц;
* дата публикации книги;
* идентификатор издателя.

Данные об авторах:
* идентификатор автора;
* имя автора.

Данные об издательствах:
* идентификатор издательства;
* название издательства.

Данные о пользовательских оценках книг:
* идентификатор оценки;
* идентификатор книги;
*  имя пользователя, оставившего оценку;
* оценка книги.

Данные о пользовательских обзорах:
* идентификатор обзора;
* идентификатор книги;
* имя автора обзора;
* текст обзора.

## Задача
Проанализировать базу данных. 

## Описание проекта
Создано подключение к базе, исследованы таблицы, решены задачи по SQL, описаны выводы по каждому заданию

## Используемые библиотеки и инструменты
*SQL, PostgreSQL*

## Статус проекта
завершен

## Вывод
Почти все книги в сервисе были опубликованы начиная с 2000 года. Больше всего книг толще 50 страниц выпущены издательством Penguin Books. Cамую высокую оценку книг получила популярная писательница Дж.К.Роулинг. Активные пользователи в среднем делают 24 обзора на книги.
