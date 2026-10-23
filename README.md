# INF8111 — TP2

Travail d'équipe organisé en deux parties :

- `Partie1/TP2_A26_Partie1/` : notebook de la partie 1 et `workflow.pdf`.
- `Partie2/TP2_A26_Partie2/` : notebook de la partie 2 et `Instructions_GCP.pdf`.

## Données locales

Les dossiers `data/` sont ignorés par Git pour éviter de versionner les jeux de données volumineux. Les fichiers restent sur votre ordinateur, mais ne sont pas inclus dans un clone du dépôt.

Après avoir cloné le dépôt, récupérez les données fournies avec le TP et placez les fichiers suivants dans `Partie1/TP2_A26_Partie1/data/` :

- `DATA.csv`
- `GroceryDataset.csv`
- `OBSERVATIONS.csv`
- `OBSERVATIONS_extract.csv`
- `SYMPTOMS.csv`
- `VAX.csv`
- `note.txt` (description des colonnes)

Utilisez tous la même copie des données du TP. Consultez les notebooks et les PDF pour les consignes d'installation et d'exécution.

## Travail en équipe

Une fois le dépôt partagé sur GitHub ou GitLab :

1. Clonez le dépôt et ajoutez les données localement.
2. Avant une nouvelle tâche, partez d'une branche `main` à jour (`git switch main`, puis `git pull`).
3. Créez une branche pour votre tâche, par exemple `git switch -c partie1-question1`.
4. Enregistrez vos modifications avec `git add <fichiers>` puis `git commit -m "Description des modifications"`.
5. Publiez votre branche avec `git push -u origin partie1-question1` et ouvrez une pull request.

Répartissez le travail pour éviter de modifier le même notebook en parallèle : les conflits dans les fichiers `.ipynb` sont difficiles à résoudre. N'ajoutez pas de clés de service GCP ni d'autres identifiants au dépôt.
