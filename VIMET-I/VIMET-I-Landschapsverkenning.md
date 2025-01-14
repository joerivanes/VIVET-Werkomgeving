## Landschapsverkenning

### Inleiding

Kennis over energie-installaties is van belang voor de energietransitie. In
het huidige energiedomein zijn de energienetten een centrale component en daarom
wordt vaak gesproken in termen van vóór en achter de meter, resp. de wereld van
netbeheerders en de wereld van de apparaten die energie invoeden op of afnemen
van het netwerk. Het netwerk maakt het mogelijk dat er een energiemarkt bestaat
waar energieleveranciers zorgen dat de energie die zij inkopen weer verkocht
wordt en dat afnemers een leverancier of producent kunnen kiezen. De apparaten
die verbonden zijn aan het netwerk - dat is wat we in deze verkenning verstaan onder 'energie-installatie' - staan vaak opgesteld in gebouwen, en hebben in ieder geval een locatie. 

Ziehier het speelveld: het energiedomein, de bouw- en installatiewereld en de
basisregistraties (denk aan de BAG). Domeinen waarin veel partijen affiniteit
hebben met de energietransitie. Domeinen die omvangrijk zijn, in toenemende mate
internationaal georiënteerd en met complexe informatievraagstukken.

Dit document is een aanzet tot ordening van wat er in die domeinen gebeurt op
het gebied van 'infotools' in het bijzonder afsprakenstelsels / projecten / data / standaarden /
informatiemodellen / taxonomieën, daar waar een verbinding bestaat met
installaties in het energiedomein. 

De afbakening en inventarisatie is gebaseerd op ‘common sense’ en op kennis die
in de context van VIVET is opgedaan en opgehaald. De eerste aanzet tot dit
speelveld is getoetst, uitgebreid en verdiept in de kick-off workshop met
experts uit de verschillende domeinen bij Geonovum op 10 februari 2020 en in
aanvullende workshops waarin is ingezoomd op specifieke onderwerpen.

Tijdens alle workshops bleek dat de aanwezigen de problematiek herkenden, de
behoefte voelden om met dit werkveld aan de slag te gaan, nieuwsgierig waren
naar mogelijke verbindingen met andere domeinen, en ook de waarde ervan zagen
voor de energietransitie. De betrokken partijen hebben aangegeven bij te willen
dragen aan de concretisering van het informatiemodel energie-installaties ten
behoeve van de energietransitie.

Deze voorstudie heeft qua data-objecten enige overlap met project VIVET-D, waaarin de viewers geanalyseerd worden. Zie bijlage 10 voor een overzichtsplaat, waarin in de linker kolom vele datasets als bronnen voor de viewers zijn opgenomen. Ondanks de overlap met VIVET-D - er zijn ook viewers die informatie serveren over opwek-installaties - is deze voorstudie  echter aanvullend omdat de focus niet ligt op: nut en noodzaak van de presentatie van de gegevens, maar op het inzichtelijk maken en waar mogelijk verbeteren van de onderliggende verbanden tussen die datasets. Een relevant verschil is, dat de viewers in VIVET-D als scope het energiesysteem hebben, terwijl in deze voorstudie daarnaast ook de installatie- en bouwwereld figureren. 
Evenzo is deze voorstudie aanvullend op VIVET-E1, waar concreet de inhoud van enkele installatie-gerelateerde registers is bestudeerd, terwijl in deze voorstudie het formaat en de gehanteerde informatie-tooling onderwerp is. 

Voor deze inventarisatie is geput uit onderstaand materiaal, dat grotendeels is
opgenomen in de bijlagen bij dit document.

-   Een uitgebreide inventarisatie van Jeroen Baltussen (RVO/Geonovum) en Remco
    van der Linden (Techniek Nederland), genaamd ‘Speelveld installatieregister
    energie-installaties' was de start van dit document;

-   De in die inventarisatie opgenomen informatiebehoeften van
    energie-installaties in beleidstukken (Jan Bruinenberg - Alliander,
    Netbeheer NL);

-   De inventarisatie van typen installaties en parameters voor gebouwen en
    netten (EG-ETRM)

-   Uit bouw- en installatiewereld: documenten van Techniek Nederland, de Atlas
    van Open BIM Standaarden 1.3.

### Stakeholders

Van de volgende organisaties zijn informatie-experts betrokken geweest bij deze
voorstudie:

