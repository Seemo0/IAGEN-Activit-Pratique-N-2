# Activité pratique n°2 — Modèles génératifs

**Nom :** Mohamed Ouallal  
**Classe :** IADATA — Groupe 4  
**Enseignant :** Mohamed YOUSSFI

## Étape 1 — Configuration

Le projet utilise Python 3.11 et UV. Les dépendances et leurs versions sont enregistrées dans `pyproject.toml` et `uv.lock`.

Avec UV installé, ouvrir un terminal dans `partie2` :

```bash
uv sync --locked
source .venv/bin/activate
```

Dans VS Code, ouvrir [Activite_2_MNIST.ipynb](Activite_2_MNIST.ipynb), puis choisir **Select Kernel → Python Environments → partie2/.venv/bin/python**. La première cellule vérifie la version de Python et les imports.

Les deux notebooks `Modeles_generatifs_pytorch*.ipynb` sont conservés comme références du cours.

Le chargement de MNIST et les modèles seront ajoutés aux étapes suivantes.

L’environnement virtuel, les données téléchargées et les poids des modèles sont exclus de Git.
