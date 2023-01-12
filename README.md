# Temperature Sensor

## Sujet 

Bonjour !
Afin d'avoir un apperçu de vos compétences, nous souhaitons avoir une API Rest répondant aux besoins suivants :

1. Une route d'API qui relève la temperature d'un composant TemperatureCaptor et retourne les informations suivantes :
  - Temperature : valeur de la température captée en °C.
  - State : 
    - "HOT" si la température captée est suppérieure ou égale a 30°C
    - "COLD" si la température captée est inférieure a 19°C
    - "WARM" si la température captée est suppérieure ou égale a 19°C et inférieure à 30°C
  - Date : Date de relève de temperature
2. Une route d'API qui permet d'afficher un historique des 15 dernières températures relevées en reprenant le retour de la route précédente.
3. Une route pour redefinir les limites de temperatures pour les trois états : "HOT", "COLD" et "WARM".

## Couche technique obligatoire :
- .NET 6
- SQL Lite
- Docker
- Swagger

Cette liste ne limite pas l'utilisation d'autres outils si vous pensez qu'ils sont un plus pour montrer votre savoir-faire.

## Rendu :
Le rendu doit se faire via une Pull Request sur [GitHub](https://github.com/).
