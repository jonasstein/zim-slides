TroLUG 2015-02-05
-----------------
.. image:: globe.png
   :width: 20%



	

Installation
------------
.. code-block:: bash
     
     $ apt-get install zim # aktuell 0.60
     $ emerge x11-misc/zim # 0.62 ~amd64

* auch für Windows und Mac OS X


Features
--------
* git Versionskontrolle
* Formeln mit LaTeX
* Bildschirmfotos mit einem Klick
* Links auf Webseiten, Ordner und Dateien
* Schlagworte (tags)
* viele Exportfilter

  

Erster Start
------------
.. code-block:: bash

     $ zim
     # oder mit einer anderen als der Systemsprache starten::
     $ LANG=de_DE ./zim.py
     $ LANG=en_EN ./zim.py  



Syntax
------
.. code-block:: bash

     Syntax ist an dokuwiki angelehnt
     
     =Erste Überschrift
     =====Untertitel
     
     :Link auf oberste Ebene
     +Link auf Unterseite

     * Aufzählung
     [] Todo
     [x] erledigt
     [*] abgebrochen
     
     **Fett** //kursiv// __unterstrichen__ ''Code''

     {{bild.png}}
     

.. header::

        zim - Wissensmanagement

.. footer::

        2015-02-05 Jonas Stein, TroLUG http://trolug.de/
