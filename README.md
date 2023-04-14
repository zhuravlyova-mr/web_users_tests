# Тесты для веб-сервера "Веб-сервер для БД пользователей"


![Картинка](images/faces.jpg)
![Картинка](images/password.jpg)


## Порядок запуска тестов

![Картинка](images/node.png)
![Картинка](images/nest.png)
![Картинка](images/postgres.png)
![Картинка](images/axios.png)

Перед запуском создайте в pgAdmin базу данных web_users_test. 

Для запуска и тестирования установите необходимые зависимости и выполните вначале запуск сервера в одном терминале (один из тестов требует, чтобы сервер был запущен заранее):
npm run start:dev

Затем в другом терминале выполните дважды:
npm run test

При первом запуске не все тесты могут быть пройдены, так как в БД не будет нужных данных. При втором запуске все тесты будут пройдены.
