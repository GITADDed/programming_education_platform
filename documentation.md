Документация к проекту обучающей платформы
==========================================

Стек технолгий:
---------------
### Frontend:
* HTML / JS / CSS
* Bootstrap
* JQuery

### Backend:
* Java Servlets
* Freemarker
* MySQL
***
### Концепция разработки: `MVC`

### Патерн проектирования: `Repository`

### Технология связи с базой данных: `ORM`
***
Страницы:
---------
1. Главная страница.
2. Профиль.
3. Форма регистрации.
4. Форма авторизации.
5. Каталог курсов.
6. Блог организатора курса.
7. Мои курсы.
8. Редактор курсов.
9. О проекте.
10. FAQ.
11. Личная страница курса с описанием, отзывами.
12. Просмотр курса.
13. Страница настроек данных профиля.
***
Функционал сайта:
-----------------
1. Создание нового пользователя или его авторизация.
2. Профиль содержит: контактную информацию(Обозреваемую для всех
с его разрешения. почта, соц.сети, гитхаб репазиторий), рейтинг
в общем зачете по пройденным курсам, дни активности, никнейм
пользователя, выбранные на данный момент курсы, пройденные курсы,
курсы написанные пользователем, какими языками владеет пользователь,
фотография профиля.
3. Вывод курсов с фильтрами(язык программирования, уровень знаний
перед началом курса, язык, популярные курсы, курсы с лучшей оценкой,
недавно добавленные курсы, курсы от пользователей, курсы от платформы)
и без фильтров.
4. Предложение курсов на основе информации из профиля.
5. Возможность оставить отзыв / поставить оценку по 5-ти бальной шкале
о курсе, о платформе(только авторизованные и
прошедшие хотя бы один курс пользователи), просматривать могут все.
6. Есть возможность изменять данные профиля.
7. Создание/удаление блоговой записи(для модераторов).
8. Возможность проверки заданий автотестами или в ручную.
***
Задачи по разработке приложения:
--------------------------------
1. Данные профиля, такие как контактная информация проходят обработку
через регулярные выражения.
2. Использование сессии для  авторизованных пользователей.
3. Использование cookie для запоминания логина и пароля,
и для сбора метрик во время использования.
4. Ajax запросы: для проверки уже существуещего email при регистрации,
правильность заполненных данных на этапе авторизации.
5. Хэширование пароля.

`Дополнительно по возможности:
Создание и обучение простой нейронной сети для подборки курсов.`
***
Бизнес требования:
------------------    
### Цель:
* Создать приложение для повышения уровня квалификации специалиста.
* Дать возможность людям других профессий получать новую квалификацию.
* Поднять общий уровень компьютерной грамотности населения.
### Проблема:
* Недостаток квалифицированных кадров.
* Низкий уровень компьютерной грамотности.
### Решение:
* Простое в использование приложение.
* Наполнение его первоначальным контентом.
