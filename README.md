# nlp_hackathon

Решение команды "Тимур и его команда".

![test workflow](https://github.com/rashidnabiev003/nlp_hackathon/actions/workflows/build.yaml/badge.svg)
![sphinx workflow](https://github.com/rashidnabiev003/nlp_hackathon/actions/workflows/pages/pages-build-deployment/badge.svg)

## Задача

Предложить метод парсинга таблиц и списков документов (docx) для векторной базы данных для IRсистемы в составе QA чат-бота.

Критерием качества рассматриваются лексические и "семантические" метрики генерации ответа языковой модели, использующей IR модель.

## Полезная информация

- **[Руководство по разработке ПП](gitdocs/contributing.md)** - обязательный гайд для всех участников о правилах написания кода и создания Пулл Реквестов.

## Подготовка рабочего окружения

```bash
make install_all
```

## Описание эксприментов

В результате работы над задачей были созданы артефакты исследований.

Их описание и путь

### Парсер

- **[Описание работы парсеров](gitdocs/parser_work.md)**

### Исследование метрик

- **[Таблица с кратким описанием метрик и обоснованием их выбора](gitdocs/metric_table.md)**

## Документация

- **[Документация по библиотеке](https://rashidnabiev003.github.io/nlp_hackathon/)** - содержит описания из doc-string используемых модулей

## Лицензия

Вся интеллектуальная собственность принадлежит физическим лицам - участникам команды "Тимур и его команда".

ПП предоставляется как есть, участники не несут отвественность за увечье приченное физическим устройства или лицам в процесс эксплуатации ПП.

Участники оставляет за собой право изменить лицензию без предупреждения.

Изменения в лицензии применяется моментально, во всех мирах, во всех временных линий, включая те, в которых эти изменения не наступили.
