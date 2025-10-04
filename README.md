# REPO-METAMATERIAU-ACOUSTIQUE
ACOUSTIC METAMATERIAL BASED ON RECYCLED PLASTIC BOTTLES

# Helmholtz Interactive — Voilà (notebook)

Notebook interactif : *Helmholtz_Interactive_impedance1.ipynb* & *TMM_Interactive.ipynb*
But : démontrer un résonateur de Helmholtz (modèle d'impédance) avec widgets interactifs — rendu via Voilà.

## Comment lancer 
Cliquez sur le badge Binder ci-dessous pour ouvrir l'interface interactive (pas besoin d'installer Python) :

1) Pour *Helmholtz_Interactive_impedance1.ipynb*: 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fanomezanaalex-arch/REPO-METAMATERIAU-ACOUSTIC/main?urlpath=voila/render/Helmholtz_Interactiver l'impédance1.ipynb)

2) Pour *TMM_Interactive.ipynb*: 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fanomezanaalex-arch/REPO-METAMATERIAU-ACOUSTIC/main?urlpath=voila/render/TMM_Interactive.ipynb)


> Remplace `<GITHUB_USERNAME>` et `<REPO_NAME>` par tes valeurs.

## Fichiers dans ce dépôt
- `Helmholtz_Interactive_impedance1.ipynb` — notebook Voilà-ready.
- `TMM_Interactive.ipynb` — notebook Voilà-ready.
- `requirements.txt` — dépendances Python (utilisées par Binder).
- `data/` — exemples de données (chemins relatifs dans le notebook).

## Notes importantes pour l'auteur
1. Exécuter `Kernel → Restart and Run All` avant de committer pour s'assurer que le notebook s'exécute de zéro.  
2. Éviter les chemins absolus : utiliser uniquement des chemins relatifs (`data/mesures.csv`).  
3. Si Binder échoue, vérifier les logs de build et ajouter les paquets manquants dans `requirements.txt`.

## Licence
(Pas de licence)
