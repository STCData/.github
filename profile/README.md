
```mermaid
flowchart LR
  subgraph iOS & OSX
    c1(STCiOSXDataCollector)
    click c1 href "https://github.com/STCData/STCiOSXDataCollector"
  end
  
  subgraph Linux
    c2(STCX11DataCollector)
  end
  subgraph Android 
    c3(STCDroneDataCollector)
  end
  subgraph Cloud
    s[(STCDataServer)]
  end
    c1 & c2 & c3 -.-> s
```
