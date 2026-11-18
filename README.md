# Привет, я Павел — Data Analyst

Готовлю данные и считаю выводы, на которые можно опираться при решениях:
SQL-метрики продуктов, A/B-тесты, ML-модели с бизнес-интерпретацией.

## Проекты

| Проект | Что внутри | Ключевой результат |
|---|---|---|
| [telco-churn](https://github.com/pavelkisov/telco-churn) | Реальный датасет IBM Telco: EDA + XGBoost (Pipeline, StratifiedKFold, permutation importance), ноутбук с графиками | ROC-AUC **0.84** CV / **0.83** test; контракт и tenure — главные факторы оттока |
| [olist-analysis](https://github.com/pavelkisov/olist-analysis) | Реальный Olist (99 440 заказов): AOV, LTV, когортный retention через SQL (CTE, оконные функции), ноутбук с EDA | AOV R$ 160.99, repeat rate 3.12%, доставка 12.1 дн |
| [ab-test-analysis](https://github.com/pavelkisov/ab-test-analysis) | A/B-тест: z-test для пропорций, Welch cross-check, 95% CI, Cohen's h, ноутбук с визуализацией | +1.22 п.п., p=0.004 — значимо, но effect size мал: решение за практической значимостью |

## Стек

**SQL** — CTE, оконные функции, JOIN · **Python** — pandas, numpy, scipy ·
**ML** — scikit-learn, XGBoost (классификация) · **A/B** — z-test, CI, effect size ·
**Визуализация** — matplotlib, seaborn

## Подход

- Реальные публичные датасеты вместо выдуманных цифр: IBM Telco, Olist (Kaggle)
- Каждый проект можно воспроизвести одной командой — данные скачиваются сами, результаты пишутся в JSON
- Честно разделяю, что в проекте боевое (метод), а что учебное (синтетика в A/B-примере)

## Контакты

- Telegram: [@kisovpavel](https://t.me/kisovpavel)
- GitHub: [pavelkisov](https://github.com/pavelkisov)

Открыт к предложениям junior/junior+ Data Analyst (в офисе или удалённо).
