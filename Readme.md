## Benchmark: ClickHouse Vs. InfluxDB Vs. Postgresql Vs. Parquet 

-----

#### How to use:
* Rename the file "properties-model.ini" to "properties.ini"
* Fill with your own credentials
----

The proposal of this work is to compare the speed in read/writing a midle level of data ( a dataset with 9 columns and 50.000 lines) to four diferent databases:
* ClickHouse
* InfluxDB
* Postgresql
* Parquet (in a S3 Minio Storage)
ToDo:
* DuckDB with Polars
* MongoDB
* Kdb+


 
Deve-se relevar:
é uma "cold-storage" ou  "frezze-storage"? ,br>
influxdb: alta leitura e possui a vantagem da indexaçõa para posterior vizualização de dados em gráficos

notas: 
* comparar tamanho do csv com parquet