# ToDo Лист API

Простой учебный проект на FastAPI для управления задачами по матрице Эйзенхауэра.

## 🚀 Запуск проекта

1. Создайте и активируйте виртуальное окружение:
python -m venv venv
source venv/bin/activate # macOS / Linux
venv\Scripts\activate # Windows

2. Установите зависимости:
pip install -r requirements.txt

3. Запустите приложение:
uvicorn main:app --reload

После запуска API доступно по адресу:  
http://127.0.0.1:8000

---

## Основные возможности API

- Просмотр всех задач — `GET /tasks`
- Просмотр задачи по ID — `GET /tasks/{task_id}`
- Фильтр по квадранту — `GET /tasks/quadrant/{quadrant}`
- Фильтр по статусу — `GET /tasks/status/{status}`
- Поиск по ключевому слову — `GET /tasks/search?q=...`
- Получение статистики — `GET /tasks/stats`

---

## Автор
Даниил Монин   
