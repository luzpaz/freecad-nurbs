# FreeCAD Nurbs

EN: The Nurbs Workbench is a collection of scripts for managing free-form surfaces and curves.  
DE: Die Nurbs Workbench ist eine Sammlung von Skripten zur Verwaltung von Freiformflächen und Screencast  

![Screenshot]()


### Features
*  
*  
*  
*  

### Installation
##### Automatically via Addon Manager (Recommended)
As of FreeCAD v0.17.9944 the new Addon Manager has been merged. Install this addon by:   
- Opening **Tools** > **Addon Manager** 
- Locating **nurbs** and installing.  
- Relaunching FreeCAD.   

##### Manually install using git
Instructions for Ubuntu & Mint specifically but can be adapted to other distros. 
- Open the command prompt (terminal) with the keys **ctrl+alt+t**   
- Install git:  ***sudo apt-get install git***   
- Clone repository:  ***git clone https://github.com/microelly2/freecad-nurbs ~/.FreeCAD/Mod/freecad-nurbs***   
- Relaunch FreeCAD (workbench should be incorporated automagically).  

##### Manually install via ZIP
- Download https://github.com/microelly2/freecad-nurbs as a ZIP (click 'Clone or Download' button)   
- For Ubuntu, Mint and similar OS's, extract it inside */home/username/.FreeCAD/Mod*   
- For Windows, extract it inside *drive: \Users\your_user_name\AppData\Roaming\FreeCAD\Mod*   
Then  
- Relaunch FreeCAD (workbench should be incorporated automagically).

### Usage

1. Check the provided 'example.fcstd'.  
2. Load the workbench and then click on "Load Example File" inside the workbench commands tab:

![example file]()

Watch the [Nurbs workflow screencast](). 

### Documentation
URL missing
  
### Feedback 
For bugs please open a ticket in the [issue queue](https://github.com/microelly2/freecad-nurbs/issues). For discussion please use the [dedicated Exploded Assembly thread]() in the FreeCAD forums.

#### License 

#### Author
@microelly2

### Videos
* [Sole Sketch](https://www.youtube.com/edit?o=U&video_id=l3U9SAbo9TE) (Screencast 26.06.2017)  
die Schuh-Sohle als eine spezielle Anwendung des Offset und Sketch  
* [Dynamic Offset](https://youtu.be/7wKXfh2fifY) (Screencast 25.06.2017)  
Aus den Offset-Kurven und einer Werteliste wird eine Zwischenkurve berechnet.  
* [SketchObjectPython Star Teil 1](https://www.youtube.com/video_id=xrmjhv9uMoI) (Screencast 23.06.2017)  
* [SketchObjectPython Star Teil 2](https://www.youtube.com/video_id=vinVDF1qL30) (Screencast 23.06.2017)  
Andockbare Sternobjekte für den Straßenbau  
* [Sketcher::SketchObjectPython](https://www.youtube.com/watch?v=U31O5vW4UhI) (Screencast 16.06.2017)  
Aus einem Polygonzug-Sketch wird eine BSpline Kurve berechnet und daraus zwei Offset-Kurven  
verwendete Klassen: Sketcher::SketchObjectPython, Part::Offset2D
* [Video split a nurbs face into 4 segments and replace two of them](https://www.youtube.com/watch?v=bBAU5fpwwk8) (Screencast 07.06.2017)  
Die Oberfläche eines Schuhes wird in 4 Segmente zerlegt. Zwei Segmente (Spitze und Ferse) 
werden durch eigenständige Freiformflächen ersetzt, wobei die Übergänge G0 (Position) und G1 (Tangenten) kontinuierlich sind  
verwendete Klassen: TangentFace, Seam, Segment  
* [A bspline volume from 2 sketches](https://youtu.be/kUbKHtEtus8) (Screencast 01.06.2017)  
Zum Erzeugen einer Schuhspitze oder eines Hecks wird aus ein paar gegebenen Sketcher-Bsplines eine Freiformfläche berechnet.  
Ausgehend von einer Fläche wird eine zweite Fläche erzeugt, deren Kanten zueinander passen. 
Das gesamte Modell lässt sich wieder in einzelnem Segmente zerlegen.  
verwendete Klassen: Segment, TangentFace, Seam

### Links
* [Etwas Theorie von Autodesk Alias (help.autodesk.com)](http://help.autodesk.com/view/ALIAS/2018/ENU/?guid=GUID-B0AAF7CA-FDBD-49FC-88BA-4F1609BC61CE)  
* [Nurbs Workbench Anwenderdokumentation (freecadbuch.de)](http://freecadbuch.de/doku.php?id=nurbs)  
* [Kurven und Flächen-Theorie: Computer Aided Geometric Design by Thomas W. Sederberg](http://cagd.cs.byu.edu/~557/text/cagd.pdf)
