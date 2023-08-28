# SITEAU_Scrap

Fichier permettant d'extraire les coupes lithologiques et les pompages d'essai au format `.pdf` à partir de la base de données de forages SITEAU du **Tchad**.

_Vue de la base de données via QGIS :_

![CAR_foragesTopo_Bessada_170x120_250dpi_200000e](https://github.com/SEVES-asso/SITEAU_scrap/assets/4429183/707a5171-4ea0-43de-880f-92be169745e3)

_Résultat d'extraction :_

![image](https://github.com/SEVES-asso/SITEAU_scrap/assets/4429183/16b49f26-be29-4ef2-bc90-479caa288e71)


## Utilisation

- Récupérer la base de données SITEAU (2 options) :
   - soit télécharger la liste des forages sur la page : http://reseau-tchad.org/siteau/coupe_litho/ et copier-coller le tableau de la page dans un fichier `.xlsx` avec la première ligne du tableau (données à jour) ;
   - soit utiliser la base de données à la racine du répertoire GitHub `logs_Forage_TCHAD.xlsx` ;
-  *Recommandé : traitement par un SIG pour ne récupérer que les forages d'intérêt :*
   - *enregister la base de données au format `.csv` ;*
   - *sélectionner les forages d'intérêt dans le SIG et sauvegarder la sélection dans un fichier `.xlsx` ;*
- Lancer `SITEAU_scrap.ipynb` pour collecter les coupes lithologiques et pompages d'essai de la base de données SITEAU.

