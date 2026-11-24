# Станислав Царыгин

**Backend .NET-разработчик** · 3 года коммерческой разработки · Чебоксары / удалённо

Специализация: производительность и данные. Миграции легаси, оптимизация PostgreSQL,
потоковая обработка больших объёмов.

## Что сделано в продакшене

- Миграция монолита .NET Framework → .NET 8 (ASP.NET Core): **+30% производительности**
- Оптимизация аналитики в PostgreSQL: отчёты **с 2 минут до 20 секунд** на сотнях тысяч строк
  (переработка хранимых процедур, индексы, анализ execution plans)
- Потоковый импорт XML-архивов: async/await, без загрузки файлов в память
- Переработка LINQ-запросов под SARGability: индексы начали использоваться
- Миграция бизнес-логики MS SQL (T-SQL) → PostgreSQL (PL/pgSQL)

## Флагманский проект

### [Pressa](https://github.com/TalisTalis/pressa) — платформа цифровой газеты с подпиской

![CI](https://github.com/TalisTalis/pressa/actions/workflows/ci.yml/badge.svg)

Модульный монолит на **.NET 10 LTS**: каталог статей и выпусков, пейволл,
импорт XML-архивов, полнотекстовый поиск. Границы модулей проверяются арх-тестами в CI.

Каждое решение задокументировано: ADR, лабораторные по конкурентности и изоляции
транзакций, нагрузочные тесты с графиками. Запуск: `docker compose up`.

Стек проекта строится по публичному roadmap — что уже работает, видно в README проекта.

## Стек

**В продакшене:** C# · .NET 8 · ASP.NET Core · EF Core · ADO.NET · LINQ ·
PostgreSQL · MS SQL / T-SQL · Docker / Compose · Git · JavaScript (ES6)

**Добавляю в арсенал через Pressa:** .NET 10 · Redis · RabbitMQ · xUnit + Testcontainers ·
OpenTelemetry · GitHub Actions · NBomber

## Контакты

- Telegram: [@tsartalis](https://t.me/tsartalis) — предпочитаемый способ
- Email: tsarst@gmail.com

Открыт к предложениям: C#/.NET backend, удалённо.
