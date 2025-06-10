# Etape1_LOG430
Rassemblement des labs 0, 1 et 2 en plus de l'interface web pour le lab 2

# Rapport disponible
- En version `.pdf` à la racine de ce projet.
- En version `.md` dans `./Lab2_LOG430/docs_lab2`

# Étapes complètes pour tester le logiciel sur un navigateur à partir du fichier .zip fraichement décompressé

- Ouvrir un teminal
## Lancer le serveur Flask pour le backend ?
- `cd ./Lab2_LOG430/Docker`
- `docker compose down && docker compose build --no-cache && docker compose up`


- Ouvrir nouveau teminal
## Lacer le serveur node pour le frontend
- `cd ./Frontend_Lab2_LOG430`
- `npm i`
- `npm run start`
- Aller sur un navigateur et entrer dans la barre d'adresse `http://localhost:8000/`

- Ouvrir nouveau teminal
## Exécuter les tests
- `cd ./Lab2_LOG430`
- `pytest tests/`

# Étapes le logiciel sur un navigateur à partir de la VM du projet
J'ai pas réussir à tout avoir qui fonctionn bien sur la VM. Pour tester le projet, prière de se référer au .zip remis le 9 juin.