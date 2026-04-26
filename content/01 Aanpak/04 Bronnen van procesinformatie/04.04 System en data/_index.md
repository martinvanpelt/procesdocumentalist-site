title: Systemen en Data  
weight: 4  
hidden: true  
---

### **Inleiding**

Systemen en data vormen een **krachtige bron** voor het **objectief analyseren** van processen. In tegenstelling tot **subjectieve informatie** uit interviews of workshops, bieden systemen **feitengebaseerde inzichten** in:  
✅ **Hoe processen daadwerkelijk verlopen** (niet hoe ze *zouden* moeten verlopen).  
✅ **Volgorde van processtappen** en **doorlooptijden**.  
✅ **Betrokken rollen, systemen, en afhankelijkheden**.  
✅ **Procesvarianten, uitzonderingen, en knelpunten**.  
✅ **KPI's en prestatiemeting** (bijv. doorlooptijd, foutpercentage).

Voor jou als **procesdocumentalist** is deze analyse **essentieel** om:

- **Procesmodellen te verfijnen** (BPMN, Swimlane).
- **Knelpunten en inefficiënties** te identificeren.
- **Datagestuurde verbeteringen** voor te stellen.
- **Compliance en audits** te ondersteunen.

**Belangrijke opmerking:**  
Systemen en data **alleen** zijn **niet voldoende** voor een complete procesanalyse. Combineer deze altijd met **interviews, workshops, en documentatie** voor een **holistisch beeld**.

---

---

## **1. Soorten Systemen**

Systemen kunnen **verschillende typen data** bevatten die relevant zijn voor procesanalyse. Hieronder een overzicht:


| **Type Systeem**               | **Beschrijving**                                                                 | **Relevante Data voor Procesanalyse**                    | **Voorbeelden**                  | **Toepassing in Telecom**                   |
| ------------------------------ | -------------------------------------------------------------------------------- | -------------------------------------------------------- | -------------------------------- | ------------------------------------------- |
| **ERP-systemen**               | Enterprise Resource Planning-systemen voor **integratie van bedrijfsprocessen**. | Orderverwerking, voorraadbeheer, financiële transacties. | SAP, Oracle, Microsoft Dynamics  | Order-to-Cash, Facturatie                   |
| **CRM-systemen**               | Customer Relationship Management-systemen voor **klantinteracties**.             | Klantgegevens, orderhistorie, klantenserviceverzoeken.   | Salesforce, HubSpot, Zoho CRM    | Klantcontact, Orderverwerking               |
| **Workflowtools**              | Tools voor **automatisering en beheer van werkprocessen**.                       | Processtappen, doorlooptijden, verantwoordelijkheden.    | Camunda, Signavio, Kissflow      | Procesautomatisering, Goedkeuringsworkflows |
| **Registratiesystemen**        | Systemen voor **registratie van gegevens**.                                      | Transacties, logs, audit trails.                         | Database, Excel, Access          | Orderregistratie, Systeemlogs               |
| **Ticketingsystemen**          | Systemen voor **beheer van verzoeken en incidenten**.                            | Status van verzoeken, doorlooptijden, oplossingen.       | Jira, ServiceNow, Zendesk        | Storingafhandeling, Klantenservice          |
| **Monitoringtools**            | Tools voor **real-time monitoring** van systemen en processen.                   | Systeembeschikbaarheid, prestatiemetrics, alerts.        | Nagios, Splunk, Grafana          | Netwerkmonitoring, Systeemprestaties        |
| **BI-tools**                   | Business Intelligence-tools voor **analyse en rapportage**.                      | KPI's, trends, dashboards.                               | Power BI, Tableau, Qlik Sense    | Procesdashboard, KPI-rapportage             |
| **Documentmanagementsystemen** | Systemen voor **opslag en beheer van documenten**.                               | Procesdocumentatie, handleidingen, beleidsdocumenten.    | SharePoint, Confluence, Alfresco | Procesbeschrijvingen, Werkinstructies       |
| **Communicatietools**          | Tools voor **interne communicatie**.                                             | Chatlogs, e-mails, samenwerkingsgeschiedenis.            | Microsoft Teams, Slack, Outlook  | Teamcommunicatie, Besluitvorming            |
| **Provisioning-systemen**      | Systemen voor **automatische inrichting van diensten**.                          | Activatiestatus, configuraties, logs.                    | Custom telecom tools, Ansible    | SIM-activatie, Netwerkconfiguratie          |


