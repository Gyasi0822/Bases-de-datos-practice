docker compose -f compose.yaml up -d  --- Esto inicia MariaDB y phpMyAdmin.


docker compose -f compose.yaml exec db mariadb -u root -p --- entrar a maria db

docker compose -f compose.yaml down --- detener MariaDB y phpMyAdmin

docker compose -f compose.yaml stop --- detenerlos temporalmente sin eliminar los contenedores

docker volume rm bases-de-datos-practice_mariadb_data --- el comando eliminará permanentemente las bases de datos y tablas guardadas en ese volumen