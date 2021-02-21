# Datensatz Testat sh308 #
Codebuch Stand 2021-21-02  
erstellt von Selin Hellfritsch (sh308@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.rm (Codierung der Datensätze)

## Ursprung und Datenerhebung
Ich habe den Datensatz von verschiedenne Websites erhoben.


# EDGE-Attribute

**id**  
Identische ID mit node Liste. Gibt eine eindeutige ID in Kurzform des Namens der Person oder Organisation an.

**from**  
Gibt an von welchem Akteur die Verbingund geht.

**to**  
Gibt an zu welchem Akteur die Verbindung geht.


# NODE-Attribute  
  
**id**  
Identische ID mit edge Liste. Gibt eine eindeutige ID in Kurzform des Namens der Person oder Organisation an. Dabei verwende ich immer die Anfangsbuchstaben der jeweiligen Vor- und Nachnamen sowie 

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

# DATENQUELLEN
Die Daten für das Netzwerk werden erhoben aus:
- Mitglieder des VfB: https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/
- Ergänzung der Personendaten durch Munzinger Archiv: https://www.munzinger.de/search/start.jsp 

##
