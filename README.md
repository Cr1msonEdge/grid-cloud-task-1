# grid-cloud-task-1
## Запуск
Находясь в директории написать в консоли:
`docker-compose up --build`

---
### Архитектура
- app - fastapi приложение
- db - postgresql база данных
---
### Команды для тестирования
- Получение данных из БД: 
`curl -X GET "http://localhost:8000/items/"`

- Отправка данных в БД: 
`curl -X POST "http://localhost:8000/items/?name=Test"`