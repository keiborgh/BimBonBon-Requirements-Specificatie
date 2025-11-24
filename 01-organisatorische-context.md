# _Requirements-specificatie_
***BimBonBon***

Welkom bij de requirements specificatie van BimBonBon!! Wij zijn een chocoladebedrijf dat zich richt op het maken van lekkere, kwalitatieve bonbons voor elke gelegenheid. In dit document leggen we uit welke systemen we nodig hebben om ons werk beter en slimmer te doen. We beschrijven op een duidelijke manier wat het bedrijf nodig heeft, zodat zowel de opdrachtgever als het developmentteam precies weet wat er gebouwd moet worden en waarom.

## Organisatorische Context

## Missie
De missie van BimBonBon is om in al ons werk de hoogste kwaliteit te leveren. Wij geloven dat kwaliteit essentieel is voor succes op zowel de korte als lange termijn. Net zoals een bonbon zorgvuldig wordt gemaakt en een unieke smaakbeleving biedt, streven wij ernaar dat onze resultaten betrouwbaar, goed doordacht en met oog voor detail worden uitgevoerd.  

**Kernpunten missie:**  
- Kwaliteit als standaard, niet als keuze  
- Betrouwbaarheid en precisie in uitvoering  
- Zorgvuldige en creatieve aanpak  
- Ervaring en beleving voor klanten en team  

## Visie
BimBonBon is een naam die staat voor kwaliteit, betrouwbaarheid en creativiteit.. We willen inspireren door te laten zien dat werken met zorg, passie en aandacht niet alleen nu, maar ook op de lange termijn een verschil maakt.  

**Kernpunten visie:**  
- Voorbeeld zijn in kwaliteit en oog voor detail  
- Klanten en partners positief verrassen  
- Creatieve en vernieuwende oplossingen ontwikkelen  
- Langdurige waarde creëren voor team, klanten en partners  

## Strategie

BimBonBon gebruikt een duidelijke strategie om de missie en visie waar te maken. De strategie richt zich op kwaliteit, klantgerichtheid, innovatie en duurzaamheid. Door gericht te werken aan korte- en langetermijndoelen kan het bedrijf zijn merk versterken en een sterke klantrelatie opbouwen.  

### Kernpunten van de strategie
- **Kwaliteit centraal**: Alle producten en diensten voldoen aan hoge kwaliteitsnormen. Dit geldt voor de chocolade, de app en de service.  
- **Klantgericht werken**: Klanten krijgen een persoonlijke ervaring, snelle oplossingen voor vragen en klachten, en relevante informatie over producten en acties.  
- **Innovatie en technologie**: Nieuwe functies zoals productregistratie, gepersonaliseerde aanbevelingen, en virtuele fabriekstours worden continu ontwikkeld.  
- **Duurzaamheid en transparantie**: Productherkomst, certificeringen en duurzame keuzes worden zichtbaar voor klanten via de app en communicatiekanalen.  
- **Data gedreven beslissingen**: Klantgegevens en aankoopgedrag worden gebruikt om producten, promoties en de app steeds te verbeteren.  
- **Community en betrokkenheid**: Klanten worden gestimuleerd om deel te nemen aan de community, recepten te delen, challenges te doen en evenementen te bezoeken.  


## Doelstellingen

## Waarom deze doelstellingen
Deze doelstellingen helpen BimBonBon om klanten blij en trouw te maken, processen makkelijker te laten verlopen en het merk sterker te maken. Door duidelijke korte- en langetermijndoelen kan het bedrijf gericht werken aan vernieuwing en klantvriendelijke oplossingen.

### Binnen 5 maanden
- De mobiele app maken en lanceren, inclusief productregistratie en een overzicht voor klanten.  
- Basisfuncties voor klachten en support beschikbaar maken.  
- Pushmeldingen instellen voor productupdates en seizoensproducten.  

### Binnen 1 jaar
- Persoonlijke aanbevelingen geven op basis van wat klanten kopen en leuk vinden.  
- De app koppelen aan ERP, CRM en BI-tools voor actuele info en klantinzichten.  
- Communityfuncties en spel-elementen toevoegen om klanten meer betrokken te maken.  

### Binnen 3 jaar
- Exclusieve productervaringen aanbieden, zoals proeverijen, workshops en evenementen.  
- Meer duurzame initiatieven tonen en laten zien waar producten vandaan komen in de app.  
- Nieuwe functies toevoegen, zoals AR-proeverijen en virtuele fabriekstours.  

### Doorlopend
- Kwaliteit, betrouwbaarheid en klantgerichtheid blijven verbeteren.  
- Regelmatig updates uitvoeren om nieuwe functies toe te voegen en de app sneller te maken.  
- Klantgegevens analyseren om trends en voorkeuren te volgen en producten te verbeteren. 
  

## Organogram BimBonBon App


