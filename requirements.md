# Introduction #
This project consists in building an image classification system, which takes images as input and gives a prediction -in percentages- of what would be on these given images. For instance, the system may receive an image of a human face as input, after treating the data, the output is then represented in a small list of objects that may be on the picture, ordered by their probability percentages. In this case, the system should display a list, whose first element "human face" is, next to the probability which the system calculated for this result.

The motivation behind this project is artificial neural networks. These are computing systems which were inspired by the biological neural network of an animal. Such systems gain knowledge in executing tasks -in our case image recognition- through a certain training. For an image recognition neural network to correctly perform its task, it is required to analyze examples of images that have been manually labeled. Other uses where artificial neural networks are deployed are predictions, function approximations, or real life patterns recognition...

Nowadays, machine learning is gaining in importance as the goal of including machines in various activities -industries, services, economy- in order to reach high levels of efficiency is in need of artificial intelligence. Indeed, under the applications of artificial neural networks, we can mention autonomous driving, natural language processing, gesture recognition, and of course, face recognition, which is the main application of this project.

It must not be forgotten to mention as well, that there exists different neural networks models, such as Back-Propagation, Boltzman Machines and Deep Neural Networks, with which we will deal in this project. In particular, we will deal with "AlexNet", which is a convolutional neural network consisting of 8 layers, 5 of which are convolutional while the others are fully-connected layers.

On one hand, deploying deep neural networks not means unlocking a massive parallelism potential for our system, but it also means that unsupervised learning is most definitely possible. On the other, we are in need of a huge data set for this unsupervised training. It is important to mention as well, that deep neural networks require intense computations, which manifests itself in high power consumption and learning and classification time.

For the sake of decreasing the number of disadvantages of deep neural networks, the decision of using heterogeneous platforms such as CPUs, GPUs and FPGAs was made. These will provide the system with a good performance for a wide range of computations, as well as a decent usage of pipelines and parallelism, and of course, all with low power consumption.

To take a taste at the fascinating world of machine learning and artificial neural networks, we invite you to try out our image recognition system, and maybe even have a little fun with it.


# Target specifications #

## Must-requirements ##

* The system must be able to classify images.
* The system must employ artificial neural networks
* The system must deploy the AlexNet deep neural network.
* The system must be able to execute intense calculations through heterogeneous platforms (CPU, GPU, FPGA, ASIC).
* The system must support an FPGA through OpenCL.
* The system must offer three performance profiles : 
   -High Performance
   -Low Power
   -Energy Efficency
* The system must allow the control and the execution of commands through a GUI interface.
* The system must exhibit a classification interface.
* The system must be able to measure its performance.
* The system must be able to measure its power consumption.

## Can-Requirements ##

* The system can deploy a GPU.
* The system can deploy a DSP.
* The system can deploy the GoogleNet neural network next to AlexNet. 
* The system can allow the training of neural networks.
* The system can display the topology of the neural network.Kann die Topologie des Neuronalen Netzes anzeigen.

## Criteria of demarcation ##
* The system isn't expected to support real-time applications.
* The system isn't expected to run on mobile-plattforms.

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

# Bedienoberfläche #

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


