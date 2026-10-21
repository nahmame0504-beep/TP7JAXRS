# TP 7 : Services Web RESTful avec JAX-RS / Jersey et Spring Boot

Ce projet est une application Java basée sur **Spring Boot** démontrant la création d'API Web RESTful avec la spécification **JAX-RS** (implémentation **Jersey**).

##  Technologies Utilisées

* **Java 17**
* **Spring Boot 3.x**
* **Jersey (JAX-RS)** - Framework pour API REST
* **Spring Data JPA** - Gestion de la persistance
* **H2 Database** - Base de données en mémoire
* **Lombok** - Réduction du code boilerplate (Getters/Setters/Constructeurs)
* **Maven** - Gestion des dépendances

---

##  Structure du Projet

```text
TP7JAXRS/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.tp7jaxrs/
│   │   │       ├── config/           # Configuration Jersey (ResourceConfig)
│   │   │       ├── entities/         # Entités JPA (Compte)
│   │   │       ├── enums/            # Énumérations (TypeCompte)
│   │   │       ├── repositories/    # Interfaces Spring Data JPA
│   │   │       ├── web/             # Endpoints JAX-RS (CompteRestJaxRSAPI)
│   │   │       └── Tp7JaxrsApplication.java # Classe principale
│   │   └── resources/
│   │       └── application.properties # Configuration de l'application & H2
│   └── test/
├── postman/                         # Collection Postman pour tester les requêtes
└── pom.xml
```

<img width="1917" height="882" alt="image" src="https://github.com/user-attachments/assets/56d7dd19-7166-424b-ac1b-9b7ff7614bdd" />

<img width="1497" height="895" alt="image" src="https://github.com/user-attachments/assets/ca3e44b7-10ec-449b-af48-c08722e79c02" />
<img width="1587" height="822" alt="image" src="https://github.com/user-attachments/assets/e01e84dd-f7ed-41c1-854e-a65a014beb64" />
<img width="1527" height="887" alt="image" src="https://github.com/user-attachments/assets/3a96b2d5-aea0-4163-a1c8-716151992de8" />
<img width="1476" height="815" alt="image" src="https://github.com/user-attachments/assets/11cabac5-db65-43ce-99b7-7adf92b5935d" />
<img width="1518" height="906" alt="image" src="https://github.com/user-attachments/assets/f760b59a-f9a8-43cf-ae95-41c1da61b0bb" />
<img width="1161" height="707" alt="image" src="https://github.com/user-attachments/assets/c95071d4-d614-4c44-80d4-bfc01c78f33c" />
