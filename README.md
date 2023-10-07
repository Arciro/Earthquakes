# Earthquakes
In this repository, you can find a Node-RED flow that enables the visualization, through a dashboard, of all the most significant recent earthquakes

## Description
This JSON script, **terremoti.json**, is a Node-RED flow where we have created a dashboard. On this dashboard, you can select any day from the last month and see how many significant earthquakes occurred on the selected day and where they occurred.


## Instruction for use
In order to launch this flow on your local pc, you should satisfy following requirements:

1. The first thing to do is installing Node-RED, that you can do following the procedure at the link [https://nodered.org/docs/getting-started/local](https://nodered.org/docs/getting-started/local)

2. Once this is done, before to import this json script, it is necessary download some libraries. So go to the Menu on top right and click to `Manage pallette`. Here you have to install following modules:
    - node-red-contrib-ui-led
    - node-red-contrib-web-worldmap
    - node-red-dashboard

3. Finally, since on the dashboard you have the possibility to export in txt and csv files all data related to the earthquakes, you have to go on your root file, in my case `C:\` and then you have to create a directory called `Earthquakes`. So if you ckick `Export` on the dashboard, you will see files where are saved all data. If Something changes on you pc you should modify suitably the path in the node `write file`.