Energiedomein: Alliander, Stedin, EDSN

Overheid: CBS, RVO, RWS Leefomgeving, RIVM, PBL, Geonovum

Kennisinstellingen: TNO

Bouw- en Installatiewereld: Techniek Nederland

Modelbouwers: ExpertGroep EnergieTransitieRekenModellen

Zie ook [Bijlage 8](#bijlage-8) voor een overzicht van de betrokkenen bij deze voorstudie.

### Relevante afsprakenstelsels en projecten

#### Afsprakenstelsels


Een afsprakenstelsel is een geschikte infrastructuur voor het op de juiste
schaal *gestructureerd datadelen*; is doorgaans opgebouwd uit een aantal
bouwstenen en kent een sectorale focus en verbinding met andere domeinen.
Afsprakenstelsels worden bij voorkeur ontwikkeld per sector, maar wel
zodanig dat je ze kunt verbinden met andere sectoren omdat dit nieuwe usecases
oplevert, bijv. Energie gecombineerd met Bouw/Installatie, of Energie gecombineerd met Mobiliteit. Er wordt 
naast afsprakenstelsel, ook wel gesproken over een datastelsel; dat is bijvoorbeeld uitgewerkt in het rapport over
datadeel-initiatieven voor het MKB rapport "Generiek afsprakenstelsel voor
datadeelinitiatieven als basis voor de [digitale economie](https://www.rijksoverheid.nl/documenten/rapporten/2018/12/30/generiek-afsprakenstelsel-voor-datadeelinitiatieven-als-basis-van-de-digitale-economie)", 
dat is opgesteld in opdracht van Ministerie van EZK. Een noodzakelijke voorwaarde om dit tot een
succes te maken is de bereidheid tot kennisuitwisseling bij alle betrokken partijen. Het afsprakenstelsel
dat in dat rapport is beschreven bestaat uit 9 bouwstenen die noodzakelijk zijn voor de opzet
van een datadeelcoalitie. Voor deze voorstudie naar enegie-installaties is vooral bouwsteen 7 van belang:
interoperabiliteit van metadata (p.81 en p.84-90 vv.).  
De kenmerken van het afsprakenstelsel zijn beschreven op p. 103-105, en
ontwikkelingsrichtlijnen op p. 106.  
Zie [Bijlage 2](#bijlage-2) voor enkele relevante schema’s uit dit
afsprakenstelsel en voor enkele schema’s uit de toepassing voor de
energiesector, zoals die is beschreven in [Presentatie toekomstige inrichting
van uitwisseling en governance
energiedata](https://github.com/Geonovum/VIVET-Werkomgeving/blob/master/Dossier/Presentatie%20toekomstige%20inrichting%20van%20uitwisseling%20en%20governance%20energiedata.191213.pdf)
door Energie-NL en Netbeheer NL. 

Naast bovengenoemde ontwikkeling door Min EZK ontwikkelt de overheid meer generiek beleid op het gebied van digitalisering ([NL DIGIbeter](https://www.digitaleoverheid.nl/nldigibeter/),
[NL Digitaal](https://www.rijksoverheid.nl/onderwerpen/digitale-overheid/nieuws/2019/03/21/nederland-digitaal-afspraken-voor-betere-samenwerking-digitalisering)). Van belang is, dat hierin is opgenomen een in zomer 2020 op te stellen
[standaardisatieagenda](https://www.digitaleoverheid.nl/actielijn/standaardisatieagenda/), en een verkenning naar cross-sectorale afsprakenstelsels in de [Nederlandse Digitaliseringsstrategie](https://www.rijksoverheid.nl/documenten/rapporten/2018/06/01/nederlandse-digitaliseringsstrategie). 

| Naam                                                                                             | Beschrijving                                                                                                                                                                                                              | Domein            | Opmerking                                                                                                                                                                                                                      |
|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Installatieregister Techniek NL                                                                  | een samenhangend geheel (‘ecosysteem’) van informatie rondom installaties, stelsel van afspraken om informatie uit tal van databronnen te verbinden. Zie ook [Bijlage 7](#bijlage-7) voor een overzicht van de registers. | Bouw Installaties | Bron van data: keuringen, inspecties. Verbinden door open standaarden en classificaties. Verbinden met VIVET en Datastelsel i.k.v. Energiewet 1.0 Proof of Concept door Fluxility                                              |
| Stelsel voor technische producten Bouw en Techniek                                               | NL-SfB Elementenmethode, ETIM Productclassificatie en Sales-berichtenstructuur is een samenhangend stelsel                                                                                                                | Installaties Bouw | sluit aan op bovenstaande                                                                                                                                                                                                      |
| Afsprakenstelsel marktfacilitering                                                               | Afspraken rond data-uitwisseling in het kader van marktfacilitering en energiewet 1.0                                                                                                                                     | Energie           | Initiatief van Netbeheer NL en Energie NL                                                                                                                                                                                      |
| [DigiDealGO](http://www.digidealgo.nl) omvat ook v/h DSBI (Digitaal Stelsel Bouw en Installatie) | Een overeenkomst tussen de overheid, de brancheverenigingen van de bouw, de installatiesector en de toeleverende industrie, gecoördineerd door de BDR (Bouw Digitaliserings Raad), en ondersteund door het BIM-loket.     | Bouw Installaties | Geeft invulling aan DSGO (Digitaal Stelsel Gebouwde Omgeving); hierop zou Informatiemodel Energie-installaties (en activiteiten i.k.v. Energiewet 1.0) kunnen aansluiten. BDR wordt ondersteund door programmateam ‘Digiteam’. |
| BIM -Afspraken                                                                                   | Gefaciliteerd door BIM-Loket                                                                                                                                                                                              | Bouw              |                                                                                                                                                                                                                                |
| [DiS Geo](https://www.geobasisregistraties.nl/basisregistraties/doorontwikkeling-in-samenhang)   | Samenhangende objectenregistraties in Stelsel van Basisregistraties                                                                                                                                                       | Bouw              | Doorontwikkeling in samenhang is initiatief van BZK om de basisregistraties onderling te gaan verbinden en als een stelsel te laten werken                                                                                     |

#### Relevante projecten

In het kader van de energietransitie zijn er veel initiatieven.
Energie-installaties staan daarbij niet los in het energie-informatielandschap.
Installaties staan in gebouwen en gebruiken energie of wekken die juist op.
Onderstaande projecten hebben directe relatie met energie-installaties of
daaraan verbonden (informatie) objecten. De paragraaf [Bevindingen
landschapsverkenning](##bevindingen-landschapsverkenning) bevat een analyse
 hoe deze zich verhouden en meegenomen moeten worden om te komen tot een
informatiemodel voor energie-installaties.

| Naam                                                                                                                                                                                                                                           | Beschrijving                                                                                                      | Domein                      | Opmerking                                                                                                                                                                                                                |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Datastelsel Energieverbruik Utiliteitsbouw](https://www.digidealgo.nl/datastelsel-energieverbruik-utiliteit/)                                                                                                                                 | Energiedossier per gebouw, verbinden EAN/BAG/BRK / benchmarks / gebouwkenmerken / maatregelen                     | Energie Bouw                | Doelgroep: gebouweigenaren, omgevingsdiensten, diensten-leveranciers (software). Door RVO in opdracht van BZK via Platform Duurzame Huisvesting; 1e helft 2020                                                           |
| Digitale dossiers i.k.v. WKB (Wet kwaliteitsborging voor het bouwen)                                                                                                                                                                           | Realiseren uniforme dossiervorming van opgeleverde bouwwerken                                                     | Bouw Installaties           | “Ten minste voor dossier bevoegd gezag en consumentendossier” Bron: [notitie Begeleidingsgroep 17 dec 2019](https://github.com/Geonovum/VIVET-Werkomgeving/blob/master/Dossier/BG%20digitale%20dossiers%2020191217.docx) |
| [Consumentendossier](https://www.rijksoverheid.nl/binaries/rijksoverheid/documenten/kamerstukken/2019/12/09/kamerbrief-over-het-energielabel-en-een-digitaal-woondossier/kamerbrief-over-het-energielabel-en-een-digitaal-woondossier.pdf)     | Dossier dat de aannemer overhandigt met volledig inzicht in het bouwwerk en bijbehorende installaties             | Bouw Installaties           | Verplicht in het kader van de WKB                                                                                                                                                                                        |
| [Digitaal Gebouwdossier](https://www.rijksoverheid.nl/binaries/rijksoverheid/documenten/kamerstukken/2019/12/09/kamerbrief-over-het-energielabel-en-een-digitaal-woondossier/kamerbrief-over-het-energielabel-en-een-digitaal-woondossier.pdf) | Uitwerken concept digitaal gebouwdossier in een startarchitectuur                                                 | Gebouw                      | BZK-initiatief a.h.v. 3 usecases: consumentendossier, dossier bevoegd gezag, het vernieuwde energielabel en het platform verbeterjehuis.nl                                                                               |
| Informatie-behoefte d.m.v. document-analyse                                                                                                                                                                                                    | Analyse van 49 brondocumenten naar informatiebehoeften                                                            | Energie Installaties Gebouw | door Jan Bruinenberg (Alliander / Netbeheer NL) Resultaat: bijna 3000 informatievragen Zie [Bijlage 4](#bijlage-4) voor de onderkende installatietypen                                                                   |
| Gebouwen en installaties tbv rekenmodellen                                                                                                                                                                                                     | Een inventarisatie door EG-ETRM (ExpertGroep EnergieTransitieRekenModellen)                                       | Energie Installaties Bouw   | Installatietypen, parameters, verschillende ruimtelijke schaalniveaus. Zie [Bijlage 5](#bijlage-5)                                                                                                                       |
| EGO Datavoorziening Energietransitie Gebouwde Omgeving                                                                                                                                                                                         | Een hulpmiddel voor gemeenten om de TransitieVisie Warmte op te kunnen stellen.                                   | Energie Bouw                | Initiator: [Programma Aardgasvrije wijken](https://www.aardgasvrijewijken.nl/).                                                                                                                                          |
| PoC voor centraal, geaggregeerd Installatie-Register                                                                                                                                                                                           | Installatieregister                                                                                               | Installaties                | Initiator: [Techniek NL](https://www.technieknederland.nl)                                                                                                                                                               |
| TKI Linked energy data [LinkED](https://projecten.topsectorenergie.nl/projecten/linked-energy-data-00027621)                                                                                                                                   | Het ontwikkelen van een methode voor het komen tot gemeenschappelijke informatiestandaarden en informatiesystemen | Energie                     | Resultaat (gereed) Model Harmonisatie Methodiek (MHM). Initiatief van Netbeheerders en TNO                                                                                                                               |
| UOI: [Unieke Object Identificatie](https://www.geobasisregistraties.nl/actueel/nieuws/2020/03/20/onderzoek-fibree---kadaster---bzk-naar-uoi)                                                                                                   | Internationale koppeling voor gebouwregistraties                                                                  | Bouw                        | BZK-initiatief binnen DiSGeo en gerelateerd aan WKB-verplichtingen (Wet Kwaliteitsborging voor Bouwen)                                                                                                                   |

### Relevante datasets / registraties

De inventarisatie van installatieregisters vindt plaats in het andere
deelproject van project VIVET-E en behoort strikt genomen niet bij dit onderzoek
naar de haalbaarheid van een informatiemodel. De hieronder opgesomde datasets geven weer waar en
door wie de belangrijk gegevensverzamelingen worden bijgehouden. Door deze
datasets inhoudelijk te bekijken ontstaat er ook inzicht in de belangrijkste
entiteiten waarover informatie wordt verzameld.

NB’s:

-   Genoemde datasets als Windkaarten, ThermoGIS en Mestproductie
    (energiepotentie) hebben die verbinding met installaties niet en maken dus
    geen deel uit van de opsomming.

-   Eenduidige datasets over restwarmte worden verwacht in 2020-Q4.

-   De WoOn-dataset van CBS heeft veel gegevens; deze heeft betrekking op een
    zes-jaarlijkse steekproef en is daarom vooralsnog niet in onderstaande lijst
    opgenomen.

-   Er zijn ook registraties tbv CO2-wetgeving (installaties) en tbv
    vergunningen (gemeenten, provincies); eventueel kan onderstaande opsomming
    later nog worden aangevuld.

-   Ook in VIVET-project D (Afstemming en voeding van informatieportalen) 
    is een inventarisatie gemaakt van datasets. Deze is in deze voorstudie nog niet in detail beschouwd; 
    een overzicht is hiervan is te vinden in [Bijlage 10](#bijlage-10). 


| Naam                                                                                                                                 | Beschrijving                                                                                                                                                                | Domein                                                                                | Opmerking                                                                                                                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Stelsel van basisregistraties                                                                                                        | Wettelijk geregelde registraties                                                                                                                                            |                                                                                       | Relevant: o.a. BAG, BGT, BRO, WOZ. In toenemende mate worden deze registraties verbonden, bijv. IV (Landelijke Inventarisatie Vastgoed), Unique ID, DiSGeo, e.d.                                                      |
| CBS Datasets                                                                                                                         | Registraties voor wettelijke taken, zoals bijv. landelijke energiebalans                                                                                                    | Energie Bouw                                                                          | Deze dataset bevat ook productie-installaties (bijv. WKK) dus deels overlap met CERES.                                                                                                                                |
| C-AR Centraal Aansluitregister, beheerd door [EDSN](http://www.edsn.nl)                                                              | Alle aansluitingen aan de elektriciteit- en gasnetten in NL Beheer EDSN namens de netbeheerders NB: *warmte-aansluitingen* zouden integraal hierin opgenomen moeten worden. | Energie                                                                               | Bevat data over de aansluiting en de energielevering. Mutaties via [www.mijnaansluiting.nl](http://www.mijnaansluiting.nl) EAN-code als id. Zakelijke warmte-aansluitingen zijn niet goed in beeld.                   |
| Leidingenregistratie-systemen van de netbeheerders (NB: er zijn ook private netten)                                                  | Toegankelijk via KLIC (Kadaster)                                                                                                                                            |                                                                                       | Elektriciteit en gas is gereguleerd. *Warmte-netten* niet; wel is er meldplicht bij ACM bij \> 10 aansluitingen.                                                                                                      |
| Energie Mgmt Systemen Netbeheerders en warmtebedrijven                                                                               | Metingen van energiestromen                                                                                                                                                 |                                                                                       | Metingen elektriciteit vaak per 5 minuten, gas per uur. Kwantiteiten en kwaliteiten. Doorgaans SCADA-software                                                                                                         |
| Meterregistatie Registratie van elektriciteit- en gasmeters. NB: Complex veld (bijv. huish. vs. zakelijk); evt. precies beschrijven. | Bij EDSN namens de netbeheerders. NB: *warmte-meters* zouden integraal hierin opgenomen moeten worden.                                                                      | [VMNED](http://www.vmned.nl) = Vereniging Meetbedrijven Nederland; behartigt belangen | Kwaliteit van de meters: VMNED en [Sentiunt](http://www.sentiunt.nl) meterbeheer (tbv woningcorp.). NB: voor warmte bestaan ook radiatormeters, bijv. [Techem](http://www.techem.nl).                                 |
| Aansluitingen en verbruik Rijksvastgoed                                                                                              | Register met alle energie-installaties incl. verbruik van de Rijksoverheid (incl. bijv. Defensie)                                                                           | Energie Bouw                                                                          | Beheerd door RWS                                                                                                                                                                                                      |
| CERES Centrale Registratie van Systeem-elementen                                                                                     | Installaties die elektriciteit produceren of verbruiken Beheer: EDSN                                                                                                        | Energie (productie) Energie (verbruik)                                                | Doelgroep: energiesector Opvolger PIR Wettelijke basis: netcode. Er bestaat ook een afzonderlijke [registratie van windturbines](www.windstats.nl).                                                                                                                                                      |
| Register Glastuinbouw CO2-sector                                                                                                     | Beheer: RVO                                                                                                                                                                 | Energie Land- en tuinbouw                                                             |                                                                                                                                                                                                                       |
| Locaties laadpalen                                                                                                                   | Locaties van alle laadpalen in Europa                                                                                                                                       | Mobiliteit                                                                            | [www.eco-movement.com](http://www.eco-movement.com)                                                                                                                                                                   |
| SCIOS Certificatie-registers [www.scios.nl](http://www.scios.nl)                                                                     | Register van o.a. stookinstallaties van 20/100kW – 50 MW                                                                                                                    | Energie                                                                               | SCIOS verzorgt kwaliteitssysteem technische installaties en beheert ook register van eigenaren, certificeerders.                                                                                                      |
| E-MJV (elektronische milieuverslagen) [www.e-mjv.nl](http://www.e-mjv.nl)                                                            | Bevat jaarverslagen van alle (1000) grote inrichtingen in NL die stoffen emitteren. Beheer: RIVM                                                                            | Water Lucht Afval Energie                                                             | Toegang voor: bevoegd gezag (lucht, water), RVO (lucht, water, energie), RWS (controle afvalmodule) Energiemodule: verbruiken, conversies, typen installaties Later: restwarmte? Geen koppelingen tussen inrichtingen. Gebaseerd op Europese normen en bijbehorend (nieuw) [datamodel](https://cdr.eionet.europa.eu/help/eprtr_lcp/Documents/EPRTR-LCP_datamodel_v3.2.pdf) |
| ISDE                                                                                                                                 | Investeringssubsidies Duurzame Energie Beheer: RVO                                                                                                                          | Energie                                                                               |                                                                                                                                                                                                                       |
| Energie-audit EED                                                                                                                    | Registers i.k.v. Energy Efficiency Directive (EU, energieaudits) Beheer: RVO                                                                                                | Energie                                                                               | 6000 bedrijven in NL (incl. MJA- en MEE-bedrijven); energie-audit betreft: energiestromen, energieverbruik (gebouw, processen, vervoer, e.d.) en maatregelen                                                          |
| EIA                                                                                                                                  | Energie-investeringsaftrek Beheer: RVO                                                                                                                                      | Energie Bouw Installaties                                                             |                                                                                                                                                                                                                       |
| EP-online                                                                                                                            | Energielabels Beheer: RVO                                                                                                                                                   | Energie Bouw                                                                          |                                                                                                                                                                                                                       |
| SDE                                                                                                                                  | Subsidie Stimulering Duurzame Energie Beheer: RVO                                                                                                                           | Energie                                                                               |                                                                                                                                                                                                                       |

### Relevante taxonomieën en informatiemodellen

Een *taxonomie* is een geordende classificaties van begrippen in een
toepassingsdomein. Een taxonomie focust op een systematiek en hiërarchie in
begrippen/concepten en vormt een begrippenkader. Moderne toepassingen hiervan
vinden hun weergave in linked data vocabulaires.

*Informatiemodellen* zijn gefocust op beschrijving van gegevens in een
datastructuur. Het basismodel geo-informatie (NEN 3610) definieert een
informatiemodel als een formele definitie van objecten, attributen, relaties en
regels in een bepaald domein
(https://definities.geostandaarden.nl/nen3610/doc/begrip/Informatiemodel).

Door middel van een informatiemodel wordt een informatiekundige beschrijving
gegeven van data binnen een toepassingsdomein die in een digitale omgeving via
berichtenverkeer beschikbaar is en aan- of uitgeleverd kan worden.

Taxonomieën en informatiemodellen kunnen op diverse schaalniveaus worden
toegepast. Voor deze verkenning zijn we geïnteresseerd in standaarden op
nationaal niveau met een informatiedetail dat niet te hoog is maar wel nog
betekenisvol voor operationele toepassing. Internationale standaarden spelen ook
een rol maar vooral daar waar ze al toegepast worden in nationale afspraken.

In de volgende paragrafen zijn de relevante taxonomieën en informatiemodellen
opgenomen. Niet alle zijn overigens uitgewerkt tot operationele standaarden.

#### Taxonomieën

In de bouwsector zijn veel standaarden die een relatie met elkaar hebben. Door
het BIM-Loket zijn deze met elkaar in verband gebracht en zijn de
standaarden/taxonomieën beschreven in de [Atlas van open BIM-standaarden](https://www.bimloket.nl/Atlasvan-open-BIM-standaarden). Zie ook [Bijlage 1](#bijlage-1).

Een belangrijke recente ontwikkeling is de omzetting van de Europese EPBDIII richtlijn naar Nederlandse wetgeving, waarmee eisen worden gesteld aan energie-installaties. Daartoe is o.a. een rekentool ontwikkeld, waarmee energiesystemen gespecificeerd  en doorgerekend kunnen worden. De tool bevat dan ook tal van classificaties voor installaties en onderdelen daarvan, die alle zijn gebaseerd op de norm NTA8800. Een toelichting hierop is te vinden bij [RVO](https://www.rvo.nl/onderwerpen/duurzaam-ondernemen/gebouwen/wetten-en-regels/nieuwbouw/epbd-iii/systeemeisen-technische-bouwsystemen). 

NB: Voorlopig is dat in dit document ondergebracht onder het kopje
‘Taxonomieën/classificaties’ en niet onder ‘Standaarden’.

Een voorbeeld van het verband van standaarden in de bouwsector is:
<!-- ![](media/966611aa83eb1c045a7129876823b224.png) -->

<figure id="966611aa83eb1c045a7129876823b224.png">
    <img src="media/966611aa83eb1c045a7129876823b224.png" alt="">
    <figcaption>Relaties tussen standaarden in de bouwsector</figcaption>
</figure>

Op het gebied van biomassa / biofuels bestaan (internationale)
classificatieschema’s. Deze worden nog nagezocht, o.a. bij Team Biomassa van
RVO.

| Naam                                                                                                                                      | Beschrijving                                                                                                                       | Domein                    | Opmerking                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Lijst met energiedragers](https://www.rvo.nl/sites/default/files/2019/05/Nederlandse%20energiedragerlijst%20versie%20januari%202019.pdf) | Beheer: RVO                                                                                                                        |                           |                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ETIM [www.ketenstandaard.nl](http://www.ketenstandaard.nl) & Stabu & BS&I                                                                 | Product-classificatie voor technische producten bestekken                                                                          | Bouw Installatie          | ETIM wordt beheerd door ‘Ketenstandaard Bouw en Techniek’. Internationaal Ketenstandaard en Stabu gaan fuseren                                                                                                                                                                                                                                                                                                              |
| [NL-SfB](http://www.bimloket.nl/NL-SfB)                                                                                                   | Classificatie van bouwdelen en installaties (‘elementen’)                                                                          | Bouw Installatie          | NL-SfB wordt ook veel gebruikt voor bestekspecificaties, kostenramingen en -calculaties                                                                                                                                                                                                                                                                                                                                                                        |
| [CB-NL](http://www.public.cbnl.org)                                                                                                       | Conceptbibliotheek voor de gebouwde omgeving                                                                                       | Bouw                      | De CB-NL wordt de verbinder tussen bronnen, zoals die van RAW, STABU, NEN, IMGeo, ETIM en Rioned                                                                                                                                                                                                                                                                                                                            |
| [UOB](http://www.openuob.nl) Uniforme objecten bibliotheek Technische installatieproducten o.b.v. ETIM-MC                                 | Een openbare, niet-merkgebonden online bibliotheek van geometrische modellen, waaraan alle fabrikanten producten kunnen toevoegen. | Bouw Installatie          | Wordt beheerd door [2BA](http://www.2ba.nl), dé neutrale datapool van handels- en productgegevens in de installatiebranche. Elk installatiebedrijf kan onafhankelijk van de eigen software de objecten uit de bibliotheek gebruiken voor het ontwerpen van gebouwinstallaties. Met één uniform informatiemodel wisselen de CAD-systemen productinformatie snel en nauwkeurig uit, in elke fase van het bouw- en BIM-proces. |
| [IP 2020](https://www.rvo.nl/onderwerpen/duurzaam-ondernemen/energie-besparen/informatieplicht-energiebesparing)                          | Informatieplicht energiebesparing Beheer: RVO                                                                                      | Energie Bouw Installaties | Overzicht [erkende maatregelen](https://www.rvo.nl/onderwerpen/duurzaam-ondernemen/energie-besparen/informatieplicht-energiebesparing/bedrijven-en-instellingen/erkende-maatregelenlijsten)                                                                                                                                                                                                                                 |
| [Europese codes voor elektriciteit](https://www.tennet.eu/nl/elektriciteitsmarkt/regels-en-procedures/europese-codes/) resp. [Nederlandse codes voor energie](https://www.acm.nl/nl/onderwerpen/energie/de-energiemarkt/codes-energie/actuele-codes-energie)                    | Lijst met de codes met de spelregels voor de Europese elektriciteitsmarkt resp. Nederlandse elektriciteit- en gasmarkt                                                         | Elektriciteit             | Op Europees niveau binnen [ENTSO-E](https://www.entsoe.eu/active-library/) gestandaardiseerd; in Nederland voorgeschreven door ACM                                                                                                                                                                                                                                                                                                                                                                                     |

#### Informatiemodellen

| Naam                                                                                                                                                                       | Beschrijving                                                                     | Domein                         | Opmerking                                                                                                                                                                                    |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| IEC CIM (Common Information Model )                                                                                                                                        | IM voor het elektriciteitsdomein (van assets tot marktmechanismen, etc.)         | Energiesysteem (elektriciteit) | Wereldwijd toegepast, alleen elektriciteit als energiedrager. Doel: informatie-uitwisseling over elektriciteitssysteem. https://en.wikipedia.org/wiki/Common_Information_Model_(electricity) |
| BIM                                                                                                                                                                        | Bouw Informatie Model                                                           | Bouw Installatie               | verschillende definities van BIM: een werkmethodiek, een digitale representatie van alle fysieke en functionele kenmerken van een gebouw.                                                    |
| IFC Industry Foundation Classes                                                                                                                                            | Beschrijft data voor architectuur en bouw                                        | Bouw                           | Zie verder: [en.wikipedia.org/wiki/Industry_Foundation_Classes](https://en.wikipedia.org/wiki/Industry_Foundation_Classes) - relatie met BM                                                  |
| COINS                                                                                                                                                                      | Semantisch datamodel en uitwisselingsformat                                      | Bouw                           | Gebruikt voor o.m. BIM-data, GIS-data, SE-data (Systems Engineering). Uitwisseling semantisch BIM (OWL)                                                                                      |
| CERISE-SG                                                                                                                                                                  | IM-SG                                                                            | Energie Bouw Geo               | Zie [Bijlage 6](#bijlage-6)                                                                                                                                                                  |
|                                                                                                                                                                            | Informatie-model Smart Grids voor energiebalancering                             |                                |                                                                                                                                                                                              |
| ESDL [TNO](https://www.tno.nl/nl/aandachtsgebieden/informatie-communicatie-technologie/expertisegroepen/monitoring-control-services/grip-op-de-energietransitie-met-esdl/) | Open-sourcetaal om informatie voor de energietransitie te beschrijven.           | Energiesysteem                 | Veelal gebruikt bij energie-rekenmodellen.                                                                                                                                                   |
|                                                                                                                                                                            |                                                                                  |                                | [Bijlage 3](#bijlage-3) bevat voorbeeld                                                                                                                                                      |
| [NEN 2660:1996/C1:1996 nl](https://www.nen.nl/NEN-Shop/Norm/NEN-26601996C11996-nl.htm)                                                                                     | Ordeningsregels voor gegevens in de bouw - Termen, definities en algemene regels | Bouw                           |                                                                                                                                                                                              |
| Sales Unifeed                                                                                                                                                              | Standaard berichtensets                                                          | Bouw Installaties              | Met deze berichtensets kan informatie uit UOB en ETIM worden ontsloten.                                                                                                                      |
| IEC 61970 /IEC 61968 / IEC 62325                                                                                                                                           | Set aan standaarden rondom IEC CIM                                               | Elektriciteit                  | Standaard voor informatie-uitwisseling in het elektriciteitsdomein.                                                                                                                          |

### Relevante rekenmodellen

Door enkele deelnemers aan de ExpertGroep EnergieTransitieRekenModellen is ten
behoeve van deze voorstudie een inventarisatie gemaakt van componenten van
energiesystemen en eigenschappen.

Het betreft

-   parameters voor verschillende typen installaties en netten,

-   een overzicht van typen installaties & netten per gebruiksdoel,

-   een lijst van installaties voor energieconversie en
media/966611aa83eb1c045a7129876823b224.png
-   een opsomming van te gebruiken parameters van gebouwen (inclusief kassen &
    schuren), te onderscheiden in drie categorieën: algemeen, schil en
    energiegebruik.

Voor elk van de parameters en installaties/netten is in genoemde spreadsheet
aangegeven op welk ruimtelijk schaalniveau (van pand tot provincie) welke
informatie gewenst is.

De volledige opsomming is te vinden in ModelParametersEnergieTransitie.xlsx. In
[bijlage 5](#bijlage-5) is daar een extract uit weergegeven.

Een interessante ontwikkeling in dat opzicht is het
[Mondaine-project](https://projecten.topsectorenergie.nl/projecten/models-and-data-interface-for-energy-20-00031738)
(Topsector Energie) waarin drie rekenmodellen (ETM van Quintel, Vesta-MAIS van
PBL en PICO van Geodan) verbonden worden: het modelleren van het systeem (ETM)
en de impact op de gebouwde omgeving (Vesta-MAIS) wordt gevisualiseerd (PICO).
De datastromen tussen de modellen worden gemodelleerd met ESDL.
