# a07g-exploring-the-CLI

* Team Number: Team 10 
* Team Name: Web Weaver
* Team Members: Zhiye Zhang, Yunlong Han
* GitHub Repository URL:
* Description of test hardware: (development boards, sensors, actuators, laptop + OS, etc)

# 1.Software architecture

## 1. HRS & SRS

HRS:
HRS. 1.The project shall be based on SAMW25
HRS. 2.The project shall have 1 temperature sensor, 1 LCD screen, 1 WiFi Module
HRS. 3.The project should be able to switch between different sensors 
HRS. 4.The project shall use a joy stick to switch between different menus or sensors
HRS. 5.The project shall have a SD card for storage purpose
HRS. 6.The project shall display a main user menu on LCD screen
HRS. 7. The project shall use a buzzer or equivalent component to sound alarms or alerts.

SRS:
SRS 01 - The main menu shall hold the classification of different recipes: BEEF/LAMB, PROK, CHICKEN, VEG, SEAFOOD and OTH
SRS 02 - There shall be a home button on every screen to return to the main menu at any time.
SRS 03 - There shall be a two level menu, the main menu hold the classification of different recipes, the submenu hold the specific recipe.
SRS 04- The first page of recipe shall show the INGR, Prep Time and Cook Time. 
SRS 05- The first page shall also have a START buttom to start cooking instruction.
SRS 06 - The cooking instruction page shall have what to do in the current step, a graphical temperature display, a C/T with a START button, a NEXT button and PREV button
SRS 07 - The graphical temperature display shall should a grap of a thermometer, following with the temperature value, and change color base on the range of temperature, and gives out warning when the temperature is too high. 
SRS 08 - The C/T with a START button shall be able to countdown the cooking time, gives out alarm when the time is over.
SRS 09- The PREV and NEXT button shall be able to switch between different steps of a recipe.
SRS 10- The should be a value display of the kitchen temperature and humidity at every screen.
