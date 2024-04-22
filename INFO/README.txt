
Техстек: Maven, SQLite, JDBC, Lombok.

1) Визначаємо об'єкти (сутності) реального світу.
На основі цих об'єктів сформуємо таблиці БД та
моделі Java-класів

2) Складаємо SQL-запити INFO/SQLs.sql

3) Створюємо Maven-проект.
В Advanced Settings можемо прописати org.example.app

4) Додаємо залежності.

5) В src/main/resources створюємо директорію db

6) Через DB Browser for SQLite (https://sqlitebrowser.org/),
в src/main/resources/db, створюємо файл БД (contacts_db.db).

7) Через DB Browser for SQLite створюємо в БД таблицю
contacts (див. INFO/SQLs.sql).

УВАГА. Після маніпуляцій в базі даних,
в DB Browser for SQLite, записуємо зміни.

8) Формуємо пакети, класи в org/example/app

9) Перевіряємо працездатність програми.

