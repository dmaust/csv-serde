# Hive CSV Support - dmaust fork

        add jar path/to/csv-serde.jar;

        create table my_table(a string, b string, ...)
          row format serde 'com.bizo.hive.serde.csv.CSVSerde'
          stored as textfile
        ;


This fork is designed to improve data type parsing support from the original project.
For information on this fork: http://www.dmaust.net/hive-csv-serde

Many thanks to the original github project ogrodnek/csv-serde: http://dev.bizo.com/2010/11/csv-and-hive.html
