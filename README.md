<p align="center"><img title="Tomb Raider Nostalgia" src="resources/picture/logo.png"/></p>


Tomb Raider Nostalgia - View levels and play cut scenes for old Tomb Raider games 1/2/3/4.

[Browse and view TR1/2/3/4 levels](https://popov72.github.io/TRN2/)

Main keys are:
  * **Z/Q/S/D** to move into the level (**A/W/S/D** in QWERTY mode)
  * **SPACE** / **X** to go UP/DOWN
  * **Right mouse button** to take control of (and release) the rotation of the camera with the mouse
  * **ENTER** to show/hide the informational panels

Hit the **H** key to display an help panel that lists all the keys you can use.

Cutscenes are the levels with a <img src="resources/picture/movie.png" width="24px"/> icon after the level name.

You can browse local levels on your hard drive by browsing the [**TRN.html** page](https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../). In this page, click on the **Select files** button and select an original TR level on your hard drive.

## 3D Engines
You can use either [BabylonJS](https://babylonjs.com) or [Threejs](https://threejs.org/) to browse a level: select the engine you want in the corresponding dropdown box.

Note that if you choose Threejs you won't have some particle effects, as Threejs don't feature such a particle system module. That's why BabylonJS is the default selected engine.

## Install
You can install the project locally (on your own computer) by doing these steps:
* Click on the **Clone or download** button in this page (see above) and download a zip archive of the project
* Uncompress this zip file on your computer (say in *c:\Projects\TRN2*)
* Install Python on your computer if you not already have it. To check if you already have Python installed:
  * Start a command line (type **cmd** in the search input of Windows and hit ENTER)
  * Type **python** then ENTER: if you get an error message, you don't have Python installed. To install it:
    * Download the package from the [Python web site](https://www.python.org/downloads/)
    * Launch the installation.
    * **__Important__**: check the **Add Python 3.7 to PATH** (3.7 or whatever the current version of Python is) checkbox that you can see at the bottom of the first screen! If you don't do it, you will have to put the Python path to the global **PATH** variable yourself
* Start Python has a simple HTTP server:
  * Start a command line (type **cmd** in the search input of Windows and hit ENTER)
  * Go to the directory where you installed TRN (for eg: **cd c:\Projects\TRN2** + ENTER)
  * If your version of Python is 3.x or more, type:
    * **python -m http.server** + ENTER
  * else type:
    * **python -m SimpleHTTPServer** + ENTER
* In your browser, browse the url http://localhost:8000. You can also browse http://localhost:8000/babylonJS/public/TRN.html?relpath=../../ if you want to display a level located on your hard drive

Note that you can use any web server for this matter. I described how to use Python to do that, but if you have another web server already installed on your computer, go for it.

You can also use PHP in much the same way than Python to start a simple HTTP server: install PHP on your computer (if not already installed), then use the command **PHP -S localhost:8000** from the TRN directory to start a simple web server.

## Credits
* **XProger**: I have stolen and ported the _Braid_ class from his awesome [OpenLara](https://github.com/XProger/OpenLara) as well as some other ideas (like the _Layer_ concept)
* **Sapper** and **T4Larson**, who did a great job deciphering the TR4 cutscene file format: no TR4 cutscene replay without them! The description of the format can be found [**here**](https://www.trsearch.org/tool/32/download)
* All people from the **Tomb Raider** community for their continuing support

## Screenshots
Click on the picture to view the corresponding level.<br>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&trgame=TR1&level=tr1/level2.phd&autostart=1"><img title="City of Vilcabamba" src="resources/picture/TR1_big/level2.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR1&level=tr1/level10b.phd&autostart=1"><img title="Atlantis" src="resources/picture/TR1_big/level10b.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR1&level=tr1/cut4.phd"><img title="Lara vs. Natla" src="resources/picture/TR1_big/cut4.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR2&level=tr2/boat.tr2&autostart=1"><img title="Venice" src="resources/picture/TR2_big/boat.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR2&level=tr2/xian.tr2&autostart=1"><img title="Dragon's Lair" src="resources/picture/TR2_big/xian.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR2&level=tr2/cut3.tr2"><img title="Bartoli vs. Monk" src="resources/picture/TR2_big/cut3.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR3&level=tr3/nevada.tr2&autostart=1"><img title="Nevada Desert" src="resources/picture/TR3_big/nevada.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR3&level=tr3/city.tr2&autostart=1"><img title="Lost City of Tinnos" src="resources/picture/TR3_big/city.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR3&level=tr3/cut2.tr2"><img title="Saved by the Bell" src="resources/picture/TR3_big/cut2.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR4&level=tr4/csplit1.tr4&autostart=1"><img title="Catacombs" src="resources/picture/TR4_big/csplit1.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR4&level=tr4/palaces.tr4&autostart=1"><img title="Pharos,Temple Of Isis" src="resources/picture/TR4_big/palaces.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&?trgame=TR4&level=tr4/palaces2.tr4&autostart=1"><img title="Cleopatra´s Palaces" src="resources/picture/TR4_big/palaces2.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&engine=babylonJS&trgame=TR4Cut&level=tr4/ang_race.tr4&autostart=0&cutscene=9"><img title="Revealing Iris, Von Croy getting trapped and Young Lara going for help" src="resources/picture/TR4Cutscene_big/cutscene_9.jpg"/></a>

<a href="https://popov72.github.io/TRN2/babylonJS/public/TRN.html?relpath=../../&engine=babylonJS&trgame=TR4Cut&level=tr4/settomb2.tr4&autostart=0&cutscene=14"><img title="Lara pulling Ankh off Seth's Tomb" src="resources/picture/TR4Cutscene_big/cutscene_14.jpg"/></a>
