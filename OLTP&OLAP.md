
1)  OLTP - это система, которая управляет ориентированными на транзакции приложениями в Интернете, 
например: ввод заказов, розничные продажи, банкомат.

2)  OLAP - это онлайновая система, которая подает отчеты по многомерным аналитическим запросам,
таким как финансовая отчетность, прогнозирование

3) OLTP - это онлайн-система обработки транзакций . Основным направлением работы системы OLTP является
запись текущего обновления, вставки и удаления во время транзакции. 
Запросы OLTP проще и короче и, следовательно, требуют меньше времени на обработку, а также требуют меньше места .

База данных OLTP часто обновляется . Может случиться так, что транзакция в OLTP завершится неудачно в середине, 
что может повлиять на целостность данных . 
Таким образом, он должен заботиться о целостности данных. 
База данных OLTP имеет нормализованные таблицы (3NF).

   OLAP также позволяет пользователю выполнять сложные запросы для извлечения многомерных данных. В OLTP,
даже если транзакция завершится неудачно в середине,
это не повредит целостности данных, поскольку пользователь использует систему OLAP для извлечения данных из 
большой базы данных для анализа.
Просто пользователь может снова запустить запрос и извлечь данные для анализа.

Транзакции в OLAP являются длинными и, следовательно, занимают сравнительно больше времени для обработки и 
требуют большого пространства. 
Транзакции в OLAP менее часты по сравнению с OLTP. 
Даже таблицы в базе данных OLAP не могут быть нормализованы.