# SUMO Starter Kit
Author: ***Hsien-wen "Steven" Deng***\
This is a starter kit for **[Simulation Urban MObility](https://sumo.dlr.de/docs/index.html)** (**SUMO**) with **[Traffic Control Interface](https://sumo.dlr.de/docs/TraCI.html)** (**TraCI**). In this case, we build a scenario referenced our testbed in Perimeter Rd., Clemson, SC. 10 vehicles are generated in this scenario and all vehicles are following a speed limit of 35 mph and perform a time headway of 1 second. Besides, 3 traffic controllers (signals) are deployed in 3 intersections and all controllers are fixed time.\
**SUMO** is a traffic engineering simulator to simulate different traffics in macroscopic or microscopic view. \
**TraCI** is a python-based platform to engage interactions (control, feedback) between user's scripts and SUMO.

## Prerequisite
1. [Python 3.8](https://www.python.org/downloads/)
2. Python IDE, recommend [Pyzo](https://pyzo.org/start.html)

## Deploy Application
1. Download [SUMO](https://www.eclipse.org/sumo/)
1. Install **SUMO**
2. Place downloaded **[SUMO_Sample](https://github.com/stevenxdeng/SUMO_Starter_Kit)** folder in installed SUMO directory: `../sumo/`

## Run Application
1. Run *SUMO_Base.py* by Pyzo or by command: `python SUMO_Base.py`
2. From SUMO GUI, tune the **delay** to max (1000ms) 
3. Hit the Run button in SUMO GUI

## Modify Application
*Here are the tips for expanding your own application by TraCI*
1. Get vehicles number
2. Get vehicles states (positions, speeds)
3. Change vehicles states (speeds)
4. Get traffic controllers phase
5. Get traffic controllers timer
