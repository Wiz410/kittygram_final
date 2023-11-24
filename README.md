# Kittygram_final

**Kittygram** социальная сеть для обмена фотографиями любимых питомцев. Учебный проект 17 спринта в **yandex practicum**.

**В нем вы можете:**

- Зарегистрироваться, авторизироваться.
- Добавить нового котика на сайт:
    - Выбрав фотографию.
    - Имя кота.
    - Год рождения.
    - Выбрать 1 из 12 цветов кота.
    - Выбрать или создать новые достижения.
- Редактировать и удалять своего котика.
- Просматривать котиков других пользователей.

## Требование

- [Docker 4.25.0](https://www.docker.com/)
- [Python 3.10.12](https://docs.python.org/release/3.10.12/)
- [Node js 18.17.1](https://nodejs.org/en/blog/release/v18.17.1)
- [Django 3.2.3](https://www.djangoproject.com/)
- [Django REST Framework 3.12.4](https://www.django-rest-framework.org/)
- [React 18.2.0](https://legacy.reactjs.org/docs/getting-started.html)
- [Gunicorn 20.1.0](https://docs.gunicorn.org/en/20.1.0/)
- [Nginx 1.18.0](https://nginx.org/en/docs/)

### Как запустить проект

Клонируйте репозиторий и перейдите в директорию проекта:
```bash
git clone git@github.com:Wiz410/kittygram_final.git
cd kittigram_final/
```

Создайте файл `.env` и заполните его:
```bash
touch .env
nano .env
```

```env
POSTGRES_USER=django_user
POSTGRES_PASSWORD=django_db_password
POSTGRES_DB=django_db
DB_HOST=db
DB_PORT=5432
DJANGO_SECRET_KEY=secret_key
DJANGO_DEBUG=False
DJANGO_ALLOWED_HOSTS=127.0.0.1 localhost
DJANGO_TIME_ZONE=UTC
```
Сохраните `ctrl + s` выйдите из него `ctrl + x`.

Запустите Docker Compose:
```bash
docker compose up
```

Проект будет доступен по адресу: http://127.0.0.1:9000/

#### Авторы проекта

- [Yandex Practicum](https://github.com/yandex-praktikum)
- [Danila Polunin](https://github.com/Wiz410)