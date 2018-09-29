# Docker compose
Oficjalny docker-compose dla napisanych aplikacji

## Wymagania
* [Docker CE v17](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* [DOcker Compose v1.21](https://docs.docker.com/compose/install/)

## Konfiguracja
1. Utwórz plik z konfiguracją o nazwie `.env` o zawartości analogicznej do pliku `.dist.env`
2. Ustaw hasło do aplikacji:
```
AUTH_USER=twoj_login
AUTH_PASSWORD=twoje_haslo
DB_NAME=paraca_inzynierska
```

## Uruchomienie
```
# Przejdź do katalogu z plikiem konfiguracyjnym
$ cd /ścieżka/do/katalogu/z/plikiem/konfiguracyjnym

# Uruchomienie aplikacji w konsoli
$ docker-compose up

# Uruchomienie aplikacji w tle
$ docker-compose up -d

# Zatrzymanie aplikacji działającej w tle
$ docker-compose stop
```
