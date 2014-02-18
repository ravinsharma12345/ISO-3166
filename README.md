ISO-3166 PHP/CSV files
======

This is a set of files that aims to help you work with **ISO Country Codes** (ISO-3166-1) and **ISO Region Codes** (ISO-3166-2). 

All files are encoded in **UTF-8**, but when opened in Excel they may appear weird because they are not in native Office encoding.

PHP Files included:
------

* **ISO-3166.php**: Array of Country codes ($ISO_3166_1) and array of regional codes ($ISO_3166_2).
* **ISO-3166-1.php**: Only the Country Codes array ($ISO_3166_1).
* **ISO-3166-2.php**: Only the Regional Codes array ($ISO_3166_1).
* **PHP Folder**: Individual files per region that contains an array ($ISO_3166_2) with his information. Example of filename format: ISO-3166-2-US.php

PHP files format is based on associative arrays that let you find ISO code quickly, for example: 

```php
$ISO_3166_1['US'] = "United States";
$ISO_3166_2['GB']['LND'] = "City of London";
```

CSV files included:
------

* **ISO-3166.csv**: All information about ISO Country codes and Region codes splitted with semicolon. Columns in file: COUNTRY NAME, COUNTRY SHORT CODE, COUNTRY LONG CODE, COUNTRY NUMBER CODE, REGION NAME, REGION TYPE, REGIONAL CODE, REGIONAL NUMBER CODE.
* **ISO-3166-1.csv**: Only information about Country codes, columns in file: COUNTRY NAME, COUNTRY SHORT CODE, COUNTRY LONG CODE, COUNTRY NUMBER CODE.
* **ISO-3166-2.csv**: Only information aboun Region codes, columns in file: COUNTRY SHORT CODE, REGION NAME, REGION TYPE, REGIONAL CODE, REGIONAL NUMBER CODE.
* **ISO folder**: Individual csv files per region, same format as ISO-3166.csv.

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/fran-diaz/iso-3166/trend.png)](https://bitdeli.com/free "Bitdeli Badge")