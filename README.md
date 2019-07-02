Приложение ведет учет космических кораблей в
далеком будущем (в 3019 году). Реализованы следующие
возможности:
1. получать список всех существующих кораблей;
2. создавать новый корабль;
3. редактировать характеристики существующего корабля;
4. удалять корабль;
5. получать корабль по id;
6. получать отфильтрованный список кораблей в соответствии с
переданными фильтрами;
7. получать количество кораблей, которые соответствуют фильтрам.

Также присутствовует бизнес-логика:
Перед сохранением корабля в базу данных (при добавлении нового или
при апдейте характеристик существующего), высчитывается
рейтинг корабля и сохраняется в БД.
