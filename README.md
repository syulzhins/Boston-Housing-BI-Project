# BI-анализ рынка жилья в Бостоне

**End-to-End BI проект** для задач ипотечного банка.

## 🎯 О проекте

Анализ датасета Boston Housing с целью помочь банку оценивать стоимость залога, сегментировать районы и понимать ключевые факторы ценообразования.

## 🛠 Что сделано

- Разведочный анализ данных (EDA)
- SQL-витрины данных
- Линейная регрессия для прогнозирования цены
- Кластеризация районов (KMeans)
- Бизнес-рекомендации

## 🔑 Ключевые insights

- **RM** (число комнат) — главный драйвер роста цены
- **LSTAT** (% малообеспеченных) — главный фактор снижения цены
- Выделено 3 ценовых кластера районов с разным уровнем риска

## 🧰 Стек технологий

- **Python**: pandas, numpy, scikit-learn, seaborn, matplotlib
- **SQL**: витрины данных
- **ML**: Linear Regression, KMeans

## 📁 Структура

- `Boston_Housing_BI_Project.ipynb` — основной ноутбук
- `BostonHousing.csv` — датасет

## 🚀 Запуск

```bash
git clone https://github.com/syulzhins/Boston-Housing-BI-Project.git
jupyter notebook Boston_Housing_BI_Project.ipynb