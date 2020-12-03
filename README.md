# Orangehrm_tool
Environment variables

The OrangeHRM instance can be customized by specifying environment variables on the first run. The following environment values are provided to custom OrangeHRM:
User and Site configuration

    ORANGEHRM_USERNAME: OrangeHRM application username. Default: admin
    ORANGEHRM_PASSWORD: OrangeHRM application password. Default: Bitnami.12345

Use an existing database

    MARIADB_HOST: Hostname for MariaDB server. Default: mariadb
    MARIADB_PORT_NUMBER: Port used by MariaDB server. Default: 3306
    ORANGEHRM_DATABASE_NAME: Database name that OrangeHRM will use to connect with the database. Default: bitnami_orangehrm
    ORANGEHRM_DATABASE_USER: Database user that OrangeHRM will use to connect with the database. Default: bn_orangehrm
    ORANGEHRM_DATABASE_PASSWORD: Database password that OrangeHRM will use to connect with the database. No defaults.
    ALLOW_EMPTY_PASSWORD: It can be used to allow blank passwords. Default: no

Create a database for OrangeHRM using mysql-client

    MARIADB_HOST: Hostname for MariaDB server. Default: mariadb
    MARIADB_PORT_NUMBER: Port used by MariaDB server. Default: 3306
    MARIADB_ROOT_USER: Database admin user. Default: root
    MARIADB_ROOT_PASSWORD: Database password for the MARIADB_ROOT_USER user. No defaults.
    MYSQL_CLIENT_CREATE_DATABASE_NAME: New database to be created by the mysql client module. No defaults.
    MYSQL_CLIENT_CREATE_DATABASE_USER: New database user to be created by the mysql client module. No defaults.
    MYSQL_CLIENT_CREATE_DATABASE_PASSWORD: Database password for the MYSQL_CLIENT_CREATE_DATABASE_USER user. No defaults.
    ALLOW_EMPTY_PASSWORD: It can be used to allow blank passwords. Default: no

PHP configuration

    PHP_MEMORY_LIMIT: Memory limit for PHP scripts. Default: 256M
