# Datensatz Testat sh308 #
Codebuch Stand 2021-22-02  
erstellt von Selin Hellfritsch (sh308@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Beim VfB tobt ein Machtkampf um das Präsidentenamt. Die Aufgabe ist es, eine Netzwerkanalyse der Mitglieder des Vorstands und des Aufsichtsrats durchzuführen. Dazu interessiert uns besonders, wer mit wem vernetzt ist.
Ich habe den Datensatz von verschiedenne Websites erhoben.
Informationen von VfB-Organe unter: https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/


# EDGE-Attribute

**id**  
Identische ID mit node Liste. Gibt eine eindeutige ID in Kurzform des Namens der Person oder Organisation an. Dabei verwende ich immer die Anfangsbuchstaben der jeweiligen Vor- und Nachnamen sowie der Organisationen.

**from**  
Gibt an von welchem Akteur die Verbingund geht.

**to**  
Gibt an zu welchem Akteur die Verbindung geht.


# NODE-Attribute  
  
**id**  
Identische ID mit edge Liste. Gibt eine eindeutige ID in Kurzform des Namens der Person oder Organisation an. Dabei verwende ich immer die Anfangsbuchstaben der jeweiligen Vor- und Nachnamen sowie der Organisationen.

**name**    
Gibt den vollen Namen der Personen und Organisationen an.

**type**    
Gibt an, ob es sich um eine Person oder Organisation handelt.
0 = person
1 = organisation
  
**age***    
Gibt das Alter der Akteure in natürliche Zahlen ohne Skalierung an.

**funktion**   
Gibt die Funktion der Akteure an.
V = Vorstand
A = Aufsichtsrat

**representation**    
Bezieht sich auf die Funktion innerhalb der VfB Gremien: 
U = Unternehmensstrategie
S = Sport
K = Kommunikation
V = Verwaltung
F = Finanzen
  
**position**    
Gibt die Position in der VfB Organisation an:
V = Vorsitzender
S = Stellvertretender Vorsitzender
I = Interimsvorstand
M = Mitglied

**organisation**    
Gibt die verschiedenen Organisationen wie Firmen und Stiftungen an, denen die Akteure zusätzlich zum VfB angehören.

# DATENQUELLEN
Die Daten für das Netzwerk werden erhoben aus:
- Mitglieder des VfB: https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/
- Ergänzung der Personendaten durch Munzinger Archiv: https://www.munzinger.de/search/start.jsp 
- Zusätzliche Recherche einzelner Daten durch Google-Suche

##
