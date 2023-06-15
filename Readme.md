## Benchmark: ClickHouse Vs. InfluxDB Vs. Postgresql Vs. Parquet Vs. MongoDB Vs. DuckDB Vs. Kdb+

-----

#### How to use:
* Rename the file "properties-model.ini" to "properties.ini"
* Fill with your own credentials

```
pip install requeriments.txt
```

----

The proposal of this work is to compare the speed in read/writing a midle level of data (a dataset with 9 columns and 1.000.000 lines) to seven diferent databases:
* ClickHouse
* InfluxDB
* Postgresql
* Parquet (in a S3 Minio Storage)<br>
* DuckDB 
* MongoDB
* Kdb+


