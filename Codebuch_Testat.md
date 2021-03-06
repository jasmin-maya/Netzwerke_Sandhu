# Datensatz Kohlekommission #
Codebuch Stand 2020-07-31   
erstellt von Jasmin Maya (jm133@hdm-stuttgart.de)

## Inhalt
- Edgelist_Testat.csv
- Nodelist_Testat.csv
- Codebuch_Testat.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Analysiert werden soll das Netzwerk der Mitglieder der Kohlekommission. Ich habe den Datensatz aus folgenden Datenquellen erhoben:
https://www.klimareporter.de/deutschland/das-sind-die-mitglieder-der-kohlekommission
https://www.bmwi.de/Redaktion/DE/Pressemitteilungen/2018/20180606-bundeskabinett-setzt-kommission-wachstum-strukturwandel-und-beschaeftigung-ein.html
https://www.munzinger.de/search/start.jsp
https://www.abgeordnetenwatch.de/

Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*.


# Codebuch


# Edge-Attribute

**from**
(ID Mitglied der Kommission)

**to**
(Alle Mitgliedschaften der Person)


# Node-Attribute

**id**
(Identische ID wie aus der Edgelist)

**label**
(Vollständige Bezeichnung der Knoten)

**type**
1 = Person 2 = Organisation 3 = Partei 4 = Unternehmen

**sex**
(Geschlecht der Mitglieder)
1 = männlich 2 = weiblich

**age**
(Alter der Mitglieder)
1 = 20-30 Jahre 2 = 30-40 Jahre 3 = 40-50 Jahre 4 = 50-60 Jahre 5 = 60-70 Jahre 6 = 70-80 Jahre 7 = 80-90 Jahre 8 = tot

**party**
(Mitgliedschaft in politischer Partei)
1 = keine 2 = CDU/CSU 3 = SPD 4 = FDP 5 = Die Grünen

**representation**
(Funktion innerhalb der Kommission)
1 = Politik 2 = Wirtschaft 3 = Gewerkschaft 4 = Umwelt 5 = Regionen 6 = Wissenschaft

**position**
(Position innerhalb der Kommission)
1 = kein Stimmrecht 2 = Mitglied 3 = Vorsitz

**state**
(Bundesland)
1 = Baden Württemberg 2 = Bayern 3 = Berlin 4 = Brandenburg 5 = Bremen 6 = Hamburg 7 = Hessen 8 = Mecklenburg-Vorpommern 9 = Niedersachsen 10 = Nordrhein-Westfalen 11 = Rheinland-Pfalz 12 = Saarland 13 = Sachsen 14 = Sachsen-Anhalt 15 = Schleswig-Holstein 16 = Thüringen

**proclimate**
(Tätigkeit im Bereich Klimaschutz)
1 = Ja 2 = Nein
