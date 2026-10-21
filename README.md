# Skillfactory Data Science Projects

Projects completed during the [Skillfactory Data Science course](https://skillfactory.ru/data-scientist-pro):
data visualization, data cleaning, SQL, statistical testing, clustering and NLP with a deployed model.
Each project has its own folder with a notebook, a short English README and a detailed description in Russian.

[Русская версия](README.ru.md)

## Projects

| # | Project | Topic | Tools |
|---|---|---|---|
| 1 | [Bank customer churn visualization](01-bank-churn-visualization) | Data visualization | pandas, Plotly |
| 2 | [HeadHunter resume analysis](02-hh-resume-analysis) | Data cleaning and EDA | pandas, Matplotlib, Seaborn, Plotly |
| 3 | [HeadHunter vacancy analysis](03-hh-vacancy-analysis) | SQL analytics | PostgreSQL, psycopg2, pandas |
| 4 | [Data science salary research](04-ds-salary-research) | Hypothesis testing | SciPy, statsmodels |
| 5 | [Online store customer segmentation](05-customer-segmentation) | RFM clustering | scikit-learn, Plotly |
| 6 | [Yandex Maps review sentiment](06-yandex-maps-review-sentiment) | NLP classification and deployment | scikit-learn, pymorphy3, FastAPI |

Interactive charts for project 6 are published on [GitHub Pages](https://tihonizy.github.io/skillfactory-ds/).
The model from project 6 is served by [sentiment-api](https://github.com/Tihonizy/sentiment-api).

## Running the notebooks

Each project lists its dependencies in `requirements.txt`:

```bash
pip install -r 05-customer-segmentation/requirements.txt
```

Datasets are not stored in the repository. Notebooks read them from a `data/` folder next to the notebook.

## License

[MIT](LICENSE)
