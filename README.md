# Bank Marketing Project

Ce dépôt contient le projet de labs sur l'analyse et le clustering du jeu de données Bank Marketing.

Contenu principal
- `Lab 1 - EDA Bank Marketing.ipynb`  : Analyse exploratoire (EDA)
- `Lab 2 - Data Preparation Bank Marketing.ipynb` : Préparation et transformation des données (scalers, feature engineering)
- `Lab 3 - Clustering Bank Marketing.ipynb` : Clustering (k-Means), PCA/MDS/t-SNE et analyses par cluster
- `bank.csv` : Jeu de données original (brut)
- `bank_marketing_prepared.csv` / `bank_marketing_clustered.csv` : sorties de préparation et clustering
- `cluster_profiles.csv` : profils par cluster (moyennes sur l'échelle originale)

Exécution rapide
1. Ouvrez un environnement Python (recommandé: venv). Installer les dépendances basiques:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt  # si présent
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Lancez les notebooks dans JupyterLab / Jupyter Notebook depuis le dossier racine.

Remarques importantes
- Les notebooks ont été préparés pour fonctionner avec les fichiers CSV présents dans ce dossier (`bank.csv`, `bank_marketing_prepared.csv`). Si vous ne voulez pas publier les données en clair sur GitHub, supprimez `bank.csv` et les CSV de sortie avant de pousser ou ajoutez-les à `.gitignore`.
- Si vous souhaitez que je retire les fichiers de données du dépôt (pour rendre le repo public sans données sensibles), demandez-moi "retirer CSV" et je ferai un `git rm --cached` pour les retirer de l'historique suivi, puis je pousserai les changements.

Licence et partage
- Ajoutez un fichier `LICENSE` si vous voulez expliciter les permissions de réutilisation.

Contact
- Pour toute aide supplémentaire (nettoyage de l'historique Git, ajout d'un `README` plus détaillé, création d'un `requirements.txt` ou d'un `environment.yml`), dites-moi ce que vous voulez automatiser.
