# Analyse de la Qualité de l'Air au Togo (2020-2025) 

Ce projet vise à analyser la qualité de l'air au Togo à l'aide de **données fictives**. Il utilise des outils d'analyse de données et de visualisation pour explorer les tendances des polluants atmosphériques, identifier les régions les plus touchées et examiner les corrélations entre différents indicateurs environnementaux.

⚠️ **Note importante** : Les données utilisées dans ce projet sont fictives et ont été générées uniquement à des fins de démonstration. Si vous disposez de **données réelles et fiables**, je serais ravi de collaborer pour enrichir ce projet avec des analyses basées sur des données authentiques.

---

## Table des matières
1. [Contexte](#contexte)
2. [Fonctionnalités](#fonctionnalités)
3. [Technologies utilisées](#technologies-utilisées)
4. [Structure du projet](#structure-du-projet)
5. [Installation et exécution](#installation-et-exécution)
6. [Contributions](#contributions)
7. [Licence](#licence)

---

##  Contexte

La qualité de l'air est un enjeu majeur pour la santé publique et l'environnement. Ce projet a été réalisé dans le cadre d'une mise en pratique 
des compétences acquises lors d'un cours d'analyse de données. Bien que les données utilisées soient fictives, ce projet démontre les capacités d'analyse et 
de visualisation pour des données réelles.

---

##  Fonctionnalités

- **Nettoyage et transformation des données** :
  - Suppression des valeurs manquantes.
  - Conversion des colonnes en types numériques.
  - Normalisation des noms de colonnes.

- **Analyse des données** :
  - Moyennes des polluants par région.
  - Tendances temporelles des polluants (2020-2025).
  - Corrélations entre les indicateurs environnementaux.
  - Comptage des dépassements du seuil de PM2.5 (25 µg/m³).

- **Visualisations** :
  - Graphiques en séries temporelles.
  - Diagrammes en barres.
  - Heatmaps de corrélations.
  - Graphiques de dispersion (scatter plots).

- **Génération d'un rapport PDF** :
  - Résumé des données.
  - Tableaux des moyennes et des dépassements.
  - Inclusion des graphiques générés.

---

## 🛠️ Technologies utilisées

- **Python** :
  - `pandas` : Manipulation et analyse des données.
  - `numpy` : Calculs numériques.
  - `matplotlib` et `seaborn` : Visualisation des données.
  - `pathlib` : Gestion des chemins de fichiers.
  - `reportlab` : Génération de rapports PDF.

---

##  Structure du projet

* code_qualite_air.ipynb : Notebook principal contenant le code
* qualite_air_togo.csv : Fichier de données fictives
* output_qualite_air : Dossier contenant les résultats générés
  - Rapport_Qualite_Air_Togo.pdf : Rapport PDF généré
  - Graphiques (fichiers PNG) : Graphiques générés 


Tous les **résultats générés** (graphiques et rapport PDF) se trouvent dans le dossier `output_qualite_air`.

---

##  Installation et exécution

### Prérequis
- Python 3.8 ou supérieur
- `pip` pour installer les dépendances

### Étapes

1. Clonez le dépôt GitHub :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-projet.git
   cd votre-projet

2. Installez les dépendances :
pip install -r requirements.txt

3. Exécutez le notebook :
Ouvrez code_qualite_air.ipynb dans Jupyter Notebook ou VS Code.
Exécutez les cellules pour générer les résultats.

4. Les résultats (graphiques et rapport PDF) seront générés dans le dossier output_qualite_air.


## 🤝 Contributions
Les contributions sont les bienvenues ! Si vous disposez de données réelles et fiables sur la qualité de l'air au Togo ou ailleurs, n'hésitez pas à les partager pour enrichir ce projet.

1. Forkez le dépôt.
2. Créez une branche pour vos modifications : git checkout -b feature/nom-de-la-fonctionnalité
3. Faites un commit : git commit -m "Ajout d'une nouvelle fonctionnalité"
4. Poussez vos modifications : git push origin feature/nom-de-la-fonctionnalité
5. Créez une Pull Request.

## Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le distribuer, à condition de mentionner l'auteur original.

## Contact
Pour toute question ou suggestion, vous pouvez me contacter via LinkedIn : https://www.linkedin.com/in/kodjo-isac-gbesse-1929a52a7
ou ouvrir une issue sur le dépôt GitHub.
