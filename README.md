A2 GEANT4 SIMULATION
==================

works with GEANT4.9.6 p02

Prerequisites
-------------
* CERN ROOT  (tested at now with version ROOT 5.34/12)
* git
* XercesC
* CLHEP
* GEANT4.9.6p02
* For polarised targets the magnetic field map (transverse only) is here ( http://www.ph.ed.ac.uk/nuclear/G4/wouter_field_map.dat  ).

Installation
------------

In order to install, just:
* mkdir build
* cd build
* cmake ../
* make

option to speed up compilation, make -j (her put the number of CPU)
