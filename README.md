# DOCKER COMPOSE PHPMYADMIN MYSQL

## Playground

1. Clone this repository
```
    git clone git@github.com:Escucha-Activa/dockercompose-mysql-phpmyadmin.git
```

2. Change to directory
```shell
    cd dockercompose-mysql-phpmyadmin
```
3. Up the compose
```
    docker-compose up -d
```
4. Access phpmyadmin
```
    your_ip:3307
    Server: mysql
    Username: root/user
    Password: root/user
```
5. Access mysql on terminal
```
    docker exec -it mysql_container_name mysql -u root -p
```

## Stop service
```
    docker-compose stop
```

## Docker phpmyadmin ENV
<table>
<tr>
<td>PMA_ARBITRARY </td>
<td>when set to 1 connection to the arbitrary server will be allowed</td>
</tr>
<tr>
<td>PPMA_HOST </td>
<td>define address/host name of the MySQL server</td>
</tr>
<tr>
<td>PMA_PORT </td>
<td> define port of the MySQL server</td>
</tr>
</table>