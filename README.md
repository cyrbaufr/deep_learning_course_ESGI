# deep_learning_course
Repo contenant des notebooks python dans le cadre du cours de Deep Learning de l'ESGI

## Prérequis

- Docker installé (Docker Engine, Docker Desktop, etc.)
- Docker Compose (inclus dans Docker Desktop récent)

## Première utilisation

Cloner ce dépôt. Exécuter la commande suivante dans un terminal:

   ```bash
   git clone https://github.com/cyrbaufr/deep_learning_course_ESGI.git
   cd deep_learning_course_ESGI
   ```

## Utilisation des notebooks

### Lancement de l'environnement docker

Saisir dans un terminal la commande suivante
```
docker compose up --build
```

### Accès au notebook en local
Ouvrir un browser (ex: Chrome) et copier l'adresse suivante
```
http://localhost:8888

```

### Arrêt
Pour fermer l'environnement, copier dans un terminal
```
docker compose down
```