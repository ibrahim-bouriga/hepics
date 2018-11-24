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

# Product-Data #
 ## System-Data ##

  * /D10/classification with percent bars

 ## User-Data ##
 
  * /D20/ For classification the original image and the result must be kept.
  * /D30/ The following user-data should be saved: /LD10/ 
     * Image that the user uploads
  * /D40/ If a user uploads more than one image, all images will be saved.


# Systemmodell #
![](images/MVC%20(3).jpg)
* Programming with less complexity makes delightful code that is less buggy and easier to maintain because it is reusable without modification. In order to achieve this goal we use in this context the MVC architecture wich consists of:

## Modell ##
* The model represents the data, and does nothing else. The model does NOT depend on the controller or the view. It contains the pretrained neural network model AlexNet as well as the classification algorithm to be used on images.

## View ##
* The view displays the model data, and sends user actions (e.g. button clicks) to the controller. It represents the graphical user ineterface wich interacts with the user (See Graphical User Interface)

## Controller ##
* The controller provides model data to the view, and interprets user actions such as button clicks. The controller depends on the view and the model.

# Product Performance #
 * To start the program, the user must click start-button.
 * User must choose the operation mode with one click.
 * The user does not need to press more than three buttons to upload an image.
 * While classifying an image one percent of the time required must be visible to the user .
 * No real time requirements.

# Graphical User Interface #
## Introduction ##
* The GUI, which represents the front-end, is the communication channel between the user and the back-end. It will guide users through the variety of operations which can be performed by the System.

## Start-Window ##
* After program start a welcome window, with informations on the Software, will be displayed.(See figure x.xx)
![](images/Main_Window.png)

## Choose-Operation-Window ##
* After clicking on Start-button in the start-window, another window will pop up. The user will have to chose a running mode:
* 1- High Performance
* 2- Low Power Consumption
* 3- High Energy Efficiency
and browse to the image path
* See figure (x.xx)
![](images/operation_mode_window.png)

## Browsing-Window ##
* The browser window allows a user to specify his input image.

## Error-Window ##
* If the operation mode or the input data was not specified an error is shown to notify the user. Here we can create two windows for each error See figure (x.xx)

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


