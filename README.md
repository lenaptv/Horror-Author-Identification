# Horror-Author-Identification
Нейросеть (на основе keras) определяет автора жанра ужасов по одному предложению

Источник датасета: https://www.kaggle.com/competitions/spooky-author-identification/data

Для решения данной задачи (определения автора текста) была выбрана рекуррентная нейросеть на основе LSTM архитектуры.

В работе были использованы библиотеки: spacy, keras и др

Показатели accuracy модели на достаточно высоком уровне.

Все расчеты и детали исследований (предобработка данных, обучение модели и проверка работы модели на тестовой выборке) см в ноутбуке `horror_author_ident.ipynb`
