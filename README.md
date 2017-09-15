# Lamp Docker

### Dockerfile and docker-compose to start php proyects in a clean system.

It has linux, apache, mysql and php7.
For more easy database controll phpmyadmin is added too.

## To use it

**Need docker and docker-compose installed in your system**

` $ docker-compose build`

` $ docker-compose up`

## Expose ports and passwords

```
Phpmyadmin      => port: 8081

                            => user: root
                            
                            => password: wbms

www proyect     => port: 8080 
```