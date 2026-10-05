# Архитектура интернет-магазина (аналог amperka.ru)

- Сервер: Java 21, Spring Boot, модульная структура (catalog, cart, order, payment, delivery, cms, admin).
- Клиент: React + библиотека UI-компонентов, адаптивная вёрстка от 360 px.
- БД: PostgreSQL, миграции Flyway.
- Внешние сервисы через адаптеры: ЮKassa (платежи), СДЭК (доставка, ПВЗ), почтовый провайдер.
- Развёртывание: Docker-контейнеры, CI/CD на GitHub Actions.
