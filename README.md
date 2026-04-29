# 1С: Адаптер Kafka — YAxUnit

![Платформа](https://img.shields.io/badge/1С-8.3.21+-blue)
![EDT](https://img.shields.io/badge/EDT-2025.2+-blue)
![YAxUnit](https://img.shields.io/badge/YAxUnit-25.12-blue)

Служебный EDT-проект с расширением [YAxUnit](https://github.com/bia-technologies/yaxunit) для запуска unit-тестов [1С: Адаптер Kafka](https://github.com/ShadobaAI/kafka-adapter).

## Назначение

Репозиторий содержит локальную копию тестового движка YAxUnit в формате EDT:

- **локальная разработка и отладка unit-тестов** — запуск тестов из EDT или временной информационной базы;
- **CI-тестирование** — загрузка расширения во временную базу перед прогоном unit-тестов;
- **обновление тестового движка** — синхронизация с upstream-репозиторием YAxUnit.

> Репозиторий не является основным проектом адаптера и не входит в промышленную поставку.

## Лицензия

YAxUnit распространяется под лицензией [Apache License 2.0](https://github.com/bia-technologies/yaxunit/blob/develop/LICENSE).

Документация YAxUnit доступна на сайте проекта: <https://bia-technologies.github.io/yaxunit/>.
