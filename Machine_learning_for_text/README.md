# Проект для «Викишоп» с BERT
## Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

План работы:

1. Загрузка и подготовка данных.
2. Обучение разных моделей.
3. Вывод.

Описание данных:

	- *text* - текст комментария,
	- *toxic* - целевой признак.