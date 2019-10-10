# Sample VOD application developed using SparkUI framework (Px Framework) and Java Script. This application runs on top of Spark (PxScene) app engine.

-For windows platform ( if using spark.exe executable) nothing need to be changed
-Quick fix for allignment issues on multiple platform Linux and RPi
    -Observed some allignment issues (need to change y positions) So added Fix for Linux and RPI platform
    -please follow given comments inline in app.js 

Download Spark (PxScene) app engine link: https://www.sparkui.org/docs/getting_started.html

# Implementations:
  - Vertical scroll
  - Horizontal scroll
  - Made Rounded corner image using SVG
  - Made rounded corner highliter using SVG
  - Dynamic content loading on Horizontal scroll
  
# Available Sections:
  - Carousel
  - New Arrival (Trending)
  - Movies
  - TV Shows
  - Categories
  - News

# Used fonts : 
  - for light text: FreeSans.ttf
  - for bold text: work-sans.black.otf 
  
# Media Screen: 1280 x 720

# How to run?
- Clone https://github.com/naseemshekh20/SparkUI_Sample_VOD_App.git repository goto dir SparkUI_Sample_VOD_App and copy absolute path of the file "app.js" or Download "https://github.com/naseemshekh20/SparkUI_Sample_VOD_App/archive/master.zip" zip folder, unzip folder and copy absolute path of the file "app.js" and paste in the spark app engine (Spark Browser) addressbar and hit enter button.

#Used locally configured data in json fomat and retriving from data.json file to display/load contents dynamically
