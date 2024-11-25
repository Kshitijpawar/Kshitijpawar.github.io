---
title: Flutter Control App
summary: Flutter mobile app to view collectibles and question-answering for Control video game
date: 2023-03-07

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''

authors:
  - admin

tags:
  - Academic
  - Hugo Blox
  - Markdown
---
[Github Link](https://github.com/Kshitijpawar/Control_collectibles_app)
{{< toc mobile_only=true is_open=true >}}
# Mobile App to view collectibles from 2019 video game [Control](https://en.wikipedia.org/wiki/Control_(video_game)) by Remedy Entertainment.

## Data scraped using Python Scrapy library and stored in Firebase Realtime database. Flutter frontend for mobile application

## Folder structure

- controlscrape: Scrapy code
- control_lore: Flutter application 

## Setup for mobile app 
Prerequistes - Flutter SDK. [How to Install](https://docs.flutter.dev/get-started/install)   
Clone the offline_json branch and cd into control_lore folder to run the following commands.  
    
    flutter pub get 
    flutter run

## To Do
- Scrape multimedia youtube links and add to mobile app as url redirect button
- ~~Add local json load and parsing instead of firebase dependency.~~
- QA System hosted on server(Provided I get resources to host the models lol)
## Images
<br></br>
<br></br>
<img src="images/Screenshot_1678166339.png" alt="screenshot 1" height="500"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="images/Screenshot_1678166348.png" alt="screenshot 2" height="500"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="images/Screenshot_1678166356.png" alt="screenshot 3" height="500"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="images/Screenshot_1678166367.png" alt="screenshot 4" height="500"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="images/Screenshot_1678166382.png" alt="screenshot 5" height="500"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;