ISO-3166 PHP/CSV files
=====

This is a set of files that aims to help you work with ISO Country Codes (ISO-3166-1) and ISO Region Codes (ISO-3166-2). 

PHP files format is based on associative arrays that let you find ISO code quickly, for example: 

```php
$ISO-3166-1['US'] = "United States";
$ISO-3166-2['GB']['LND'] = "City of London";
```

All files are encoded in UTF-8, but when opened in Excel they may appear weird because they are not in native Office encoding.
