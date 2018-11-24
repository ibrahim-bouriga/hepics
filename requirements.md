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
 
 ## Field of application ##
 This program is designed for image classification. The user or system can use this program to recognize pre-specified or learned objects. Because the system runs on heterogeneous platforms, the user is allowed to switch between various operation modes depending on power or performance preferences.
Victims of strokes or memory problems have a hard time recognizing even the most simple objects we deal with everyday. Building on this system, it would be possible to help these people to rebuild their memories or label the objects presented on the images. It can also help the visually disabled have a better idea about their environment through processing images they choose.
Another application of this system is the optimization of the traffic lights through equipping them with a functionality that would set the traffic free for other sides, if the current side is empty.
We can think about a use in the tourism field as well, as tourists may want to have a better idea about buildings or statues of the city they are visiting, which they can do through our system.
 
 ## Target Group ##
 * people with impaired vision
 * tourists
 * developers of other systems
 * users who need to classify images
 * systems which process images or solve problem in computer vision

 
 ## Operation Condition ##
 The following conditions must be met:
 * Hardware and software as follows must be available: 
     Host PC with Ubuntu 16.04
     FPGA
 * System and possible user-system must be installed.
 * Images must be accessible to file system.
 * Host PC must be powered.
 * FPGA must be powered.
 * Images must be JPG.
 * FPGA have to be connected to Host PC.
 * There must be enough storage for the program.
 * There must be enough storage to store results. 
 


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

# Product-Data #
 ## System-Data ##

  * /D10/classification with percent bars

 ## User-Data ##
 
  * /D20/ For classification the original image and the result must be kept.
  * /D30/ The following user-data should be saved: /LD10/ 
     * Image that the user uploads
  * /D40/ If a user uploads more than one image, all images will be saved.


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

# Product Performance #
 * To start the program, the user must click start-button.
 * User must choose the operation mode with one click.
 * The user does not need to press more than three buttons to upload an image.
 * While classifying an image one percent of the time required must be visible to the user .
 * No real time requirements.

# Bedienoberfläche #

# Quality Specification #
* The acceleration hardware should accelerate or save power consumption.
* The test coverage should be as high as possible.
* Maintenance and reusability results from the implementation in the MVC principle.
* Robustness plays a crucial role in the development, so that arbitrary keystrokes do not lead to a crash.

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


