![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=rsochaa&show_icons=true&theme=transparent)

# 14497 Netatmo Basis

## Beschreibung 

Der Baustein dient zur Kommunikation mit einer Netatmo Basis Station.

## Eingänge

| Nr. | Name              | Initialisierung   | Beschreibung                                                                                                          |
|-----|-------------------|-------------------|-----------------------------------------------------------------------------------------------------------------------|
| 1   | Intervall         | 0                 | Bei einem Wert <> 0 werden die Daten vom Netatmo Portal zyklisch mit dem angegebenen Intervall in Sekunden abgerufen. |
| 2   | Trigger           | 0                 | Bei einem Wert <> 0 werden die Daten vom Netatmo Portal abgerufen.                                                    |
| 3   | Client ID         | 0                 | Client ID vom Netatmo Portal                                                                                          |
| 4   | Client Secret     | 0                 | Client Secret vom Netatmo Portal                                                                                      |    
| 5   | Refreh Token      | 0                 | refresh-token vom Netatmo Portal                                                                                      |
| 6   | Zeitformat 0/1    | 0                 | Soll eine Umwandlung der Zeitausgabe erfolgen. 0=Nein / 1=Ja                                                          |
| 7   | Format Datum-Zeit | %d-%m-%Y %H:%M:%S | Format der Zeitausgabe                                                                                                |


## Ausgänge

| Nr.    | Name          | Initialisierung | Beschreibung                                                   |
|--------|---------------|-----------------|----------------------------------------------------------------|
| 1ff    | ...           | ...             | Selbsterklärend                                                |
|        |               |                 |                                                                |
| 15/27  | Platzhalter   |                 | Trennung zu den Modulen                                        |
| 28     | Module-output |                 | Output für Zusatzmodule wie Wind- Regenmodul oder Zusatzmodul. | 

## Beispielwerte

| Eingang | Ausgang |
| --- | --- |
| - | - |


## Other

- Neuberechnug beim Start: Nein
- Baustein ist remanent: nein
- Interne Bezeichnung: 14497
- Kategorie: Datenaustausch

### Change Log
- v0.6
  - Aenderung Abfrage und Aufbau
- v0.5
     - Interall angepasst
- v0.3
     - Zeitformatierung hinzugefügt
 - v0.2
     - div. Anpassungen  
 - v0.1
     - Initial

   


## Requirements


## Licence

Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
