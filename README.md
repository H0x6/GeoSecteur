# 🗺️GeoSecteur

##🔗Lien:
https://h0x6.github.io/GeoSecteur/

GéoSecteur est un jeu inspiré de GeoGuessr permettant de s'entraîner à localiser les rues d'un secteur donné sur une carte.

Le projet a été conçu principalement pour les sapeurs-pompiers, les forces de l'ordre ou toute personne souhaitant améliorer sa connaissance du réseau routier d'un territoire.

## Objectif

L'objectif est de permettre un entraînement rapide et ludique à la localisation des rues d'un secteur, notamment dans le cadre des interventions des services de secours.

## Fonctionnalités

- Sélection d'une ou plusieurs communes
- Deux modes de jeu :
  - **Mode difficile** : fond de carte neutre sans nom de rue
  - **Mode facile** : fond OpenStreetMap avec les noms de rues
- Nombre de manches personnalisable
- Timer automatique selon la difficulté et le nombre de communes
- Calcul du score en fonction de la distance jusqu'à la rue
- Récapitulatif complet de la partie
- Fonctionne directement dans un navigateur PC ou mobile (aucune installation nécessaire)

## Calcul du score

- 🎯 Moins de **30 m** de la rue : **5000 points**
- Au-delà, le score diminue progressivement selon la distance.
- Les rues sont considérées sur toute leur longueur.

## Temps de jeu

### Mode difficile

| Communes sélectionnées | Temps |
|------------------------|-------|
| 1 à 2 | 45 s |
| 3 à 4 | 1 min |
| 5 et + | 1 min 30 |

### Mode facile

| Communes sélectionnées | Temps |
|------------------------|-------|
| 1 à 2 | 20 s |
| 3 à 4 | 30 s |
| 5 et + | 40 s |

## Utilisation

- Ouvrir le fichier `index.html` dans un navigateur.

ou

- Cliquer sur le lien GitHub Pages en haut de cette note.



## Technologies utilisées

- HTML
- CSS
- JavaScript
- Leaflet
- OpenStreetMap
- Données IGN BD TOPO
- Base Adresse Nationale (BAN)

## Auteur

Conçu par **HB** avec l'aide de **Claude**🤖.
