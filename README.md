# Mise-en-oeuvre-des-architectures-micro-services-Docker
# Présentation du projet :
Mise en oeuvre d'une application distribuée basée sur deux micro-services:
  - Couches DA0, Service, Web, DTO
  - Utilisation de MapStruct pour le mapping entre les objet Entities et DTO
  - Génération des API-DOCS en utilisant SWAGGER3 (Open API)
  - Communication entre micro-services en utilisant OpenFeign
  - Spring Cloud Gateway
  - Eureka Discovery Service
# Structure du projet :

![image](https://user-images.githubusercontent.com/86124754/198901595-9c9803ab-4dc5-45fe-8a28-96b3612fa4c9.png)

# Création des micro-services :
## Customer-Service :
### Structure du Service:

 ![image](https://user-images.githubusercontent.com/86124754/198901939-426a5b84-1a0d-4ca3-a5de-5c88f89d4dc9.png)
 
### Open API Customer-Service:
 
 ![image](https://user-images.githubusercontent.com/86124754/198902397-918982a4-abc8-4c0a-b794-94309f71c049.png)
 
 ### Base de données h2:
 
 ![image](https://user-images.githubusercontent.com/86124754/198903065-9892def2-18c5-4ad3-a1f4-40641520057b.png)

 
## Billing-Service :
### Structure du Service:

![image](https://user-images.githubusercontent.com/86124754/198902502-01d13bc7-8d71-4052-8df1-bc8170212089.png)

### Base de données h2:

![image](https://user-images.githubusercontent.com/86124754/198903119-7d4f0dd8-e539-42b4-995d-8beb846140e7.png)

 
### Open API Customer-Service:

![image](https://user-images.githubusercontent.com/86124754/198902959-4e128f5e-4d8a-4e27-b37e-3baa72c07f60.png)

# Communication entre micro-services en utilisant OpenFeign:

![image](https://user-images.githubusercontent.com/86124754/198903213-a7a79a36-8747-4d4b-928c-a7c68c6f0430.png)

# Spring Cloud Gateway:

![image](https://user-images.githubusercontent.com/86124754/198903264-439867ea-8551-496d-8ab1-87e9df53d58d.png)

# Eureka Discovery Service:

![image](https://user-images.githubusercontent.com/86124754/198903310-b476060f-e26e-4dd9-9258-cfa938d8540a.png)

![image](https://user-images.githubusercontent.com/86124754/198903422-4acb2967-d846-44c7-bdcd-c4b9a0950603.png)

# Utiliser docker-compose
## Extraire Les fichiers jar

![image](https://user-images.githubusercontent.com/86124754/198904334-1620dae8-fbc9-4c28-861d-c6ba068a8e60.png)
 
##  Créer les fichiers Docker

![image](https://user-images.githubusercontent.com/86124754/198904426-80d2b21d-d1c8-4e72-a587-f6a0aa916a00.png)
![image](https://user-images.githubusercontent.com/86124754/198904674-7e28df37-f608-4326-9cca-b368a25210cb.png)


##  Création de fichier docker-compose.yml 

![image](https://user-images.githubusercontent.com/86124754/198904775-b4abdc24-2fb0-492d-9840-4f2f5647c463.png)

![image](https://user-images.githubusercontent.com/86124754/198904806-7c3cc1a7-41e4-49ae-ad70-4aba1c90a7d8.png)

## Création des images

![image](https://user-images.githubusercontent.com/86124754/198904877-c3871a17-17d3-4071-9238-9b3ea23b3a5f.png)

## Création des  containers 

![image](https://user-images.githubusercontent.com/86124754/198904950-41b0cda1-31d6-4778-bed6-2524fbf838cd.png)



















 
 
 
 
