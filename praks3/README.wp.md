# praks 3

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

------------------------------

#PHP my admin

juhend: 
https://www.codero.com/knowledge-base/content/24/415/en/installing-phpmyadmin-on-debian-8.html

logisin sisse: http://172.23.13.39/phpmyadmin/

kasutajanimi root ja parooliks qwerty





# praks4

ülesandeks oli https sertifikaat teha

tegin juhendi järgi:https://www.digitalocean.com/community/tutorials/how-to-create-a-ssl-certificate-on-apache-for-debian-8?fbclid=IwAR1gZGHBANP6aXdGnUQwKlRAtyJbFTvUCpqBaHZXS8rtmqi83LHU4qeRI9k





# praks5

