---
softDelete: true
timestamps: true
---

| name         | type               | default | unique | nullable | desctiption         |
| ------------ | ------------------ | ------- | ------ | -------- | ------------------- |
| spawn_chance | float              | 0       |        |          | Шанс появления      |
| min_level    | int                | 1       |        |          | Мин уровень         |
| max_level    | int                |         |        |          | Макс уровень        |
| modifiers    | array [[Modifier]] |         |        |          | Модификаторы        |
| drops        | array [[Проекты/Браузерна ММО игра/Техническая структура/Models/Item]]     |         |        |          | Выпадающие предметы |
|              |                    |         |        |          | Сложность           |

