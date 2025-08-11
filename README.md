# TODO LIST API

## Запуск приложения
1. Установка зависимостей: `composer install`
2. Переименовать файл `.env.example` на `.env`
3. Изменить переменные для подключения к базе данных: `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`
4. Выполнить команды: `npm install`, `npm run build`
5. Выполнить миграции: `php artisan migrate`
6. Запустить приложение: `php artisan serve`

## API

Для выполнения POST, PUT и DELETE используйте заголовки:
1. Accept: application/json
2. Content-Type: application/json

### Tasks

* GET /tasks - Получить все задачи
* GET /tasks/{id} - Получить задачу по id
* POST /tasks - Добавить задачу
* PUT /tasks/{id} - Изменить задачу
* DELETE /tasks/{id} - Удалить задачу


