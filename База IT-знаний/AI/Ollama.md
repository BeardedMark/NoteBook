Это сервер, который умеет запускать локальные модели и предоставляет к ним API

## Сервер

1. Скачать Ollama окружение - https://ollama.com/download
2. Проверить PATH или перезагрузить систему

- Директория - `C:\Users\<Пользователь>\.ollama\models`
- Процесс - `Ollama.exe
- Адрес сервера - `http://localhost:11434`

`ollama -v` - версия сервера / проверка доступности
`ollama serve` - запустить сервер в терминале (занимает терминал)

`ollama list` - установленные модели
`ollama ps` - запущенные модели
`ollama pull model` - скачать модель
`ollama run model` - запустить модель в терминале
`ollama stop model` - остановить модель
`ollama rm model` - удалить модель

## Модели

| Назначение                | Модель              | Размер   | Команда                         |
| ------------------------- | ------------------- | -------- | ------------------------------- |
| Универсальный помощник    | `qwen2.5:7b`        | ~4.7 ГБ  | `ollama pull qwen2.5:7b`        |
| Быстрая текстовая модель  | `gemma3:4b`         | ~3 ГБ    | `ollama pull gemma3:4b`         |
| Сильная большая модель    | `qwen3:14b`         | ~9–10 ГБ | `ollama pull qwen3:14b`         |
| Работа с изображениями    | `llava`             | ~4.7 ГБ  | `ollama pull llava`             |
| Генерация кода            | `qwen2.5-coder:7b`  | ~4.7 ГБ  | `ollama pull qwen2.5-coder:7b`  |
| Очень сильный программист | `deepseek-coder-v2` | крупная  | `ollama pull deepseek-coder-v2` |
| Векторизация (Embeddings) | `nomic-embed-text`  | ~300 МБ  | `ollama pull nomic-embed-text`  |
