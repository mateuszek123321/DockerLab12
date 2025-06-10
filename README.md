# Labolatrium 12
Stworzenie docker-compose ze stackiem LEMP.

### Polecenie 1
uruchomienie pliku compose:
docker-compose up -d
![alt text](image.png)

### Polecenie 2
Sprawdzenie działających kontenerów:
docker compose ps
![alt text](image-1.png)

### Polecenie 3
Sprawdzenie sieci 
docker network ls
![alt text](image-2.png)

### Sprawdzenie 
Wyświetlenie strony php: http://localhost:4001
![alt text](image-3.png)
Wyświetlenie phpMyAdmin: http://localhost:6001
![alt text](image-4.png)
Założenie testowej bazy:
![alt text](image-5.png)
### polecenie 4
Zatrzymanie lempa:
docker compose down 
