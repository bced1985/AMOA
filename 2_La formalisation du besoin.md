# La formalisation du besoin

Après analyse du besoin, je répère les grandes entités qui interagiront au sein de l'applicatif.

Pour chaque entité, je rédige : une définition, la liste de ses attributs, les règles métiers et de gestion.

## L'entité Propriétaire particulier

### Définition :
Un propriétaire particulier est une personne physique, qui possède un bien; et qui décide d'en confier la gestion à l'agence immobilière.

### Liste des attributs
identifiant, nom, prénom, genre, date de naissance, profession, adresse, ville, pays, téléphone, adresse électronique

### Règles métiers et de gestion
Un particulier peut confier plusieurs biens immobiliers à l'agence immobilière.

Un bien immobliier ne peut appartenir qu'à un seul propriétaire.

Un propriétaire particulier doit être majeur (avoir plus de 18 ans).

L'identifiant doit être unique.
