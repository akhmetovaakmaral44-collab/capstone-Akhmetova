# Анализ калорийности продуктов питания и классификация категорий

## 📌 Описание проекта
Проект посвящен исследованию питательной ценности продуктов питания, проведению аналитических SQL-запросов и построению моделей машинного обучения для автоматического определения группы продуктов (`Food Group`) на основе их наименования и калорийности.

## 📁 Структура репозитория
* `Food_Items_Calories.csv` — исходный датасет продуктов.
* `Food_Analysis_Project.ipynb` — Jupyter Notebook с исследованием (EDA, SQL, NLP, ML).
* `presentation.pdf` — презентация для защиты проекта.
* `README.md` — главная документация проекта.

## 🛠️ Стек технологий
* **Python**, **Pandas**, **NumPy**
* **SQLite / SQL** (аналитические запросы, оконные функции)
* **Matplotlib**, **Seaborn** (визуализация)
* **scikit-learn** (TF-IDF Vectorizer, StandardScaler, LogisticRegression, RandomForestClassifier)

## 📈 Результаты моделей
* **Logistic Regression:** Accuracy ≈ 50.0%
* **Random Forest Classifier:** Accuracy ≈ 58.3% *(Лучшая модель)*

## 🚀 Инструкция по запуску
1. Откройте файл `Food_Analysis_Project.ipynb` в Google Colab.
2. Выполните все ячейки по порядку (**Среда выполнения -> Перезапустить и выполнить все**).
