# 581RidesharingProject
CS 581 - DBMS Ridesharing Project

Instructions on How to Run

# Preliminary Things
1) Install Jupyter Notebook software: http://jupyter.org/install.html

2) Setup Graphhopper API Locally
   1. Install the latest JRE and get GraphHopper Server as [zip](https://graphhopper.com/public/releases/graphhopper-web-0.6.0-bin.zip). Unzip it. 
   2. Copy this OSM file into the SAME unzipped directory: [new-york-latest.osm.pbf](http://download.geofabrik.de/north-america/us/new-york-latest.osm.pbf)
   3. Start GraphHopper Maps via: `java -jar graphhopper-web-0.6.0-with-dep.jar jetty.resourcebase=webapp config=config-example.properties osmreader.osm=new-york-latest.osm.pbf`. The first time you run it, it will take a while to load the whole map. Anytime thereafter it will run right away.
   4. Test to see if its running after you see 'Started server at HTTP 8989' by going to [http://localhost:8989/](http://localhost:8989/) and you should see a map of New York. 
   5. Keep this running when executing our program because this is the API

3) Clone/Download Git Repository: Specifically Delay1_2.xlsx, Delay1_3.xlsx, Delay1_5.xlsx, and Ridesharing Program.ipynb

# Running Ridesharing Program
1) Start Jupyter Notebook and open Ridesharing Program.ipynb
2) In order to run the program, you will have to compile every cell. Follow the directions in the notebook. They are straightforward.

# Important Notes
1) Depending on your processor, when running our program, processing times may be extremely long specifically when k=3, pool window of 5 minutes, and the number of pools you process is a large number. I would experiment with smaller numbers. Use the examples given first.
2) 