---

---

## **2. Wat Systemen en Data Kunnen Laten Zien**

Systemen en data bieden **waardevolle inzichten** voor procesanalyse:


| **Inzicht**                    | **Beschrijving**                                   | **Voorbeeld**                                                              | **Toepassing**                          |
| ------------------------------ | -------------------------------------------------- | -------------------------------------------------------------------------- | --------------------------------------- |
| **Volgorde van processtappen** | Hoe processen **daadwerkelijk** verlopen.          | "Stap 1: Ontvangst order → Stap 2: Validatie → Stap 3: Productieopdracht." | BPMN-diagram, Procesbeschrijving        |
| **Doorlooptijden**             | Tijd tussen **processtappen**.                     | "Gemiddelde doorlooptijd orderverwerking: 22 uur."                         | KPI-definitie, Processturing            |
| **Betrokken rollen**           | Wie is **betrokken** bij het proces.               | "Order Medewerker, Proceseigenaar, IT-afdeling."                           | RACI-matrix, Procesrollen               |
| **Procesvarianten**            | Verschillende **paden** die een proces kan volgen. | "Spoedorders vs. standaardorders."                                         | BPMN-diagram (Gateways)                 |
| **Uitzonderingen**             | Afwijkingen van de **standaardstroom**.            | "Onvolledige klantgegevens → Terug naar klant."                            | Procesbeschrijving, BPMN (Error Events) |
| **Knelpunten**                 | **Vertragingen of blokkades** in het proces.       | "Validatiestap duurt gemiddeld 30 minuten."                                | Root Cause Analyse, Procesverbeterplan  |
| **Systeemintegraties**         | Hoe systemen **met elkaar verbonden** zijn.        | "CRM-systeem koppelt met ERP-systeem."                                     | Swimlane-diagram, Systeemdocumentatie   |
| **Dataflows**                  | Hoe **data** door het proces stroomt.              | "Klantgegevens → CRM → ERP → Productie."                                   | Data Flow Diagram (DFD)                 |
| **Fouten en herwerk**          | **Foutpercentages** en herwerkstappen.             | "5% van de orders bevat fouten."                                           | KPI-definitie, Kwaliteitsborging        |
| **Compliance**                 | Naleving van **wettelijke en organisatie-eisen**.  | "GDPR: Persoonsgegevens worden versleuteld opgeslagen."                    | Compliance-rapport, Audit               |
| **KPI's**                      | **Prestatie-indicatoren** van het proces.          | "Doorlooptijd: < 24 uur, Foutpercentage: < 1%."                            | KPI-definitie, Procesdashboard          |


---

---

## **3. Voordelen van Systeem- en Data-analyse**


| **Voordeel**                     | **Toelichting**                                                           | **Impact**                               |
| -------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------- |
| **Objectieve data**              | Systemen bevatten **feitengebaseerde informatie**.                        | Betrouwbaarder dan subjectieve meningen. |
| **Real-time inzicht**            | Data kan **real-time** worden geanalyseerd.                               | Snelle identificatie van knelpunten.     |
| **Historische trends**           | Analyse van **historische data** voor trendherkenning.                    | Voorspellen van toekomstige prestaties.  |
| **Procesvarianten**              | Identificatie van **alle mogelijke paden** in een proces.                 | Completere procesmodellen.               |
| **KPI-meting**                   | Meten van **prestaties** tegen doelstellingen.                            | Datagestuurde verbeteringen.             |
| **Compliance-controle**          | Verifiëren of processen **voldoen aan eisen**.                            | Verminderen van risico's.                |
| **Automatiseringsmogelijkheden** | Identificatie van **herhalende taken** die geautomatiseerd kunnen worden. | Efficiëntieverbetering.                  |


---

---

## **4. Aandachtspunten bij Systeem- en Data-analyse**


