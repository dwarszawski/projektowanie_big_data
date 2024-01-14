# Projektowanie rozwiązań Big Data

## Cel
1) Zaprojektowanie procesu ETL lub ELT do przetwarzania wsadowego surowych danych wejściowych do postaci ustrukturyzowanej. Analiza danych wejściowych do określenia wzorców i trendów.
2) Zaprojektowanie procesu ETL lub ELT do przetwarzania strumieniowego surowych danych. Zasymulowanie procesu pozyskiwania i analizy danych w czasie rzeczywistym do określenia wzorców i trendów.

## Wymagania
* Wyznaczenie praktycznego celu pracy: wymagania funkcjonalne i techniczne (atrybuty jakości)
* Wykorzystanie istniejących zbiorów danych lub symulacja danych wejściowych
* Analityka danych lub uczenie maszynowe:
  * Analityka danych: analiza danych, określenie metryk, wizualizacja danych
  * Uczenie maszynowe: wybór odpowiedniej metody, zbudowanie modelu, ocenianie wsadowe (batch scoring) lub predykcja czasu rzeczywistego
* Dobór odpowiednich narzędzi do wyznaczonego celu

## Wytyczne
* Projekt realizowany w grupach 2-3 osobowych lub indywidualnie
* Akceptacja projektu wymagana do zaliczenia przedmiotu i podejścia do egzaminu ustnego
* Przygotowanie infrastruktury na koncie AWS
* Dokumentacja w formie opisowej od 2 do 5 stron:
  * Architektura systemu jako diagram komponentów
  * Opis poszczególnych komponentów i ich rola
  * Opis transformacji, łączenia i wzbogacania danych
  * Opis wykorzystywanych metod uczenia maszynowego
  * Opis procesu analizy danych
  * Opis metryk wyjściowych
  * Opis wizualizacji danych i metryk
  * Numer konta AWS gdzie została przygotowana infrastruktura
  * Dokumentacja powinna być załączona w systemie OKNO w sekcji "Praca grupowa"

## Stos technologiczny
* Infrastruktura:
    * AWS Academy Learner Lab
    * Docker
* Języki programowania:
    * Python
    * Java
    * Scala
    * Inne
* Środowisko deweloperskie:
    * Cloud9
    * Intellij IDEA Community Edition
* Procesowanie wsadowe:
    * Apache Spark
    * Apache Airflow
    * Amazon Elastic Map Reduce (EMR)
    * AWS Glue
    * AWS Lambda
* Procesowanie strumieniowe
    * Apache Kafka
    * Kinesis Data Streams
* Przechowywanie danych
    * Amazon Aurora
    * Amazon DynamoDB
    * Amazon S3
    * Mongo DB
* Analityka danych
    * Amazon Athena
    * Amazon Redshift
    * Amazon Quicksight
    * Kinesis Data Analytics
    * Pandas
    * Tableu
* Uczenie maszynowe
    * Spark ML
    * Amazon Sagemaker

## Przydatne linki
* [Przykłady danych dostępnych przez publiczne API](https://github.com/public-apis/public-apis)
* [Serwisy dostępne przez AWS Academy Learner Lab](https://labs.vocareum.com/web/2884087/2295987.0/ASNLIB/public/docs/lang/en-us/README.html#services)
