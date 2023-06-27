# Project_toxic_text

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Задача: обучить модель классифицировать комментарии на позитивные и негативные на основании набора данных с разметкой о токсичности правок.

Метрика качества F1 модели должна быть не меньше 0.75..

План проекта

Загрузка и подготовка данных.
Обучение разных моделей.
Выводы.
Описание данных

Данные находятся в файле toxic_comments.csv. Столбец text в нём содержит текст комментария, а toxic — целевой признак.


Используемые инструменты: Pandas, nltk, tf-idf