| **Aandachtspunt**                   | **Toelichting**                                                 | **Risico**                    | **Oplossing**                                    |
| ----------------------------------- | --------------------------------------------------------------- | ----------------------------- | ------------------------------------------------ |
| **Data is niet altijd betrouwbaar** | Systemen kunnen **fouten of onvolledige data** bevatten.        | Onnauwkeurige procesmodellen. | **Valideer data met stakeholders**.              |
| **Beperkte toegang**                | Niet alle systemen zijn **toegankelijk** voor de procesanalist. | Ontbrekende informatie.       | **Vraag toegang aan bij IT of systeemeigenaar**. |
| **Complexe systemen**               | Sommige systemen zijn **te complex** voor directe analyse.      | Tijdsintensief.               | **Focus op relevante data**.                     |
| **Geen context**                    | Data geeft **geen inzicht in de redenen** achter processtappen. | Gebrek aan begrip.            | **Combineer met interviews/workshops**.          |
| **Datakwaliteit**                   | Data kan **onvolledig, verouderd, of inconsistent** zijn.       | Onbetrouwbare analyses.       | **Voer datakwaliteitscontroles uit**.            |
| **Privacy en compliance**           | Sommige data is **gevoelig** (bijv. persoonsgegevens).          | Wettelijke risico's.          | **Houd rekening met GDPR en andere wetgeving**.  |
| **Te veel data**                    | Systemen bevatten **enorme hoeveelheden data**.                 | Overweldigend.                | **Focus op relevante KPI's en processtappen**.   |


---

---

## **5. Stappen voor het Analyseren van Systemen en Data**

Volg deze **stappen** om systemen en data **effectief** te analyseren voor procesdocumentatie.

---

### **5.1 Inventarisatie van Systemen**

Maak een **overzicht** van alle **relevante systemen** voor het proces dat je analyseert.


| **Systeem**      | **Type**   | **Eigenaar** | **Toegang** | **Relevantie** | **Data die beschikbaar is**             | **Status** |
| ---------------- | ---------- | ------------ | ----------- | -------------- | --------------------------------------- | ---------- |
| ERP-systeem      | SAP        | IT-afdeling  | Ja          | Hoog           | Ordergegevens, voorraad, doorlooptijden | Actueel    |
| CRM-systeem      | Salesforce | Sales        | Ja          | Hoog           | Klantgegevens, orderhistorie            | Actueel    |
| Ticketingsysteem | Jira       | IT-afdeling  | Nee         | Middel         | Storingmeldingen, doorlooptijden        | Actueel    |
| Monitoringtool   | Nagios     | IT-afdeling  | Ja          | Hoog           | Systeembeschikbaarheid, alerts          | Actueel    |


**Status:**

- **Actueel**: Systeem is recent bijgewerkt.
- **Verouderd**: Systeem is niet recent bijgewerkt.
- **Onbekend**: Status is onduidelijk.

---

### **5.2 Selectie van Relevante Systemen**

Selecteer de **meest relevante systemen** voor je procesanalyse. Gebruik de volgende **criteria**:


| **Criterium**                      | **Beschrijving**                                               | **Voorbeeld**                                      |
| ---------------------------------- | -------------------------------------------------------------- | -------------------------------------------------- |
| **Relevantie voor het proces**     | Hoe relevant is het systeem voor het proces dat je analyseert? | ERP-systeem is zeer relevant voor Orderverwerking. |
| **Beschikbare data**               | Bevat het systeem **data die relevant is** voor je analyse?    | CRM-systeem bevat klantgegevens en orderhistorie.  |
| **Toegankelijkheid**               | Heb je **toegang** tot het systeem?                            | Toegang tot ERP-systeem is goedgekeurd.            |
| **Datakwaliteit**                  | Is de data in het systeem **betrouwbaar en actueel**?          | ERP-data wordt dagelijks bijgewerkt.               |
| **Integratie met andere systemen** | Hoe is het systeem **geïntegreerd** met andere systemen?       | CRM-systeem koppelt met ERP-systeem.               |


---

### **5.3 Data Extractie**

Extraheer **relevante data** uit de geselecteerde systemen. Gebruik de volgende **methoden**:


