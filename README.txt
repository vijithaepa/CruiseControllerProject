CruiseControllerProject
===========

This Simple Application for demonstrate CruiseControl build automation configuration.


Contents :
==========
CCBUILDS
│   cc-build.properties
│   cc-build.xml
│   config.xml
│   cruisecontrol.log
│   guide.txt
│   README.txt
│
├───cc-lib
│       maven-ant-tasks-2.1.3.jar
│
├───checkout
│       cruisecontrol.log
│
└───logs
    │   2013_05_30.request.log
    │
    └───Alogorithms

Building the Project.
====================

Tools used
--------------
JDK 1.6.0_45
Maven 2 or higher
Ant 1.9.1
cruisecontrol-bin-2.8.4
set java_home, ant_home and m2_home.

Steps:
------
manual process : 
1 - Add ant-junit.jar in lib folder of CruiseControl (else error on build)

Running the application.
========================
C:\Personal\Vijitha\CCBuilds>C:\SWTools\cruisecontrol-bin-2.8.4\cruisecontrol.bat



