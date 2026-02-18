# sfp_analysis

## Étape 1
Clustering des microprotéines selon :
- hydrophobic profile TMD
- aromatic face distribution
- charge distribution

## Étape 2
Projeter ces clusters sur :
- différentes classes GPCR (A/B/C)
- différents environnements membranaires

## Étape 3
- Simuler seulement les combinaisons les plus compatibles
- Ça réduit l’espace de recherche.

Ce que je peux reprendre : 

| Élément du rapport                | Intérêt | Niveau    |
| --------------------------------- | ---------------- | --------- |
| Harmonisation TMD DeepTMHMM/TMHMM | Oui              | Moyen     |
| Profil hydrophobe + MSE           | Oui              | Fort      |
| Projection cylindrique            | Oui              | Très fort |
| Grid multi-copy script            | Oui              | Très fort |
| PyLipID occupancy                 | Oui              | Très fort |
| Lipid droplet spécifique          | Partiel          | Faible    |



## Stratégie intelligente
je reprendrais :
- Projection cylindrique
- Profil hydrophobe comparatif
- CG-MD multi-copy GPCR + microproteins
- PyLipID interaction mapping

Et je ferais :

“Predicting GPCR–microprotein interaction propensity using biophysical surface complementarity and CG-MD validation”
