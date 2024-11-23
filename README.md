# Домашнее задание к занятию "Микросервисы: принципы`

---

### Задание 1 API Gateway


Предложите решение для обеспечения реализации API Gateway. Составьте сравнительную таблицу возможностей различных программных решений. На основе таблицы сделайте выбор решения.

Решение должно соответствовать следующим требованиям:

- маршрутизация запросов к нужному сервису на основе конфигурации,
- возможность проверки аутентификационной информации в запросах,
- обеспечение терминации HTTPS.
Обоснуйте свой выбор.

### Решение:

Для реализации API Gateway в микросервисной архитектуре я рассмотрел несколько популярных решений. Ниже представлена сравнительная таблица возможностей различных программных решений:


|Решение      |Маршрутизация запросов|Аутентификация|Терминация HTTPS|Модель распространения|
|-------------|----------------------|--------------|----------------|----------------------|
| Kong        | 10|  ✓|✓|✓|Открытый исходный код|
| NGINX       | 3000 | ✓|✓|✓ | Открытый исходный код / Платная|
| Traefik     | 500|✓|✓|✓|Открытый исходный код|
| HAProxy     | 7000|✓|✓|✓|Открытый исходный код|
| API Gateway (AWS)     | 4000|✓|✓|✓|Платная|
| Azure API   |✓|✓|✓|Платная|
| Tyk         |✓|✓|✓|Открытый исходный код / Платная








































