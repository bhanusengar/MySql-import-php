This script import the sql queries from a file to mysql database.

Steps to Run the secript.

1.Download here - importScript.php

2.Open the importScript.php and replace following varialbles with your Database credentials

$filename = 'importScript.php';

$mysql_host = 'localhost';

$mysql_username = 'USERNAME';

$mysql_password = 'PASSWORD';

$mysql_database = 'DB_NAME';'

3.Run the importScript.php

That's it. your database is imported :)

Note: If you have very large database file then you have to enable the following line in the import.php to avoid PHP timeouts

set_time_limit(0);
