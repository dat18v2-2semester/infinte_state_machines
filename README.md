# State Machines
Agenda d. 9-10-2018 dat18b

> At anskue software som værende en maskine der på et givent tidspunkt er i én tilstand, og over tid kan ændre tilstand hører under det at designe og kode efter det pricip der kaldes for en tilstands maskine, eller en _State Machine_.

> I dag skal i lære at lave state machine diagrammer og lave deciderede state machines i jeres kode.

## Eksempler
### State Machine Diagram
Et State Machine Diagram består af følgende figurer:

### State Machine eksempel
Problemet der skal løses er at jeg gerne vil have en maskine der kan give adgang til noget login beskyttet materiale. Men i stedet for at hver bruger har et unikt brugernavn og password skal brugeren i stedet have et password der kan være forskellig fra gang til gang, men kravene til passwordet er at det skal afsluttes med et **_@_** tegn efterfulgt af en tilfældig række af **_tal_** og sluttende med et **_#_** tegn. 

Altså for eksempel: 

* Henning@123#
* Hjeningh@123#
* 1234claus@4382984637#
* @1#

#### Diagram
_upload_

#### Kode

````   
  // Indsæt her

````   




## Literatur
* Larman kap. 29.
* https://se.mathworks.com/videos/understanding-state-machines-what-are-they-1-of-4-90488.html
* https://se.mathworks.com/videos/understanding-state-machines-why-use-them-2-of-4-90489.html
* https://se.mathworks.com/videos/understanding-state-machines-mealy-and-moore-machines-3-of-4-90490.html


## Øvelser

<!-- Kom på et ikke alt for kompliceret eksempel, lave et stae machine diagram og omsæt det til kode og vis det for os andre sidst på dagen. -->
