# Reflectie document
## Pre coaching - V1
### Geschatte Progress (in procent): 25%

#### Status:
We zijn eerst gestart met het maken van een domeinmodel en na te denken over de klassen. 
Dat ging vrij vlot, toen we voldoende hadden gewerkt aan het domeinmodel (eind week 1) zijn 
we begonnen met het starten van onze drie projecten (bakery, client en warehouse). We hebben
daarna de databank geconnecteerd en dit lukte vrij vlot. We hebben dan ook de eerste versie en
schatten dat we ongeveer aan een 25% zitten.

#### Stories
[48. Als systeem wil ik gefinaliseerde producten, met hun details, uitsturen naar andere partijen.]
We weten niet goed hoe we de verschillende applicaties gaan laten communiceren met elkaar.

#### Quality
[37. Bereid de codebase voor op toekomstige verbeteringen.] We hebben onze code zo flexibel mogelijk
proberen te maken a.d.h.v. de SOLID principes.

#### Vragen
[35. Als systeem wil ik nieuwe ingrediënteninformatie ontvangen.] Is dit voldoen om een API
te maken die enkel de naam van het ingrediënt verwacht?

[26. Bereik een coderegeldekking van ten minste 60%.] Wat wordt hier juist mee bedoelt?

### POST Coaching V1
-   Interfaces voor services
-   RabbitTemplate niet gebruiken in REST-controller
-   Geen HTTP of messaging verkeer 
-   Altijd DTO's gebruiken
-   Error handling maken

## Pre coaching - V2
### Geschatte Progress (in procent): 80%

#### Status:
We hebben de meeste stories afgewerkt en hebben de meeste bugs opgelost.
We zijn ook begonnen aan testen. We gaan nog eens samenzitten om Keycloak op elkaar af te stemmen. Keycloak realm file geeft een error wanneer hij wordt upgeload bij de andere teamlid.

#### Stories
[17. Als klantenbeheerder wil ik de prijs voor nieuwe producten instellen en zo een product aanbieden aan klanten.]
- Met deze US zijn we nog bezig.

#### Quality
[24. Maak unit tests voor loyaliteitsniveaulogica.]
[26. Bereik een coderegelsdekking van ten minste 60%.]
[17. Als klantenbeheerder wil ik de prijs voor nieuwe producten instellen en zo een product aanbieden aan klanten.]

#### Vragen
/


### POST Coaching V2
- Project was goed
- Final touches doen / laatste user stories

## Pre coaching - V3
### Geschatte Progress (in procent): 100%

#### Status:
We hebben alle userstories afgewerkt en hebben de laatste bugs opgelost. We hebben ook de laatste testen geschreven en de code coverage is nu 60%.

#### Stories
/

#### Quality
/

#### Vragen
/


#### Moeilijkheden binnenin het project
- Keycloak
  - Keycloak realm file gaf een error wanneer die werd geupload bij de andere teamlid, opgelost door authentication tijdelijk uit te schakelen en opnieuw te uploaden. Verder hebben we zelf de users handmatig aangemaakt bij het andere teamlid.
- Soms moeilijke debugging door messaging errors

