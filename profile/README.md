
```mermaid
flowchart LR
  subgraph iOS & OSX
    c1(STCiOSXDataCollector)
    click c1 href "https://github.com/STCData/STCiOSXDataCollector"
  end
  
  subgraph Linux
    c2(STCX11DataCollector)
    click c2 href "https://github.com/STCData/STCX11DataCollector"
  end
  subgraph Android 
    c3(STCDroneDataCollector)
    click c3 href "https://github.com/STCData/STCDroneDataCollector"
  end
  subgraph Cloud
    s[(STCDataServer)]
    click s href "https://github.com/STCData/STCDataServer"
  end
    c1 & c2 & c3 -.-> s
```

[STCData] is a system for collecting data from user devices for machine learning. Features include:

 - Support for video, image, speech, text and structured data mining
 - Data collection applications for [iOS, MacOS], [Android], [Linux]
 - On device real time data pre-labeling using fast [vendor provided] models
 - Realtime data streaming
 - [Data offloading to eventually available servers and pre upload on device data storage balancing]


STCData could be used both as a starting point for building out your own data collection pipeline or as ready solution. It's iOS/MacOS application could be installed as data collecting appliance. It features:

 - ML aware browser with hierarchical tabs
 - In-app and system user actions mining
 - Camera with hands and body poses recognition
