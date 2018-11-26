# Week 9 Project: Honeypot

Time spent: 40 hours spent in total

### Project summary 

In this project we stand up a basic honeypot and demonstarte its effectiveans at detecting and collecting data about an attack. The project requires to use a well-supported open source honeypot, which is Modern Honey Network(MHN). MHN is a centralized server for management and data collection of honeypots.


<img src="9.gif" width="800">
### Exporting Data

Attempted to export session file 
<img src="9.png" width="800">
mongoexport --db mnemosyne --collection session > session.json
-bash: session.json: Permission denied
