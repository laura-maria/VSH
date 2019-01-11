+praks 3
php ja mysql'i pakettide paigaldamine website - https://wiki.debian.org/LaMp
#root kasutajana
aptitude update && aptitude upgrade #uuenduste allalaadimine
aptitude install mysql-server mysql-client #MySql'i paigaldamine
--------------------------------
#PHP paigaldamine
aptitude install php php-mysql
aptitude install perl libapache2-mod-perl2
aptitude install python libapache2-mod-python
-----------------------------------
#PHP test
nano /var/www/html/test.php
kirjutasin sinna: <?php phpinfo(); ?>

---------------------------------
172.23.13.39/test.php #tegin HTML keeles väikese scripti, kuna PHP keelt ma ei oska
ja see töötab
