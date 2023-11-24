# Документация на бэкэнд
Структура:

- [architecture.md](architecture.md): общая архитектура бэкэнда
- [initial-db-schema.sql](initial-db-schema.sql): первоначальная схема базы данных
- [sesmgr-ws.svg](sesmgr-ws.svg): диаграмма взаимодействия менеджера сессий и вебсокетов

## Используемые технологии

Язык программирования: [Golang](https://go.dev/), БД - [PostgreSQL](https://www.postgresql.org/)
- Валидация: [valgo](https://github.com/cohesivestack/valgo)
- Web-framework: [🦍Gorilla](https://gorilla.github.io/)
- Конфигурация: [🐍Viper](https://pkg.go.dev/github.com/dvln/viper)
- Работа с БД: [pgxpool](https://pkg.go.dev/github.com/jackc/pgx/v5@v5.5.0/pgxpool)