| **Methode**                | **Beschrijving**                                                | **Wanneer te gebruiken**                   | **Voorbeeld**                                                |
| -------------------------- | --------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------------------ |
| **Handmatige extractie**   | Data handmatig **exporteren** uit systemen.                     | Kleine datasets, eenmalige analyse.        | Exporteren van ordergegevens uit ERP.                        |
| **Automatische extractie** | Data **automatisch** extraheren via API's of scripts.           | Grote datasets, regelmatige analyse.       | Automatisch extraheren van KPI's uit BI-tool.                |
| **Rapportages**            | Gebruik **bestaande rapportages** uit systemen.                 | Als rapportages beschikbaar zijn.          | Gebruik maandelijkse KPI-rapportage uit ERP.                 |
| **Logs en audit trails**   | Analyseer **systeemlogs** voor procesinformatie.                | Voor diepgaande analyse van processtappen. | Analyseer logs van Ticketingsysteem voor storingafhandeling. |
| **Datawarehouse**          | Gebruik een **centraal datawarehouse** voor geïntegreerde data. | Als data uit meerdere systemen nodig is.   | Gebruik datawarehouse voor Order-to-Cash-analyse.            |


**Tip voor Martin:**  
Gebruik je **technische kennis** (of die van IT) om **data te extraheren** uit systemen zoals **ERP, CRM, of monitoringtools**.

---

### **5.4 Data Analyse**

Analyseer de **geëxtraheerde data** om **inzichten** te verkrijgen. Gebruik de volgende **analysemethoden**:

---

#### **5.4.1 Processtroomanalyse**

Analyseer de **volgorde van processtappen** en **doorlooptijden**.


| **Analyse**             | **Beschrijving**                                           | **Voorbeeld**                                    | **Tool**         |
| ----------------------- | ---------------------------------------------------------- | ------------------------------------------------ | ---------------- |
| **Procesmining**        | Automatisch **ontdekken van processtappen** uit data.      | Ontdek de werkelijke stroom van orderverwerking. | Celonis, Disco   |
| **Doorlooptijdanalyse** | Analyseer **tijden tussen processtappen**.                 | Gemiddelde doorlooptijd per stap.                | Excel, Power BI  |
| **Frequentieanalyse**   | Analyseer **hoe vaak** bepaalde stappen worden uitgevoerd. | Aantal keren dat validatiestap wordt herhaald.   | Excel, Tableau   |
| **Variantanalyse**      | Identificeer **verschillende paden** in het proces.        | Spoedorders vs. standaardorders.                 | Celonis, Minitab |


---

#### **5.4.2 Knelpuntenanalyse**

Identificeer **knelpunten** in het proces.


| **Analyse**                 | **Beschrijving**                                   | **Voorbeeld**                                        | **Tool**                   |
| --------------------------- | -------------------------------------------------- | ---------------------------------------------------- | -------------------------- |
| **Bottleneck-analyse**      | Identificeer **stappen met lange doorlooptijden**. | Validatiestap duurt gemiddeld 30 minuten.            | Excel, Power BI            |
| **Foutenanalyse**           | Analyseer **foutpercentages** en herwerk.          | 5% van de orders bevat fouten.                       | Excel, Qlik Sense          |
| **Capaciteitsanalyse**      | Analyseer **capaciteitsbeperkingen**.              | Order Team kan maximaal 50 orders per dag verwerken. | Excel, Simulation Software |
| **Afhankelijkheidsanalyse** | Identificeer **afhankelijkheden tussen stappen**.  | Stap B kan niet starten voordat stap A is afgerond.  | BPMN, Swimlane-diagram     |


---

#### **5.4.3 Compliance-analyse**

Controleer of het proces **voldoet aan wettelijke en organisatie-eisen**.


| **Analyse**             | **Beschrijving**                                            | **Voorbeeld**                                | **Tool**                      |
| ----------------------- | ----------------------------------------------------------- | -------------------------------------------- | ----------------------------- |
| **Audit trail analyse** | Controleer of **alle stappen** zijn geregistreerd.          | Alle orderstappen zijn gelogd in ERP.        | ERP-systeem, Audit Software   |
| **GDPR-naleving**       | Controleer of **persoonsgegevens** correct worden verwerkt. | Klantgegevens worden versleuteld opgeslagen. | GDPR Compliance Tools         |
| **ISO 9001-naleving**   | Controleer of het proces **voldoet aan kwaliteitsnormen**.  | Proces is gecertificeerd volgens ISO 9001.   | Kwaliteitsmanagement Software |


---

---

## **6. Integratie met Andere Templates**

Gebruik de **inzichten uit systeem- en data-analyse** om andere templates uit je **7x Framework** in te vullen.


