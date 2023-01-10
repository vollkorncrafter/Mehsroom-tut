# Mehsroom-tut
---
## 1. Bilder hinzufügen
![Alt text](bilder.png "a title")
Zuerst müssen die Bilder die für den 3D-Scan verwendet werden sollen in die Bilder-Ablage Gezogen werden.

## 1.1 (nur für nutzer ohne Nvidia Grafikkarte)
![Alt text](deln.png "a title")
Die 3 Nodes mit den Tieln: "PrepareDenseScene", "DepthMap" und "DepthMapFilter" müssen entfernt werden, da diese eine Cuda-Fähige (Nvidia) Graffikarte benötigen. Die Nodes können mit einem Rechtsklick und einem Folge-Klick auf "Delete Node" Gelöscht Werden.

## 1.2 (nur für nutzer ohne Nvidia Grafikkarte)
![Alt text](cnn.png "a title")
Jetzt muss der punkt "SFMData" der Node "StructureFromMotion" mit dem punkt "SFMData" der Node "Meshing" verbunden werden.
Der erste Punkt muss 
## 2
![Alt text](start.png "a title")
Jetzt kann der Start Knopf betätigt werden. Danach hat man die option das Projekt zu speichern.
