
***************************************************************************
*  CiberRato Robot Simulation Environment                                 *
*  Ciber-Rato 2021 - Universidade de Aveiro                               *
***************************************************************************

### Information

CiberRato Robot Simulation Environment simulates the movement
of robots inside a labyrinth.  Robots objective is to go from their
starting position to beacon area and then return to their start position.

http://microrato.ua.pt/

This is the source code release of CiberRato tools.

### Version Info

CiberRato tools v2.2.6.pc

simulator         version 2.2.7.rmi  - October 12, 2021
Viewer            version 2.2.7.rmi  - October 12, 2021
logplayer         version 2.2.7.rmi  - October 12, 2021
robsample         version 2.2.7.rmi  - October 12, 2021
GUISample         version 2.2.7.rmi  - October 12, 2021
jClient           version 2.2.7.rmi  - October 12, 2021

### Contents

simulator/           The simulator source code
Viewer/              The Visualizer source code
logplayer/           The logplayer source code
GUISample/           Graphical robot agent (C++) source code
robsample/           robot agent (C) source code
jClient/             robot agent (Java) source code
pClient/             robot agent (Python) source code
Labs/                examples of labyrinths used in previous competitions

README               This README file

startAll             Startup script that runs the simulator, the visualizer and 5 GUISamples
startSimViewer       Startup script that runs the simulator and the Viewer

### Operating System and Compiler

The source code was compiled with gcc/g++ - Gnu Project C/C++ Compiler
(gcc version  9.3.0) using the Qt libraries (release 5.12.8) on Ubuntu 20.04.

It is required to have the development version of Qt libraries
release 5.x installed in the system prior to compilation.
On Ubuntu 20.04 run the following:
```bash
sudo apt-get install qt5-default qtmultimedia5-dev
```


### Instructions on how to use this release:


To compile the CiberRato tools

        1- execute make:

          make

        if this does not work you may have to execute qmake (or qmake-qt4) before executing make

After compiling, to run the simulator, the visualizer and 3 GUISamples

       ./startAll

After compliling, to run the simulator and the Viewer

       ./startSimViewer

       Then each robot should be started manually

After compiling, to run the logplayer

       cd logplayer
       logplayer -log <logfile>

To run a sample individually

       LD_LIBRARY_PATH=../libRobSock/ ./GUISample

### More Information

    Please consult:
        http://microrato.ua.pt/

    or Please Contact :
        Nuno Lau
        University of Aveiro
        email: nunolau@ua.pt

        Artur C. Pereira
        University of Aveiro
        email: artur@ua.pt

        Andreia Melo
        University of Aveiro
        email: abmelo@criticalsoftware.com

        Antonio Neves
        University of Aveiro
        email: an@ieeta.pt

        Joao Figueiredo
        University of Aveiro
        email: joao.figueiredo@ieeta.pt

        Miguel Rodrigues
        University of Aveiro
        email: miguel.rodrigues@ua.pt

 Copyright (C) 2001-2021 Universidade de Aveiro

