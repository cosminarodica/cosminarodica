[Homepage](index.md)

# Diagrame de lowchart

mermaid
flowchart LR
A[Anul I] --> B[Anul II]


mermaid
flowchart LR
A(Anul I) --> B(Anul II)


mermaid
flowchart LR
A[/Anul I/] -->|tranzitie usuoara| B[\Anul II\]
A -.-> |tranzitie grea|C[\Anul IV/]
C-->|tranzitie medie|[Mate]


**de retinut:**
- Diagramele_flowcharte_au noduri si conectori
- nodurile au:
 - **forma** (data de parantezele folosite la descriera _nodului_)
 - ID (sirul folosit in afara ndescrierii nodului)
 - Descriere(textul ce apare in caseta nodului si care este implementat in interiorul diferitelor tipuri de paranteze -  ce decid forma casetei nodului)
- Conectorii au:
 - Diferite tipuri de sageti sau chiar pot activa fara sageti
 - dif tipuri de linii:
  - `-->` linie continua (sageata dreapta)
  - `--` linie continua fara sageti
  - `<-->` linie continua cu sageti
  - `==> linie ingrosata

    ## Diagrame _flowchart_ avansate

    ```
    A & B --> C & D & E--> F & G
    ```
    ## Diagrame _timeline_
 






    
