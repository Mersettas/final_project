МФТИ Хакатон 2024

# RAG (Retrieval-Augmented Generation) Система для Ответов на Вопросы о Китае

Этот проект реализует RAG систему, которая отвечает на вопросы туристов о Китае. Система комбинирует поиск по базе данных текстовых документов с генеративными возможностями модели искусственного интеллекта, чтобы предоставлять точные и информативные ответы.

## О проекте

Система предназначена для туристов, интересующихся культурой, достопримечательностями, историей и другими аспектами путешествий по Китаю. Она позволяет:
- Быстро находить релевантную информацию по текстовым источникам.
- Генерировать осмысленные ответы с использованием модели машинного обучения.

## 📋 Основные функции

- **Поиск по базе данных текстов**: Используется библиотека FAISS для эффективного поиска по векторам.
- **Генерация ответов**: Модель `GPT-4` или аналогичная используется для создания осмысленных ответов на основе найденных данных.

## 🚀 Как запустить проект

- **Клонируйте репозиторий** - git clone https://github.com/Mersettas/final_project.git
- **Установите зависимости** - pip install -r requirements.txt
- **Запустите все ячейки в ноутбуке RAG system.ipynb**

## Используемые технологии
**PyPDF2**: Парсинг данных из pdf
**Langchain**: поиск по векторам.
**SentenceTransformers**: Создание эмбеддингов для текстов.
**Openai**: Фреймворк для обращения в модель GPT4
**Gradio**: Веб-интерфейса для общения с моделью
