# Datensatz Pretest Bachelor Netzwerk #
Codebuch Stand 2023-01
erstellt von Marie Sailer (ms594u@hdm-stuttgart.de)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

Das Netzwerk ist ein *ungerichtetes two-mode Netzwerk*. 

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   

**from**
initiierender Knoten

**to**
erhaltender Knoten

**relation**  
1 = Leiter    
2 = Mitglied    
3 = Freunde
4 = Kollegen

**year**
Numerischer Wert der Teilnahme nach Jahr

# NODE-Attribute  

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 

**name**
numerische ID

**type**  
1 = Akteur
2 = Organisation

**sex**
1 = weiblich
2 = männlich

**start**
Ausgangspunkt der Realtity-TV-Karriere, Unterscheidung Bachelor und Bachelorette

**year**
Numerischer Wert der Teilnahme nach Jahr

**place**
Platzierung der jeweiligen Bachelor-/Bachelorettestaffel
