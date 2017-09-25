
# Système d'information intégrée sur la Biodiversité

# Livrable 1: La BD

### Défis 1: Diversité des inventaires


#### 1er slide:

- En partant des types d'inventaires et les données récoltés, on a dresser la liste des champs et conçu la base de données.
- Voici les différents types d'inventaires:
    * végétation
    * sol
    * suivi acoustique
    * carabes
    * phénologie végétale
    * mésocarnivores
    * papillons
    * odonnates

- Défis:
    - Multiples organismes inventoriées
    - Aspect temporelle
    - Aspect spatiales
- Définition des termes utilisées dans la DB: 
    - Sites (lieu géographique constant)
    - Campagne d'inventaires (durée dans le temps)
    - Observations lié à une campagne. 

#### 2e slide:

- Design de la DB: Stockages des données d'inventaires 
    - Schéma centré sur la table de campagnes.
        - Pause: Ajout de site
        - Pause: Ajout de la sous table de données
- Design de la 
        

    
Aspect spatiaux prit en charge par PostgreSQL


- Solution DB
- Présentation des termes en rapport avec le protocole d'échantillonnage
- Destiner à entreposer les données
- Présentation grossière des tables 
- Mapping des champs avec le Darwin core pour une potentielle exportation des données non-sensibles vers d'autres initiatives
- On a une DB, comment insérer/manipuler les données?

### Défis 2: Multiplicité des acteurs/partenaires

- Solution: API
- Définition d'une API
- Trois public: Techniciens (Archivage et prise de données), Biologistes du ministère et Chercheurs (Développement méthodologiques/Analyses), Développeurs externes (Développement d'un tableau de bord à destination du grand public)
- Chacun son point d'accès
    - Portail pour les techniciens et biologistes (Saisie et exploration partielle des données)
    - Package R pour retirer les données (medias + observations) du portail + le calculs des indicateurs (problème, source externes) + 
- Exemple d'application retrait et analyse des données avec R

### Défis 3: Synthèse de l'information

- Solution: Package R, Dashboard

### Défis 4: Arrimage avec les autres SIB

- Solution: Stockage local?, connexion distante?

### C'est quoi les priorités de développement? 
### Qu'est ce que vous voulez en premier?