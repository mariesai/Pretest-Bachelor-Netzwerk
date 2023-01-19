# Datensatz Pretest Bachelor Netzwerk #
Codebuch Stand 2023-01
erstellt von Marie Sailer (ms594), Anne Hartung (ah242), Emily Lang (el036), Annika Piper (ap132)

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

Das Netzwerk ist ein *ungerichtetes two-mode Netzwerk*. 

# EDGE-Attribute#

**id**  
(eindeutige Codierung des Knoten)   

**Knoten 1**
Knoten 1 der bestehenden Beziehung

**Knoten 2**
Knoten 2 der bestehenden Beziehung

**relation**  
1 = Leiter    
2 = Mitglied    
3 = Freunde
4 = Kollegen

**year**
Jahr der Teilnahme (Numerischer Wert)

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
Jahr der Teilnahme (Numerischer Wert) 

**exit**
Platzierung der jeweiligen Bachelor-/Bachelorettestaffel (Numerischer Wert)

**age**
Alter zum Zeitpunkt der Teilnahme (Numerischer Wert)