| **Template**                          | **Toepassing**                                | **Voorbeeld**                                       |
| ------------------------------------- | --------------------------------------------- | --------------------------------------------------- |
| **Procesbeschrijving** (PMD-03.07.01) | Basis voor gedetailleerde procesbeschrijving. | Gebruik processtappen uit ERP-data.                 |
| **BPMN-diagram** (PMD-03.06.01)       | Visuele weergave van het proces.              | Gebruik processtroom en beslissingen uit data.      |
| **Swimlane-diagram** (PMD-03.06.03)   | Weergave van verantwoordelijkheden.           | Gebruik rollen uit systeemlogs.                     |
| **Processturing** (PMD-03.08.00)      | Monitoring en sturing van het proces.         | Gebruik KPI's uit BI-tools.                         |
| **KPI-definitie** (PMD-03.08.04)      | Definitie van KPI's.                          | Gebruik doorlooptijden en foutpercentages uit data. |
| **Procesverbeterplan** (PMD-03.09.02) | Actiepunten voor procesverbetering.           | Gebruik knelpunten uit data-analyse.                |
| **Root Cause Analyse** (PMD-03.09.01) | Analyse van knelpunten.                       | Gebruik data over vertragingen en fouten.           |
| **RACI-matrix** (PMD-03.07.03)        | Verantwoordelijkheden per taak.               | Gebruik rollen uit systeemdata.                     |


---

---

## **7. Tips voor Effectieve Systeem- en Data-analyse**

🔹 **Begin met een duidelijk doel**: Bepaal **wat je wilt bereiken** met de analyse (bijv. procesmodellering, knelpunten identificeren).  
🔹 **Selecteer relevante systemen**: Focus op systemen die **de meeste relevante data** bevatten.  
🔹 **Gebruik automatisering**: Maak gebruik van **API's, scripts, of procesmining-tools** voor efficiënte data-extractie.  
🔹 **Valideer data**: Controleer of de data **betrouwbaar en actueel** is.  
🔹 **Combineer met andere bronnen**: Gebruik **interviews, workshops, en documentatie** voor een compleet beeld.  
🔹 **Focus op KPI's**: Analyseer data die **relevant is voor KPI's** (bijv. doorlooptijd, foutpercentage).  
🔹 **Gebruik visuele tools**: Maak gebruik van **Power BI, Tableau, of Celonis** voor inzichtelijke analyses.  
🔹 **Houd rekening met privacy**: Zorg dat je **GDPR en andere wettelijke eisen** naleeft.  
🔹 **Documenteer je bevindingen**: Leg **inzichten, knelpunten, en verbeterkansen** vast in procesdocumentatie.

---

---

## **8. Veelgemaakte Fouten en Hoe ze te Vermijden**


| **Fout**                               | **Oorzaak**                                    | **Impact**                    | **Oplossing**                             |
| -------------------------------------- | ---------------------------------------------- | ----------------------------- | ----------------------------------------- |
| **Te veel systemen analyseren**        | Tijdsgebrek door te veel systemen.             | Vertraging in procesanalyse.  | **Focus op de meest relevante systemen**. |
| **Data niet valideren**                | Aanname dat data altijd betrouwbaar is.        | Onnauwkeurige procesmodellen. | **Valideer data met stakeholders**.       |
| **Geen duidelijke vraagstelling**      | Onduidelijk wat je wilt bereiken.              | Ongefocuste analyse.          | **Definieer een duidelijk doel**.         |
| **Privacy schenden**                   | Gebruik van gevoelige data zonder toestemming. | Wettelijke risico's.          | **Houd rekening met GDPR**.               |
| **Te diepgaande analyse**              | Te veel detail voor het beoogde doel.          | Tijdsverspilling.             | **Focus op relevante data**.              |
| **Geen integratie met andere bronnen** | Alleen vertrouwen op systeemdata.              | Onvolledig beeld.             | **Combineer met interviews/workshops**.   |
| **Verouderde data gebruiken**          | Gebruik van data die niet actueel is.          | Onnauwkeurige analyses.       | **Controleer de datum van de data**.      |


---

---

## **9. Tools voor Systeem- en Data-analyse**

Gebruik deze **tools** om systemen en data **efficiënter** te analyseren:


