# Distances & Géocodage CSV 🚗

Ce projet permet d'enrichir un fichier CSV contenant des adresses en France avec :
- Les coordonnées GPS (via [api-adresse.data.gouv.fr](https://adresse.data.gouv.fr/api))
- La distance en voiture entre les adresses (via [OSRM](http://project-osrm.org/))

## ✅ Exemple d'utilisation

1. Prépare un fichier CSV avec les colonnes :
   - `Adresse départ`
   - `Adresse destination`

2. Lance ce notebook ici :

[![Ouvrir dans Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mmaybon/distances-trajets/blob/main/distances_trajets.ipynb)

3. Upload ton fichier CSV
4. Récupère un fichier `.xlsx` enrichi avec :
   - Latitude / Longitude de départ et destination
   - Distance en km

## 📦 Dépendances

Aucune installation requise si utilisé via Google Colab.
Sinon :

```bash
pip install pandas openpyxl
