---
title: "My Office"
author: "Chunna"
date: "9/18/2019"
output:
  html_document: default
  pdf_document: default
---


## Here is my Office

library(leaflet) 
my_map <-leaflet() %>% addTiles()
my_map <-my_map %>% addMarkers(lat=46.280418, lng= -119.2752, popup="My Office")
my_map}

