# CP-Pension

Сссылка на интерактивную доску с решением [kaggle](https://www.kaggle.com/code/nikitaniktech/pensioner?scriptVersionId=203577239)

## Что использовали
- Python
- KNN
- CatBoost
- pGeoCode
- imbalanced-learn
- SHAP

## Что сделали
- Очистили данные
- Заполнили пропуски
- CatBoost балансирует классы, но в некоторым местах пришлось использовать imbalanced-learn
- Почтовый индекс превратили в lang, lat, state_code => более надежные гео данные

## Файлы
- Pension - графики, гео
- Итоговое решение - агрегация
