# Einleitung #

# Zielbestimmung #

## Muss Kriterien ##

* Muss Bilder klassifizieren können
* Muss Neuronale Netze verwenden
* Muss Alex Net unterstützen
* Muss teure Berechnungen an Beschleunigungshardware weiergeben können
* Muss FPGA durch OpenCL unterstützen
* Muss Profile High Performance, Low Power und Energy Efficency unterstützen
* Muss per GUI steuerbar sein
* Muss Schnittstelle für Klassifikation vorweisen
* Muss Performance messen können
* Muss Verbrauch messen können

## Kann Kriterien ##

* Kann GPU unterstützen
* Kann DSP unterstützen
* Kann Google Net unterstützen
* Kann Training von Neuronalen netzen unterstützen
* Kann die Topologie des Neuronalen Netzes anzeigen

## Abgrenzungskriterien ##
* Keine Echtzeitanwendung
* Nicht für Moblile Plattformen

# Produkteinsatz #

## Einsatzgebiet ##
* Vergleichssystem
* System zur Massenklassifikation
* Subsystem

## Zielgruppe ##
* Entwickler von vergleichbaren Systemen
* Nutzer die viele Bilder zu klassifizieren haben
* Systeme die eine Bildklassifikation gebrauchen können

## Betriebsbedingungen ##
* Hardware und Software wie unten vorhanden
* System und mögliche Nutersysteme sind installiert
* Bilder müssen über Dateisystem zugänglich sein

# Produktumgebung #

## Software ##
Ubuntu 16.04
QT

## Hardware ##
Workstation
FPGA

# Produktfunktionen #
* Auswahl Netz
* Auswahl Profil
* Auswahl Bilder
* Start der Verarbeitung
* Pause der Verarbeitung
* Stop der Verarbeitung

# Produktdaten #
* Gewichte für Neuronales Netz
* Bilder

# Systemmodell #

## Modell ##
* Neuronales Netz
* Convolutional part

## View ##
* Anzeige des Bildes/Ordners
* Anzeige des Profils
* Anzeige des Netzes

## Controller ##
* Bilderwahl/Ordnerwahl
* Wahl des Profils
* Wahl des Netzes

# Produktleistungen #

# Graphical User Interface #
## Introduction ##
* The GUI, which represents the front-end, is the communication channel between the user and the back-end. It will guide users through the variety of operations which can be performed by the System.

## Start-Window ##
* After program start a welcome window, with informations on the Software, will be displayed.(See figure x.xx)

## Choose-Operation-Window ##
* After clicking on Start-button in the start-window, another window will pop up. The user will have to chose a running mode:
1- High Performance
2- Low Power Consumption
3- High Energy Efficiency
and browse to the image path
* See figure (x.xx)

## Browsing-Window ##
* The browser window allows a user to specify his input image.

## Error-Window ##
* If the operation mode or the input data was not specified an error is shown to notify the user. Here we can create two windows for each error See figure (x.xx)

# Qualitätszielbestimmungen #
* Durch die Beschleunigungshardware soll eine Beschleunigung oder eine Energieersparnis erreicht werden
* Die Testabdeckung soll möglichst hoch sein

# Testfälle und Testszenarien #

# Entwicklungsumgebung #
* Altera SDK
* Eclipse
* Git
* Latex
* Markdown
* Ubuntu
* Gcov

# Glossar #

* Neuronale Netze
* Alex Net 
* FPGA GUI
* GPU
* DSP
* Google Net
* Beschleunigungshardware
* High Performance
* Low Power
* Energy Efficency
* Ubuntu
* QT
* Workstation
* Echtzeitanwendung
* Moblile Plattformen


