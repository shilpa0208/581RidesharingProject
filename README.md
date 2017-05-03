# 581RidesharingProject
CS 581 - DBMS Ridesharing Project

Instructions on How to Run

# Preliminary Things
1) Install Jupyter Notebook software: http://jupyter.org/install.html

2) Setup Graphhopper API Locally
   1. Install the latest JRE and get GraphHopper Server as [zip](https://graphhopper.com/public/releases/graphhopper-web-0.6.0-bin.zip) 
   2. Unzip it. Copy this OSM file into the SAME directory. For example [new-york-latest.osm.pbf](http://download.geofabrik.de/north-america/us/new-york-latest.osm.pbf)
   3. Start GraphHopper Maps via: `java -jar graphhopper-web-0.6.0-with-dep.jar jetty.resourcebase=webapp config=config-example.properties osmreader.osm=new-york-latest.osm.pbf`
   4. Test to see if its running after you see 'Started server at HTTP 8989' by going to [http://localhost:8989/](http://localhost:8989/) and you should see a map of New York.
   5. Keep this running when executing our program because this is the API

3) Clone/Download Git Repository: Specifically Delay1_2.xlsx, Delay1_3.xlsx, Delay1_5.xlsx, and Ridesharing Program.ipynb

# Running Ridesharing Program
1) Start Jupyter Notebook and open Ridesharing Program.ipynb
2) In order to run the program, you will have to compile every cell. Follow the directions in the notebook. They are straightforward.
