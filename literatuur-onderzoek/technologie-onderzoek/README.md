# Technologie onderzoek

## Welke oplossingen zijn er al bedacht om mensen te motiveren om meer te bewegen?

Er zijn al heel wat applicaties bedacht om mensen te laten bewegen, maar er zijn er nog niet heel veel die focussen op kantoormedewerkers. Er zijn een aantal apps die focussen op meer bewegen tijdens kantooruren zoals Stepjockey, Fitcoins en Stridekick. Er zijn ook een hele hoop algemene apps die gewoon focussen op gezonder worden zoals de Fitbit en de Pedometer++. Uit mijn interviews met mijn doelgroep heb ik begrepen dat de doelgroep apps zoals Fitbit en Pedometer++ alleen gebruiken om data in te zien, maar de actieve medewerkers die competetief zijn zullen proberen om hun huidige records te verbreken. 

## Welke technologieën kunnen ingezet worden om gedrag te beïnvloeden?

### Healthapp

De Healthapp van Apple zet alle data om in mooie grafieken waar de gebruiker hun vooruitgang kan zien. Healthapp haalt de data van sensoren die zich bevinden in de iPhone, maar het kan ook data van andere applicaties gebruiken. Applicaties zoals Lifesum registreren het aantal calorieën dat je inneemt elke dag. Healthapp kan dit in een grafiek zetten zodat de gebruiker kan zien of ze genoeg calorieën binnen krijgen.

Elevate haalt de data over het aantal trappen van de Healthapp, maar de Healthapp haalt de data van de Motion & Fitness van Apple. Motion & Fitness houdt alle data bij die geregistreerd worden via de sensoren.

In de huidige versie van Elevate gebruiken we de healthapp om de data over traplopen te weergeven in Elevate. Het werkt nog niet optimaal en ik wil Motion & Fitness onderzoeken om te kijken of we het synchroniseren van data sneller en makkelijker kunnen maken.

### Motion & Fitness

Ik heb een developer van Touchwonders gesproken en ik heb hem gevraagd of het mogelijk is om Motion & Fitness te gebruiken voor Elevate. De huidige versie van Elevate gebruikt de Healthkit om data te verzamelen over het aantal gelopen trappen. Ik heb tijdens de Field trial ontdekt dat het synchroniseren van data een beetje langzaam is. Het duurt even voordat het aantal trappen die je gelopen hebt ook geregistreerd staat in Elevate. Dit heeft bij sommige gebruikers gezorgd voor verwarring, hierdoor dachten ze dat de app niet werkte.

Een ander probleem dat we tegen zijn gekomen is dat Touchwonders niet kan zien of gebruikers toestemming hebben gegeven om data te verzamelen. Stel dat een gebruiker een klacht heeft en zegt dat de Elevate de trappen niet telt dan kan Touchwonders niet zien waardoor het komt. Met Motion & Fitness kunnen de developers zien of de gebruiker toestemming heeft gegeven om data te verzamelen. Mocht een gebruiker toch een probleem tegen komen met het trappen registreren dan kan de developer kijken of ze wel toestemming hebben gegeven. \(Apple, z.d.-a\)

Maar nadat de developer onderzoek heeft gedaan naar Motion & Fitness, zijn we erachter gekomen dat ondanks dat deze framework het beste zou zijn voor Elevate, is het niet mogelijk om deze framework te combineren met geolocatie. Een belangrijke element van Elevate is dat het geolocatie gebruikt om alleen specifiek de trappen te tellen op kantoor en niet de trappen buiten je kantoor om. Tenzij we het concept zouden omgooien, moeten we de Health app blijven gebruiken om data te verzamelen over de trappen.

{% page-ref page="gesprek-met-developer.md" %}

### Beacon

#### Wat is een beacon?

Beacons zijn kleine draadloze transmitters die low-energy Bluetooth technologie gebruiken om signalen te versturen naar smartphones die in de buurt zijn. Ze zijn in eerste instantie ontwikkeld voor marketing in een winkel maar je kan er meer mee doen dan marketing. \(Haines, 2018\)

Apple introduceerde deze technologie in 2013. Het wordt vooral gebruikt als marketing tool voor bedrijven. Als de gebruiker in de buurt van een iBeacon is, dan kan de iBeacon kleine deeltjes versturen naar de smartphone, dat weer een actie triggert in de applicatie.

Als een smartphone een unieke code heeft ontvangen van de iBeacon dan kan het bijvoorbeeld in de applicatie een functie triggeren om een speciale deal te sturen naar de gebruiker. Maar een iBeacon kan ook in een musea gebruikt worden om informatie te versturen over een installatie naar een smartphone. Een iBeacon kan de locatie van je smartphone beter bepalen dan de GPS, dit kan gebruikt worden om te onderzoeken hoe de klanten bewegen in een winkel of musea.

#### Hoe werkt een beacon?

Elke beacon heeft een CPU, radio en batterijen en het werkt door constant een identifier uit te zenden. De identifier wordt opgepikt door een smartphone. Een identifier is een uniek ID nummer dat je samrtphone herkent en dit is ook een unieke nummer van de beacon. Als het eenmaal verbonden is met je device zal het de functie uitvoeren die geprogrammeerd is. \(Haines,2018\)

### Smartwatches

Uit een onderzoek \(Bravata, Smith-Spangler, Sundaram, Gienger, Lin, Lewis & Sierad, 2007\) kan geconcludeerd worden dat het gebruik van een pedometer het lichamelijk activiteit kan verhogen. In een internetartikel \(Donnachie & Hunt, 2017\) wordt verteld dat doelen instellen en zelf-monitoren via een smartwatch een gebruiker kan motiveren om meer te bewegen. Doormiddel van deze inzichten kan ik concluderen dat Elevate in de toekomst ook op smartwatches moet werken. 

### Augmented reality

Augmented reality is digitale interactieve elementen in de echte wereld toevoegen. Deze elementen kun je zien via je telefoon of via een bril. Pokemon Go is een app die gebruik maakt van AR. De gebruiker kan door middel van hun smartphone camera Pokémons zien en vangen. Een ander voorbeeld is de Google SkyMap of de Ikea Place app. De mogelijkheden met AR technologie is eindeloos. \(Reality technologies, 2018\)

## Waarom is technologie de beste oplossing om volwassenen te motiveren om meer te bewegen?

In een blogpost \(Vogel, 2017\) verteld de schrijver dat een activity tracker gebruikers kan helpen om meer te bewegen. Dit komt door een uitdagende aspect tussen vrienden en familie. Toen een vriendin de schrijver uitdaagde om een bepaalde doel te behalen was ze heel erg gemotiveerd om te bewijzen dat ze het kan.

