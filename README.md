# Projet Analyse de Données 

Equipe : 
- Nathan Pagnucco
- Thomas Cossic

## Intro : 

Oreiller connecté : Analyse de données pour la détection de la qualité du sommeil à partir des données collectées par un oreiller connecté.

## Methodes utilisées : 


## Etude sur les paramètres : 

En utilisant `DataBrut.describe()` sur le fichier `SaYoPillow.csv`, on obtient les informations suivantes sur les colonnes de données :

| Index | Colonne | Signification | Plage observée | Unité probable |
|---|---|---|---|---|
| 0 | `sr` | **S**noring **r**ate : niveau de ronflement | 45 – 100 | dB |
| 1 | `rr` | **R**espiration **r**ate : fréquence respiratoire | 16 – 30 | respirations/min |
| 2 | `t` | Body **t**emperature : température corporelle | 85 – 99 | °F |
| 3 | `lm` | **L**imb **m**ovement : fréquence des mouvements des membres | 4 – 19 | — |
| 4 | `bo` | **B**lood **o**xygen : taux d'oxygène dans le sang | 82 – 97 | % |
| 5 | `rem` | **R**apid **E**ye **M**ovement : mouvements oculaires | 60 – 105 | — |
| 6 | `sr` (2e) | **S**leeping hours : durée de sommeil | 0 – 9 | heures |
| 7 | `hr` | **H**eart **r**ate : fréquence cardiaque | 50 – 85 | bpm |
| 8 | `sl` | **S**tress **l**evel : niveau de stress (cible) | 0 – 4 | classe |

En utilisant `print(DataBrut["sl"].value_counts())`, on obtient la distribution des classes de stress dans le dataset. On peut voir que toutes les classes sont représentées également.


## Resultats : 


## Conclusion : 

