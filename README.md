# TicTacTrip-SamiChebbi
# Crunching de data

# Introduction

---

Nous ne nous attendons pas à un résultat parfait car l’exercice peut être infini, le but est de tester tes capacités d’apprentissage et ta motivation.

Plus tu vas loin, mieux ce sera !

# Objectifs

---

- Extraire des infos intéressantes type :
    - prix min, moyen et max
    - durée min, max, moyenne par trajet
- Différence de prix moyen et durée selon le train, le bus et le covoit selon la distance du trajet
    
    Par exemple (0-200km, 201-800km, 800-2000km, 2000+km)
    
- Le plus d’infos bonus !
    
    Comme par exemple :
    
    *Graphes, prédictions de prix, rapport des soucis relevés dans les données, visualisation interactive, sourcing & utilisation de données externes pertinentes, utilisation d’API externes*
    

Langage requis : **Python** + le package **Pandas** 

# Les données

---

[stations.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c021fc0b-4fe0-418e-8948-78d66ed14a6d/stations.csv)

[providers.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/12eab515-ffe1-4c3a-ba00-67527ceb7774/providers.csv)

[cities.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/48f2456d-f1ef-444e-8a0d-3ef60bed5753/cities.csv)

[ticket_data.csv](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/164d0bc3-e1ec-4e96-b3a5-fb59ba7ef88b/ticket_data.csv)

- ***ticket_data.csv*** : Contenant un historique de ticket (une ligne => une proposition de ticket sur tictactrip)
- ***cities.csv*** les villes desservies par tictactrip (lien grâce aux colonnes o_city (origin_city), d_city (destination_city) de ticket_data)
- ***stations.csv*** les stations desservies par tictactrip (lien via o_station, d_station de ticket_data)
- ***providers.csv*** infos sur les différents providers (lien via company de ticket_data)Un provider est une "sous-compagnie". Par exemple TGV et TER sont deux providers de VSC (voyages-sncf).

