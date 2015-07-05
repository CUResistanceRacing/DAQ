This is the schematic and PCB design files for the DAQ. 
Do not use regular github app to manage this project! Only use Altium to connect to this repo. 

How to connect to this repo via Altium 14:

1. Go into the Preferences window and go into Design Repositories under Data Management. 
2. Click Create New (SVN)
    Name: DAQ
    Method: https
    Server: github.com
    Server Port: default
    Repository Subfolder: /tincanman/DAQ
3. Click on Test and then log in.
4. Now that the repo has been added, go into File->Check Out
5. Select the DAQ repo and choose a local destination to check out the repo to. 
6. Now you just open up the project in Altium and start working on it.

Some basic usage info:
Commit as often as possible. This version control is not very well suited for PCB design as for code. 
To access the version control features, right click on any file of the project and go to Version Control.
Everytime you start up Altium, be sure to first Refresh the project and if needed, Update Whole Project.
You can either commit individual files or the whole project. If you only worked on a single file, then just commit that single file. If you messed up and need a previous version, click on Revert Local Modifications. Lock will be used in the future.

Schematic Todo:
- [x] Create SD card symbol, footprint, and sheet.
- [ ] Finishes all external peripheral connections for MCU
- [ ] Add external power filtering and isolation to power supply
- [ ] Add crystal and programming interfaces to MCU
