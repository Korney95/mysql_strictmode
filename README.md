# mysql_strictmode
1) Скачать файл и положить в директорию /etc/mysql/conf.d
2) перезапустить mysql service mysql restart
3) проверить включен ли strict mode можно select@@GLOBAL.sql_mode;
