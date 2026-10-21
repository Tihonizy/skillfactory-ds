# Проекты курса Skillfactory Data Science

Проекты, выполненные на [курсе Skillfactory Data Science](https://skillfactory.ru/data-scientist-pro):
визуализация, очистка данных, SQL, статистические тесты, кластеризация и NLP с моделью в продакшене.
У каждого проекта своя папка: ноутбук, короткий README на английском и подробное описание на русском.

[English version](README.md)

## Проекты

| # | Проект | Тема | Инструменты |
|---|---|---|---|
| 1 | [Визуализация оттока клиентов банка](01-bank-churn-visualization) | Визуализация данных | pandas, Plotly |
| 2 | [Анализ резюме из HeadHunter](02-hh-resume-analysis) | Очистка данных и EDA | pandas, Matplotlib, Seaborn, Plotly |
| 3 | [Анализ вакансий из HeadHunter](03-hh-vacancy-analysis) | Аналитика на SQL | PostgreSQL, psycopg2, pandas |
| 4 | [Исследование зарплат в Data Science](04-ds-salary-research) | Проверка гипотез | SciPy, statsmodels |
| 5 | [Сегментация клиентов онлайн-магазина](05-customer-segmentation) | RFM-кластеризация | scikit-learn, Plotly |
| 6 | [Тональность отзывов с Яндекс Карт](06-yandex-maps-review-sentiment) | Классификация текстов и деплой | scikit-learn, pymorphy3, FastAPI |

Интерактивные графики проекта 6 опубликованы на [GitHub Pages](https://tihonizy.github.io/skillfactory-ds/).
Модель из проекта 6 работает в сервисе [sentiment-api](https://github.com/Tihonizy/sentiment-api).

## Запуск

Зависимости каждого проекта перечислены в его `requirements.txt`:

```bash
pip install -r 05-customer-segmentation/requirements.txt
```

Датасеты в репозитории не хранятся. Ноутбуки читают их из папки `data/` рядом с ноутбуком.

## Лицензия

[MIT](LICENSE)
