app/: Це основна папка додатку.
app/api/: Тут зберігаються всі файли, що стосуються API.
app/api/contacts/: Тут розміщено файли, пов'язані з контактами.
app/api/__init__.py: Цей файл маркує папку api як пакет Python.
app/api/contacts/__init__.py: Цей файл маркує папку contacts як пакет Python.
app/api/contacts/crud.py: Файл, де містяться функції для операцій CRUD.
app/api/contacts/models.py: Файл, де описуються моделі даних SQLAlchemy.
app/api/contacts/schemas.py: Файл, де описуються схеми Pydantic для валідації даних.
app/api/contacts/main.py: Основний файл для маршрутизації та обробки запитів API стосовно контактів.
app/data_base/: Тут зберігаються файли, що стосуються бази даних.
app/data_base/__init__.py: Цей файл маркує папку data_base як пакет Python.
app/data_base/base.py: Файл, де створюється базовий клас для моделей даних SQLAlchemy.
app/data_base/session.py: Файл, де налаштовується з'єднання з базою даних та створюється сесія для роботи з нею.
app/main.py: Основний файл, який ініціалізує FastAPI та містить основну конфігурацію додатку.
