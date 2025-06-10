# Etape1_LOG430
Rassemblement des labs 0, 1 et 2 en plus de l'interface web pour le lab 2

# Rapport disponible
- En version `.pdf` à la racine de ce projet.
- En version `.md` dans `./Lab2_LOG430/docs_lab2`

## Lancer le serveur Flask pour le backend ?
- `cd ./Lab2_LOG430`
- `docker compose down && docker compose build --no-cache && docker compose up`

## Lacer le serveur node pour le frontend
- `cd ./Frontend_Lab2_LOG430`
- `npm i`
- `npm run start`
- Aller sur un navigateur et entrer dans la barre d'adresse `http://localhost:8000/`

## Exécuter les tests
- `cd ./Lab2_LOG430`
- `pytest tests/`