
Markdown
# Генератор кулинарных рецептов с ИИ 🍳

## Главный интерфейс приложения

### Описание проекта
Веб-приложение для генерации кулинарных рецептов с использованием искусственного интеллекта. Получайте персонализированные рецепты на основе имеющихся ингредиентов с фотографиями блюд.

### Ключевые особенности
- 🍽️ Генерация рецептов по списку ингредиентов
- 🖼️ Автоматическое создание изображений блюд
- ⏱️ Указание времени приготовления и сложности
- 📱 Адаптивный интерфейс для всех устройств

### Технологический стек

**Фронтенд:**
- React.js
- Vite
- Ant Design
- Axios

**Бэкенд:**
- Python
- FastAPI
- OpenAI API
- Spoonacular API

---

## Установка и настройка

### Необходимые компоненты
- **Node.js** v18+
- **Python** 3.10+
- **API ключи:**
  - OpenAI API key
  - Spoonacular API key

### Пошаговая инструкция

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/ваш-профиль/recipe-generator.git
   cd recipe-generator
Настройте бэкенд:

Перейдите в директорию backend:
bash
cd backend
Создайте и активируйте виртуальное окружение:
bash
python -m venv venv
# Для Linux/Mac:
source venv/bin/activate
# Для Windows:
venv\Scripts\activate
Установите зависимости:
bash
pip install -r requirements.txt
Создайте файл .env:
plaintext
OPENAI_API_KEY=ваш_ключ_openai
SPOONACULAR_API_KEY=ваш_ключ_spoonacular
Настройте фронтенд:

Перейдите в директорию frontend:
bash
cd ../frontend
Установите зависимости:
bash
npm install
Запуск приложения:

Запустите бэкенд (из папки backend):
bash
uvicorn app.main:app --reload
Запустите фронтенд (из папки frontend):
bash
npm run dev
Приложение будет доступно по адресу: http://localhost:5173

Получение API ключей
OpenAI API:

Зарегистрируйтесь на platform.openai.com.
В разделе "API Keys" создайте новый ключ.
Spoonacular API:

Зарегистрируйтесь на spoonacular.com/food-api.
Получите ключ в личном кабинете.
Структура проекта
recipe-generator/
├── backend/               # Серверная часть
│   ├── app/               # Исходники FastAPI
│   ├── requirements.txt   # Зависимости Python
│   └── .env               # Конфигурация
└── frontend/              # Клиентская часть
    ├── src/               # Исходники React
    ├── public/            # Статические файлы
    └── package.json       # Зависимости Node.js

Создайте новый файл `README.md` по [этой ссылке](https://github.com/1he0den/ai_pet_project/new/main?filename=README.md), вставьте содержимое, и сохраните файл.