| **Tool**       | **Type**     | **Doel**                                          | **Voordelen**                            | **Nadelen**                | **Link**                                                         |
| -------------- | ------------ | ------------------------------------------------- | ---------------------------------------- | -------------------------- | ---------------------------------------------------------------- |
| **Celonis**    | Procesmining | Automatisch ontdekken van processtappen uit data. | Krachtige analyse, real-time inzichten.  | Duur, complex.             | [Celonis](https://www.celonis.com)                               |
| **Disco**      | Procesmining | Procesontdekking en -analyse.                     | Gebruiksvriendelijk, visuele weergave.   | Betaalde versie.           | [Disco](https://fluxicon.com/disco)                              |
| **Power BI**   | BI-tool      | Data-analyse en rapportage.                       | Flexibel, integratie met andere tools.   | Leercurve.                 | [Power BI](https://powerbi.microsoft.com)                        |
| **Tableau**    | BI-tool      | Data-visualisatie en analyse.                     | Krachtige visualisaties, real-time data. | Duur.                      | [Tableau](https://www.tableau.com)                               |
| **Qlik Sense** | BI-tool      | Data-analyse en dashboarding.                     | Associatieve data-analyse.               | Complex.                   | [Qlik Sense](https://www.qlik.com)                               |
| **Splunk**     | Monitoring   | Real-time monitoring en log-analyse.              | Krachtige zoekfunctie, alerts.           | Duur, technisch.           | [Splunk](https://www.splunk.com)                                 |
| **Nagios**     | Monitoring   | Systeembeschikbaarheid en prestatiemeting.        | Open-source, real-time alerts.           | Technisch.                 | [Nagios](https://www.nagios.org)                                 |
| **Excel**      | Spreadsheet  | Data-analyse en rapportage.                       | Flexibel, eenvoudig.                     | Handmatige invoer.         | -                                                                |
| **SQL**        | Database     | Data-extractie en -analyse.                       | Krachtig, flexibel.                      | Technische kennis vereist. | -                                                                |
| **Python/R**   | Scripting    | Geavanceerde data-analyse.                        | Flexibel, automatiseerbaar.              | Technische kennis vereist. | [Python](https://www.python.org), [R](https://www.r-project.org) |


---

---

## **10. Stakeholders en Verantwoordelijkheden**

Geef hier een overzicht van **wie betrokken is** bij de systeem- en data-analyse.


| **Rol**                | **Verantwoordelijkheid**                                          | **Betrokkenheid** |
| ---------------------- | ----------------------------------------------------------------- | ----------------- |
| **Procesanalist**      | Voert de systeem- en data-analyse uit.                            | Ad hoc            |
| **IT-afdeling**        | Leveren toegang tot systemen en ondersteuning bij data-extractie. | Ad hoc            |
| **Proceseigenaar**     | Valideert de uitkomsten van de analyse.                           | Periodiek         |
| **Data Analist**       | Ondersteunt bij complexe data-analyses.                           | Ad hoc            |
| **Compliance Officer** | Zorgt voor naleving van wettelijke eisen (bijv. GDPR).            | Periodiek         |


---

---

## **11. Gerelateerde Documenten**

Lijst hier alle **gerelateerde documenten**, zoals:

- [Link naar Procesbeschrijving (PMD-03.07.01)]
- [Link naar BPMN-diagram (PMD-03.06.01)]
- [Link naar Processturing (PMD-03.08.00)]
- [Link naar KPI-definitie (PMD-03.08.04)]
- [Link naar Interviews (PMD-03.09.01)]
- [Link naar Workshops (PMD-03.09.02)]

---

---

## **12. Versiehistorie**


| **Versie** | **Datum**  | **Wijziging**   | **Auteur** |
| ---------- | ---------- | --------------- | ---------- |
| 1.0        | 17/04/2026 | Initiële versie | [Naam]     |


---

---

## **13. Instructies voor Gebruik**

1. **Inventariseer systemen**:
  - Maak een **overzicht** van alle relevante systemen voor het proces.
2. **Selecteer relevante systemen**:
  - Kies systemen op basis van **relevantie, beschikbare data, en toegankelijkheid**.
3. **Extraheer data**:
  - Gebruik **handmatige of automatische methoden** om data te extraheren.
4. **Analyseer data**:
  - Voer **processtroomanalyse, knelpuntenanalyse, en compliance-analyse** uit.
5. **Integreer met andere templates**:
  - Gebruik de inzichten om **Procesbeschrijving, BPMN-diagrammen, etc.** op te stellen.
6. **Valideer resultaten**:
  - Controleer de **nauwkeurigheid** van de analyse met stakeholders.
7. **Documenteer bevindingen**:
  - Leg **inzichten, knelpunten, en verbeterkansen** vast in procesdocumentatie.

---

---

## **14. Voorbeeld: Systeem- en Data-analyse voor Orderverwerking**

### **Inventarisatie van Systemen**


| **Systeem**      | **Type**   | **Eigenaar** | **Toegang** | **Relevantie** | **Data die beschikbaar is**              | **Status** |
| ---------------- | ---------- | ------------ | ----------- | -------------- | ---------------------------------------- | ---------- |
| ERP-systeem      | SAP        | IT-afdeling  | Ja          | Hoog           | Ordergegevens, voorraad, doorlooptijden  | Actueel    |
| CRM-systeem      | Salesforce | Sales        | Ja          | Hoog           | Klantgegevens, orderhistorie             | Actueel    |
| Ticketingsysteem | Jira       | IT-afdeling  | Nee         | Middel         | Storingmeldingen (indien van toepassing) | Actueel    |


---

### **Selectie van Relevante Systemen**

- **ERP-systeem**: Zeer relevant voor **ordergegevens, voorraad, en doorlooptijden**.
- **CRM-systeem**: Zeer relevant voor **klantgegevens en orderhistorie**.

---

### **Data Extractie**


| **Methode**            | **Systeem** | **Data**                                                   | **Frequentie** |
| ---------------------- | ----------- | ---------------------------------------------------------- | -------------- |
| Handmatige extractie   | ERP-systeem | Ordergegevens (ID, datum, status, doorlooptijd)            | Eenmalig       |
| Automatische extractie | CRM-systeem | Klantgegevens (ID, naam, contactgegevens)                  | Eenmalig       |
| Rapportages            | ERP-systeem | Maandelijkse KPI-rapportage (doorlooptijd, foutpercentage) | Maandelijks    |


---

### **Data Analyse**

#### **Processtroomanalyse**

- **Procesmining**: Ontdek de **werkelijke stroom** van orderverwerking met Celonis.
  - **Resultaat**: 90% van de orders volgt de standaardstroom, 10% heeft herwerk nodig.
- **Doorlooptijdanalyse**: Gemiddelde doorlooptijd per stap.
  - **Resultaat**:
    - Ontvangst order: 5 minuten.
    - Validatie klantgegevens: 30 minuten (**knelpunt**).
    - Genereren productieopdracht: 15 minuten.
    - Versturen orderbevestiging: 2 minuten.

#### **Knelpuntenanalyse**

- **Bottleneck-analyse**: Validatiestap duurt **gemiddeld 30 minuten** (langer dan andere stappen).
- **Foutenanalyse**: **5% van de orders** bevat fouten (vooral bij onvolledige klantgegevens).
- **Capaciteitsanalyse**: Order Team kan **maximaal 50 orders per dag** verwerken.

---

### **Integratie met Andere Templates**

#### **Procesbeschrijving (PMD-03.07.01)**

- **Processtappen**: Gebruik de **werkelijke stroom** uit procesmining.
- **Knelpunten**: Voeg **validatiestap en foutpercentage** toe.

#### **BPMN-diagram (PMD-03.06.01)**

- **Hoofdstroom**: Teken de **standaardstroom** (90% van de orders).
- **Uitzonderingen**: Voeg **herwerkstappen** toe voor de 10% uitzonderingen.
- **Beslissingen**: Voeg **gateways** toe voor validatie en voorraadcontrole.

#### **Processturing (PMD-03.08.00)**

- **KPI's**:
  - Doorlooptijd orderverwerking: **Doel < 24 uur, Huidig 22 uur**.
  - Aantal fouten per order: **Doel < 1%, Huidig 5%**.
- **Alerts**: Stel alerts in voor **doorlooptijd > 24 uur** en **foutpercentage > 1%**.

---

### **Validatie van Resultaten**

- **Interview met Order Team**: Bevestigd dat **validatiestap tijdrovend** is.
- **Workshop met Proceseigenaar**: Bevestigd dat **5% foutpercentage** te hoog is.

---

---

## **15. Voorbeeld: Systeem- en Data-analyse voor SIM-activatie (Telecom)**

Gebaseerd op je **ervaring in de telecomsector**, hier een **praktisch voorbeeld** voor een **SIM-activatieproces**.

### **Inventarisatie van Systemen**


| **Systeem**          | **Type**   | **Eigenaar** | **Toegang** | **Relevantie** | **Data die beschikbaar is**           | **Status** |
| -------------------- | ---------- | ------------ | ----------- | -------------- | ------------------------------------- | ---------- |
| Provisioning-systeem | Custom     | IT-afdeling  | Ja          | Hoog           | Activatiestatus, logs, doorlooptijden | Actueel    |
| CRM-systeem          | Salesforce | Sales        | Ja          | Hoog           | Klantgegevens, activatieaanvragen     | Actueel    |
| Monitoringtool       | Nagios     | IT-afdeling  | Ja          | Hoog           | Systeembeschikbaarheid, alerts        | Actueel    |


---

### **Selectie van Relevante Systemen**

- **Provisioning-systeem**: Zeer relevant voor **activatiestatus en doorlooptijden**.
- **CRM-systeem**: Zeer relevant voor **klantgegevens en activatieaanvragen**.

---

### **Data Extractie**


| **Methode**            | **Systeem**          | **Data**                                                   | **Frequentie** |
| ---------------------- | -------------------- | ---------------------------------------------------------- | -------------- |
| Handmatige extractie   | Provisioning-systeem | Activatiegegevens (ID, datum, status, doorlooptijd)        | Eenmalig       |
| Automatische extractie | CRM-systeem          | Klantgegevens (ID, naam, contactgegevens, activatiestatus) | Eenmalig       |
| Rapportages            | Monitoringtool       | Maandelijkse rapportage (systeembeschikbaarheid, alerts)   | Maandelijks    |


---

### **Data Analyse**

#### **Processtroomanalyse**

- **Procesmining**: Ontdek de **werkelijke stroom** van SIM-activatie met Celonis.
  - **Resultaat**: 85% van de activaties volgt de standaardstroom, 15% heeft herwerk nodig.
- **Doorlooptijdanalyse**: Gemiddelde activatietijd per stap.
  - **Resultaat**:
    - Ontvangst activatieaanvraag: 2 minuten.
    - Validatie klantgegevens: 10 minuten.
    - Activatie SIM-kaart: 25 minuten (**knelpunt**).
    - Testen SIM-kaart: 5 minuten.
    - Versturen bevestiging: 3 minuten.

#### **Knelpuntenanalyse**

- **Bottleneck-analyse**: Activatiestap duurt **gemiddeld 25 minuten** (langer dan andere stappen).
- **Foutenanalyse**: **7% van de activaties** mislukt (vooral bij onjuiste klantgegevens).
- **Capaciteitsanalyse**: Technisch Team kan **maximaal 100 activaties per dag** verwerken.

---

### **Integratie met Andere Templates**

#### **Procesbeschrijving (PMD-03.07.01)**

- **Processtappen**: Gebruik de **werkelijke stroom** uit procesmining.
- **Knelpunten**: Voeg **activatiestap en foutpercentage** toe.

#### **Swimlane-diagram (PMD-03.06.03)**

- **Swimlanes**:
  - **Klant**: Ontvangt bevestiging.
  - **Klantenservice**: Ontvangt activatieaanvraag.
  - **Technisch Team**: Voert activatie uit.
  - **Provisioning-systeem**: Registreert activatie.

#### **Processturing (PMD-03.08.00)**

- **KPI's**:
  - Activatietijd: **Doel < 1 uur, Huidig 45 minuten**.
  - Aantal mislukte activaties: **Doel < 5%, Huidig 7%**.
- **Alerts**: Stel alerts in voor **activatietijd > 1 uur** en **foutpercentage > 5%**.

---

### **Validatie van Resultaten**

- **Interview met Technisch Team**: Bevestigd dat **activatiestap tijdrovend** is.
- **Workshop met Proceseigenaar**: Bevestigd dat **7% foutpercentage** te hoog is.