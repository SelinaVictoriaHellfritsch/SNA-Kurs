# Datensatz Testat sh308#
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
d

**to**  
d


# NODE-Attribute  
  
**id**  
Identische ID mit edge Liste. Gibt eine eindeutige ID in Kurzform des Namens der Person oder Organisation an.

**type**    
Gibt an, ob es sich um eine Person oder Organisation handelt.
0 = person
1 = organisation
  
**age***    
Gibt das Alter der Akteure in natürliche Zahlen ohne Skalierung an.

**funktion**   
Gibt die Funktion der Akteure an.
V = Vorstand
AR = Aufsichtsrat

**representation**    
Bezieht sich auf die Funktion innerhalb der VfB Gremien: Politik, Wirtschaft, Gewerkschaft, Umwelt, Sport, Wissenschaft, etc.
  
**position**    
Gibt die Position in der VfB Organisation an: Vorsitz, Stellvertreter, Mitglied

# DATENQUELLEN
Die Daten für das Netzwerk werden erhoben aus:
- Mitglieder des VfB: https://www.vfb.de/de/1893/club/vfb-ag/organe-der-vfb-ag/
- Ergänzung der Personendaten durch Munzinger Archiv: https://www.munzinger.de/search/start.jsp 

##
