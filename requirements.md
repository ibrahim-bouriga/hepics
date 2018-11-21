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

# Product Use #
 
 ## Use Range ##
 This program is designed for image classification. The user or subsystem can use this program to recognize pre-specified or learned
 objects or object classes. Owing to running on heterogeneous platforms, user is also allowded to switch various operation modes for
 different goals. Besides, the user can deploy training of an arbitrary neural network and transfer learning of an already implemented
 neural network. 
 
 ## Target Group ##
 * developers of the compared system
 * users who need to classify images
 * systems which process images or solve problem in computer vision 

 
 ## Operation Precondition ##
 The following conditions must be met:
 * Hardware and software as follows must be available: 
     Host PC with Ubuntu 16.04, FPGA
 * System and possible user-system must be installed.
 * Images must be accessible to file system.


# Product Environment #
 
 ## Software ##
 * Ubuntu 16.04 - operating system of Host PC
 * QT - to create classic and embedded GUI
 * OpenCL - framework for writing programs that execute across heterogeneous platforms
 
 ## Hardware ##
 * Lab PC at CDNC institute
 * FPGA

# Product Functions #
 ## Basic Functions ##

 * /F010/ show welcome screen
 * /F020/ show start menu
 * /F030/ choose input image (at least 5 images of an object at various angels)
 * /F040/ reset the selection
 * /F050/ choose operation mode: High Performance, Low Power Consumption, High Energy Efficiency
 * /F060/ start processing
 * /F070/ pause processing
 * /F080/ stop processing
 * /F090/ show output results (names and precents of top 5)
 * /F100/ terminate program


 ## Optional Functions ##

 * /F110/ choose neural network type
 * /F120/ deploy training of an arbitraty neural network
 * /F130/ transfer learning of the already implemented neural network
 * /F140/ show neural network topology
 * /F150/ show output results in clear form (with histogram or pie chart)

# Produktdaten #

## System-Daten ##
* Klassifikation mit Percent Bar

## Benutzer-Daten ##

### /D10/ ###
### Zur Klassifizierung muss das Originalbild sowie das Ergibnis vorgehalten werden ###

### /D20/ ###
#### über einen Kunden sind folgenden Daten zu speichern /LD10/ ####
* Das Bild, das der Benutzer hochlädt.

### /D30/ ###
#### wenn ein Benutzer mehr als ein Bild hochlädt, werden alle Bilder gespeichert gespeichert ###


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

* Zum starten des Programms muss der Benutzer auf start klicken.
* the user have to choose the running mode with one click
* Der Benutzer muss zum Hochladen eines Bildes höchstens drei Tasten betätigen
* Während Klassifizieren eines Bildes muss für den Benutzer ein (Prozent der benötigte Zeit) sichtbar sein.
* No real time requirements

# Bedienoberfläche #

# Qualitätszielbestimmungen #
* Durch die Beschleunigungshardware soll eine Beschleunigung oder eine Energieersparnis erreicht werden
* Die Testabdeckung soll möglichst hoch sein
* Wart- und Wiederverwendbarkeit ergibt sich durch die Implementierung im MVC -Prinzip.
* Robustheit spielt bei der Entwicklung eine maßgebliche Rolle, so dass willkürliches Tastendrücken nicht zum Absturz führt.


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


