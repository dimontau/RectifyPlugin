# CraftBeerPi RectifyPlugin
[Тема на форуме](https://forum.homedistiller.ru/index.php?topic=308749.0)

Этот плагин позволяет использовать CraftBeerPi в качестве автоматики для ректификационной колонны.
Реализованы несколько режимов:
###### Покапельный отбор голов:
- Указывается скорость отбора и общее количество голов, после которого переходит переключение на отбор тела.
###### Залповый сброс голов:
- Указывается время накопления, время сброса и общее количество голов.
###### Отбор тела с автоуменьшением:
Указывается стартовая скорость отбора и температура завершения отбора тела и перехода на хвосты.
Алгоритм вычисляет и автоматически уменьшает отбор в зависимости от температуры в кубе.
###### Отбор тела по старт-стопу:
Алгоритм позволяет реагировать на изменение температуры колонны, перекрывать и уменьшать отбор для стабилизации колонны.

![interface](https://i.ibb.co/vdfbL15/2020-01-12-19-12-13.png)
![my column](https://i.ibb.co/wsKtndK/column.jpg)