---
title: Analyse I
link: http://robinmalfait.com/1ste-jaar/semester-I/Analyse-I.md
---

# Kwaliteitsvolle ICT projecten opleveren

- Tijd
- Communicatie: Team-verband
- Geld

> Meer mensen betekent niet betere software. Communicatie neemt ook toe waardoor communicatie moeilijker wordt. Neemt polynomiaal toe.

| Tamme Problemen                            | Wicked Problemen        |
| ------------------------------------------ | ----------------------- |
| (Goed gedefinieerd + makkelijke oplossing) | (Moeilijke oplossing)   |
| Budget op                                  | Weten wat de klant wilt |
| Tijd op                                    | &nbsp;                  |
| Werknemer ziek                             | &nbsp;                  |
| Netwerk probleem                           | &nbsp;                  |
| Hardware                                   | &nbsp;                  |
| Eisen v.d. klant wijzigen                  | &nbsp;                  |

# Software ontwikkelingsproces

Een kader dat vastlegt hoe een softwareproject wordt aangepakt.

Een methode om de activiteiten in verband met creatie, oplevering en onderhoud van softwaresystemen te organiseren.

# Watervalmethode

**Opeenvolgend process**

1. **Analyse**: Requirements achterhalen. Taal verstaanbaar voor klant & programmeur
2. **Ontwerp**: Onderdelen van het te bouwen systeem (Classes & Objects)
3. **Implementatie**: Coderen & organiseren, unit testen schrijven
4. **Testen**: Requirements testen (use cases)
5. **Integratie**: Samen werken met andere systemen (API’s)
6. **Onderhoud**: features & optimalisatie.

Simpel process (Voor kleinere software projecten)

—> Problemen:

- Weinig flexibiliteit, houdt geen rekening met veranderende eisen van de klant.
- Verlies van informatie: gespecialiseerde personen verlaten het project na hun respectievelijke fase)
- Testen op het einde: fouten worden pas op het einde ontdekt.


**Oplossing:**

**Iteratieve** en **incrementele** ontwikkelmethode

—> Per iteratie een milestone (= documentatie)


# Rational Unified Proces (RUP)

**Iteratie:**

- Software opdelen in time boxes waarbij elke iteratie het proces Analyse, Ontwerp, Implementatie, Testen, Integratie doorlopen en dus uitbreiden.
- We gaan domeinmodel per iteratie (en dus Use Case) opbouwen.

**Incrementeel:** functionaliteit dat werkt (een werkend geheel)

- Iteratieve, incrementele ontwikkeling
    - think big, develop small: werk in iteraties
- Een iteratie bevat steeds dezelfde activiteiten
- De tijdsbesteding aan iedere activiteit zal gaandeweg tijdens het project veranderen (in het begin meer analyse…)
- Iteraties duren meestal 2 tot 6 weken.

> Agile (Een voorbeeld van een RUP)

**Agile Manifesto:**

| &nbsp;                       | over     | &nbsp;                      |
| ---------------------------: | :------: | --------------------------- |
| Individualsand interactions  | &nbsp;   | processes and tools         |
| working software             | &nbsp;   | comprehensive documentation |
| customer collaboration       | &nbsp;   | contract negotiation        |
| responding to change         | &nbsp;   | following a plan            |

# OOA/D

Object georiënteerde Analyse/Design

Klasse:

- parameters (attributen)
- methodes

Object:

- Audi A4 (Instantie)

> Use cases != object georiënteerde analyse/design (maar wordt gebruikt)

# UML

Unified Modelling Language (Notatie wijze)

**Voordelen:**

- Visualisatie
- Communicatie (klant <—> programmeurs)
- Transformatie

**Sequentiediagram:**

Dynamische levenslijnen

# Use Case vs Verhaal

verhaal:

- geen structuur
- irrelevante informatie
- warrig verteld

Use Case Diagram:

- UML Diagram
- Alle taken die het systeem uitvoert
- Actor (Persoon **OF** Extern Systeem)
    - De ‘starter’ is de Primaire Actor

Wat is een Use Case

- tekstuele beschrijving van een taak
- beschrijft gebruik (doel)
- Begrijpbaar voor alle partijen
- Contract
- **Functionele vereisten**

**Wat het doet** en niet hoe hij het doet

# Voorbeeld van een use case:
(hoe het er uit moet zien)

**Use Case:** Naam van de use case<br>
**Situering:** Korte beschrijving<br>
**Primaire Actor:** de entiteit (belangrijke partij!) die de use case instantieert<br>
**Pre Conditie:**
- Voorwaarden voldaan voor een succes (Voor de use case)
- nodige voorwaarden

**Post Conditie:** Voorwaarden voldaan na een succes<br>
**Normaal verloop:** (Main Succes Scenario)

- Lijst van acties die het systeem moet doen om tot een succes te geraken
- Wie / Wat

**Alternatieve Verlopen:** uitbreidingen/uitzonderingen + referentie naar de stap in het main succes scenario<br>
**Domeinregels:** Beperkingen/voorwaarden die geldig moeten zijn in het systeem (VB.: Wachtwoord moet min 6 tekens zijn)
