# PHP

 ```
下午 02:59:25  [mysql] 	Problem detected!
下午 02:59:25  [mysql] 	Port 3306 in use by "Unable to open process"!
下午 02:59:25  [mysql] 	MySQL WILL NOT start without the configured ports free!
下午 02:59:25  [mysql] 	You need to uninstall/disable/reconfigure the blocking application
下午 02:59:25  [mysql] 	or reconfigure MySQL and the Control Panel to listen on a different port
 ```


- Go into the most recent my.ini file and change the port to 3307.

Reference
https://stackoverflow.com/questions/18177148/xampp-mysql-does-not-start


## PHPMyAdmin Error (HY000/1045): Access denied | Cannot Connect to Server | localhost
https://www.youtube.com/watch?v=o56L2He3YbA

## phpMyadmin "Invalid Server Index"
https://forums.phpfreaks.com/topic/73996-solved-phpmyadmin-invalid-server-index/

## mysqli_connect(): (HY000/1045): Access denied for user 'root'@'localhost'
https://stackoverflow.com/questions/72439819/mysqli-connect-hy000-1045-access-denied-for-user-rootlocalhost
