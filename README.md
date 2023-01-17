### ETL_Airflow
#### Dags: 
- k-veryutina-cbr.py: забираем по API данные с курсом валют, парсим, складываем в Greenplum;
- k-veryutina-rick-and-morty.py: нахождение ТОП-3 локаций в данных Рик и Морти, для нахождения используется свой оператор TopLocations

#### Plugins:
- оператор TopLocations для нахождения ТОП-3 локаций.
