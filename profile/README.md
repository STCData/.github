
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

 - Support for video, speech, text and structured data, structured UI screenshots, user actions, human hands and body poses, aerial video human and vehicles mining
 - Data collection applications for [iOS, MacOS], [Android], [Linux]
 - On device real time data pre-labeling using fast [vendor provided] models
 - Realtime data streaming
 - [Data offloading to eventually available servers and pre upload on device data storage balancing]
