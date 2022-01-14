---
sourcePath: core/concepts/_includes/databases/database.md
---
## База данных {#database}

_База данных YDB (БД YDB)_ — изолированное согласованное множество данных, доступ к которому осуществляется через сервис Yandex Database.

Сервис Yandex Database:

* Принимает сетевые соединения от клиентов и обрабатывает их запросы на изменение и чтение данных.
* Аутентифицирует и авторизует клиентов.
* Обеспечивает транзакционное изменение и консистентное чтение данных.
* Обеспечивает масштабируемость нагрузки на БД и высокую доступность БД для клиентов.
* Хранит информацию о схеме данных, обрабатывает запросы по ее изменению, контролирует размещаемые данные на соответствие схеме и позволяет формулировать запросы к данным с использованием элементов схемы — таблиц, полей, индексов.
* Обеспечивает консистентное изменение данных в индексах при изменениях данных в таблицах.
* Генерирует метрики, которые можно использовать для наблюдения за работой БД.

Под БД YDB выделяются ресурсы в пределах кластера YDB (CPU, RAM, узлы, дисковое пространство).