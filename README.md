# CSA-SoLawi-Management-Excel
Mitglieder, Abholstellen und Ernteanteil verwalten in Excel.

# Download
SoLawi v4.9.xlsm

# Setup
## Referenzdaten
![Referenzdaten](/Screenshots/Referenzdaten.PNG)

Die 1. Tabelle **Familie** ist nur für die Sortierung der Artikelliste nach Kategorie.

Die 2. Tabelle **Einheit** definiert die verwendeten Einheiten.

In der 3. Tabelle **Abholort** werden die Abholorte mit ihren Abkürzungen festgelegt. Summe ist immer Teil dieser Liste.

In der 4. Tabelle **Abholtag** werden die Abholtage festgelegt.

Die 5. Tabelle **Anteil** legt die möglichen Anteile fest, die ein Mitglied haben kann.

## Mitglieder
![Mitglieder](/Screenshots/Mitglieder.PNG)

**Achtung!** Die ersten 5 Überschriften dürfen in ihrer Reihenfolge und ihrem Inhalt nicht verändert werden!

**Achtung!** In der Spalte **Nachname** düfen KEINE leeren Felder sein!

## Artikel
![Artikel](/Screenshots/Artikel.PNG)

In der **Ernteliste** werden die Mengen immer auch in Verpackungseinheiten angegeben. Siehe [Ernteliste](/README.md#ernteliste)
## Orte (Abholstellen und Tage)
![Orte (Abholtage)](/Screenshots/Orte%20(Abholtage).PNG)

Diese Tabelle definiert den Aufbau der Ernteliste.
# Anwendung
## Ernteanteil erstellen
![Orte (Abholtage)](/Screenshots/Ernteanteil.PNG)

1. Artikel per Dropdown auswählen
2. Sorte und Anmerkungen hinzufügen
3. Für Großen und Kleinen Anteil die Mengen festlegen

**Achtung!** In der Spalte **Artikel** düfen KEINE leeren Felder sein!
## Ernteliste
Die Ernteliste gibt die Mengen an, die geerntet und in die jeweilige Abholstelle geliefert werden müssen.

1. Auf **Ernteliste** Klicken
![Ernteliste Button](/Screenshots/Ernteliste%20Button.PNG)
2. Kalenderwoche eingeben
![Kalenderwoche](/Screenshots/KW.PNG)
3. Jahr eingeben
![Jahr](/Screenshots/Jahr.PNG)
4. Die Tabelle wird erstellt und der Druckbereich automatisch festgelegt. Existiert eine Tabelle mit gleichem Datum, wird diese überschrieben. 
5. Drucken: **Strg+P**
![Ernteliste](/Screenshots/Ernteliste.PNG)
Die ersten 3 Spalten sind der Ernteanteil als Referenz.
![Ernteliste Ernteteil](/Screenshots/Ernteliste%20Ernteteil.PNG)
Danach hat jede Kombination aus Tag und Abholstelle 2 Spalten. 
![Ernteliste Abholstelle](/Screenshots/Ernteliste%20Abholstelle.PNG)
Die Linke Spalte zeigt die Mengen in kg, stk... an, die rechte Spalte zeigt die anzahl der Verpackungseinheiten an.
## Ernteanteil Druck
## Abhakliste
## Lieferungskalender
## Fehlersuche - Troubleshooting
1. Überschriften von Tabellen sollten nach Möglichkeit **nicht geändert oder in ihrer Position verschoden werden**.
2. Es sollten keine **Leerzeilen** in Tabellen sein, da Tabellen sonst nur bis dorthin ausgewertet werden. Siehe [Mitglieder](/README.md#mitglieder)

