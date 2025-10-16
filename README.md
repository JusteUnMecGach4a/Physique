# \#📚 Index de Révision Physique BTS CIEL {#index-de-révision-physique-bts-ciel}

Ce projet est une ressource interactive et organisée destinée aux
étudiants en BTS Cybersécurité, Informatique et réseaux, Électronique
(CIEL) pour réviser efficacement les concepts fondamentaux de la
physique appliquée.

L\'index se décompose en chapitres thématiques, chaque chapitre
détaillant les définitions, les lois, les formules clés (rendues avec
KaTeX) et les capacités exigibles du programme.

## \#🚀 Technologies Utilisées {#technologies-utilisées}

Ce projet est une application web monopage (SPA) statique et légère,
conçue pour être consultée rapidement sur n\'importe quel appareil.

- HTML5 : Structure sémantique de base.

- Tailwind CSS : Framework CSS utilisé pour le style et le design
  > responsive.

- KaTeX : Bibliothèque JavaScript légère et rapide pour le rendu des
  > formules mathématiques (LaTeX).

## \#🗺️ Structure des Chapitres {#structure-des-chapitres}

L\'index est divisé en quatre chapitres principaux, chacun ayant son
propre fichier HTML pour une navigation claire.

| **Fichier HTML**                     | **Chapitre**                                | **Thèmes Principaux**                                                                      |
|--------------------------------------|---------------------------------------------|--------------------------------------------------------------------------------------------|
| chapitre0_lois_fondamentales.html    | 0\. Lois Basiques & Circuits Fondamentaux   | Ohm, Kirchhoff, Puissance, Associations de Résistances (DC).                               |
| chapitre1_analyse_temporelle.html    | 1\. Analyse Temporelle des Signaux          | Période, Fréquence, Valeur Moyenne, Efficace, Déphasage, Représentation Sinusoïdale.       |
| chapitre2_analyse_frequentielle.html | 2\. Analyse Fréquentielle des Signaux       | Séries de Fourier, Spectre de Raies, Niveaux dB (dBV, dBm), TDH.                           |
| chapitre3_circuits_sinusoidaux.html  | 3\. Circuits Linéaires en Régime Sinusoïdal | Notation Complexe, Impédances Z_R, Z_L, Z_C, Théorèmes (Thévenin/Norton en AC), Résonance. |
| index.html                           | Index Principal                             | Page d\'accueil et liens vers tous les chapitres.                                          |

## 🛠️ Installation et Utilisation {#installation-et-utilisation}

Ce projet ne nécessite aucune installation de dépendances.

1.  **Clonage du répertoire :**  
    > git clone \[URL_DE_VOTRE_REPERTOIRE\]

2.  Ouverture :  
    > Ouvrez simplement le fichier index.html dans votre navigateur web
    > préféré.

## ✅ Comment Contribuer {#comment-contribuer}

Les contributions sont les bienvenues ! Si vous trouvez une erreur,
souhaitez ajouter une formule, ou proposer un nouveau chapitre (par
exemple, Optique ou Thermique) :

1.  **Fork** le projet.

2.  Créez une nouvelle branche pour votre fonctionnalité (git checkout
    > -b feature/nouv-formule).

3.  Commitez vos modifications (git commit -m \'feat: ajout de la
    > formule de Thévenin\').

4.  Poussez la branche (git push origin feature/nouv-formule).

5.  Ouvrez une **Pull Request** détaillée.