Een organogram laat zien hoe de structuur van een organisatie is opgebouwd, wie verantwoordelijk is voor wat, en hoe de communicatie verloopt. Voor het project van de BimBonBon app is het belangrijk om te weten wie beslissingen neemt, wie de uitvoering doet en wie input levert. Zo weet iedereen in het team waar zijn of haar taken liggen en wie moet worden geraadpleegd bij vragen of problemen.

In ons organogram zie je bijvoorbeeld:
- De **raad van commissarissen** die strategische beslissingen neemt.  
- De **algemeen directeur** die alles coördineert en toezicht houdt.  
- De **projectmanager van de app** die verantwoordelijk is voor het ontwikkelen van de app en het aansturen van het team.  
- Het **ontwikkelteam** dat de app programmeert, ontwerpt en test.  
- **Marketing & communicatie** die ervoor zorgt dat klanten weten van de app en de promoties.  
- **Klantenservice** die vragen en klachten via de app afhandelt.  
- **Productie & kwaliteit** die productinformatie, voorraadstatus en kwaliteitsdata levert.  
- De **klanten zelf**, die de app gebruiken en feedback geven.

### Organogram
```mermaid
graph TD
    RC[Raad van Commissarissen]
    AD[Algemeen Directeur]
    PM[Projectmanager App-ontwikkeling]
    OT[Ontwikkelteam]
    DEV[Programmeurs / Developers]
    UX[UX/UI Designers]
    QA[Testers / QA]
    PO[Product Owner / Business Analyst]
    MC[Marketing & Communicatie]
    CT[Content Team / Social Media]
    CS[Klantenservice]
    SM[Supportmedewerkers]
    PK[Productie & Kwaliteit]
    CP[Chocoladeproductie]
    QC[Kwaliteitscontrole]

    RC --> AD
    AD --> PM
    AD --> MC
    AD --> CS
    AD --> PK
    PM --> OT
    PM --> PO
    OT --> DEV
    OT --> UX
    OT --> QA
    MC --> CT
    CS --> SM
    PK --> CP
    PK --> QC
```

## Stakeholderanalyse BimBonBon app

In deze analyse bekijken we de belangrijkste betrokkenen (stakeholders) rondom de BimBonBon app.  
We beschrijven hun belangen, invloed op het project, en wat zij verwachten van het resultaat.  
Dit helpt ons om te zorgen dat we aan de wensen van alle partijen voldoen en effectief kunnen samenwerken.

### Belang, Invloed en Verwachting
- **Belang**: Wat de stakeholder belangrijk vindt in het project.  
- **Invloed**: Hoeveel invloed de stakeholder heeft op beslissingen en uitvoering.  
- **Verwachting**: Wat de stakeholder verwacht of nodig heeft van het project.  

De stakeholders zijn ingedeeld op basis van hun invloed en belang: hoog, middel en laag. Zo kunnen we prioriteiten stellen in communicatie en samenwerking.

![Start](stakeholdermatrix_bimbonbon.png)


### Stakeholders indeling

#### Actief beheren (veel invloed en veel belang)
- **Raad van Commissarissen**  
  - Belang: Succesvolle lancering van de app, betere klantloyaliteit, datagedreven inzichten.  
  - Invloed: Hoog, beslist over goedkeuring en strategische keuzes.  
  - Verwachting: App voldoet aan bedrijfsstrategie en kwaliteitsstandaarden.  
- **Algemeen Directeur / Managementteam**  
  - Belang: Project succesvol uitvoeren, integratie met ERP/CRM.  
  - Invloed: Hoog, stuurt middelen, prioriteiten en team aan.  
  - Verwachting: Efficiënte voortgang, juiste functies en tijdige oplevering.  
- **Projectmanager App-ontwikkeling**  
  - Belang: Het project volgens planning en budget opleveren.  
  - Invloed: Hoog, direct verantwoordelijk voor team en voortgang.  
  - Verwachting: Duidelijke requirements, gemotiveerd team, minimale problemen.  
- **Product Owner / Business Analyst**  
  - Belang: Functionele en zakelijke eisen correct geïmplementeerd.  
  - Invloed: Hoog, bepaalt backlog en prioriteiten.  
  - Verwachting: App voldoet aan businessdoelen en gebruikersbehoeften.  

#### Tevreden houden (weinig invloed maar wel belang)
- **Klanten / Eindgebruikers**  
  - Belang: Gemakkelijk registreren van producten, overzichtelijk dashboard, gepersonaliseerde ervaring.  
  - Invloed: Laag, kunnen niet direct beslissen over features.  
  - Verwachting: Intuïtieve, betrouwbare en veilige app.  
- **Klantenservice**  
  - Belang: Minder meldingen van problemen, makkelijker klachten afhandelen via app.  
  - Invloed: Laag, hebben input over procesverbeteringen maar niet over prioriteiten.  
  - Verwachting: App ondersteunt self-service en reduceert werkdruk.  

#### Monitoren (veel invloed maar weinig belang)
- Momenteel geen stakeholders in deze categorie.

#### Informeren (weinig invloed en weinig belang)
- Momenteel geen stakeholders in deze categorie.
---

[👉 Volgende: Actoren](02-actoren.md)

